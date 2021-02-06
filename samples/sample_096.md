[<img src="../images/home.png"> 主页 ](https://github.com/VFP9/Win32API)  

# 当前系统信息

## 代码：
```foxpro  
DECLARE GetSystemInfo IN kernel32 STRING @lpSystemInfo
	
*| typedef struct _SYSTEM_INFO {
*|   union {
*|     DWORD  dwOemId;
*|     struct {
*|       WORD wProcessorArchitecture;
*|       WORD wReserved;
*|     };
*|   };
*|   DWORD  dwPageSize;
*|   LPVOID lpMinimumApplicationAddress;
*|   LPVOID lpMaximumApplicationAddress;
*|   DWORD_PTR dwActiveProcessorMask;
*|   DWORD dwNumberOfProcessors;
*|   DWORD dwProcessorType;
*|   DWORD dwAllocationGranularity;
*|   WORD wProcessorLevel;
*|   WORD wProcessorRevision;
*| } SYSTEM_INFO;

PRIVATE cSysInfo, nOffs
	
cSysInfo = Repli(Chr(0), 1024)
= GetSystemInfo(@cSysInfo)

CREATE CURSOR cs (varname C(24), prm N(12), descr C(100))
nOffs = 1

= AddParam("dwOemId",;
"用于与Windows NT 3.5和更早版本兼容", 4)

= AddParam("wProcessorArchitecture",;
"指定系统处理器架构", 2)

= AddParam("wReserved", "保留供今后使用", 2)

= AddParam("dwPageSize",;
"页面大小以及页面保护和承诺的颗粒度", 4)

= AddParam("lpMinimumApplicationAddress",;
"指向应用程序和DLL可访问的最低内存地址的指针", 2)

= AddParam("lpMaximumApplicationAddress",;
"指向应用程序和DLLs可访问的最高内存地址的指针", 2)

= AddParam("dwActiveProcessorMask",;
"Bit 0 is processor 0; bit 31 is processor 31", 4)

= AddParam("dwNumberOfProcessors",;
"Number of processors in the system", 4)

= AddParam("dwProcessorType",;
"An obsolete member", 4)

= AddParam("dwAllocationGranularity",;
"Virtual memory granularity", 4)

= AddParam("wProcessorLevel",;
"Valid for Windows NT/2000 or later", 2)

= AddParam("wProcessorRevision",;
"Valid for Windows NT/2000 or later", 2)

SELECT cs
GO TOP
BROWSE NORMAL NOWAIT
* 主程序结束

PROCEDURE AddParam(cVarname, cDescr, nLen)
	IF nLen = 2
		nParam = buf2word(SUBSTR(cSysInfo, nOffs, 2))
		nOffs = nOffs + 2
	ELSE
		nParam = buf2dword(SUBSTR(cSysInfo, nOffs, 4))
		nOffs = nOffs + 4
	ENDIF
	INSERT INTO cs VALUES (cVarname, nParam, cDescr)

FUNCTION buf2dword(lcBuffer)
RETURN Asc(SUBSTR(lcBuffer, 1,1)) + ;
	Asc(SUBSTR(lcBuffer, 2,1)) * 256 +;
	Asc(SUBSTR(lcBuffer, 3,1)) * 65536 +;
	Asc(SUBSTR(lcBuffer, 4,1)) * 16777216

FUNCTION buf2word(lcBuffer)
RETURN Asc(SUBSTR(lcBuffer, 1,1)) + ;
	Asc(SUBSTR(lcBuffer, 2,1)) * 256  
```  
***  


## 函数列表：
[GetSystemInfo](../libraries/kernel32/GetSystemInfo.md)  
