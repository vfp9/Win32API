<link rel="stylesheet" type="text/css" href="../../css/win32api.css">  
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

## Functionname : MapViewOfFile
Group: File Mapping - Library: kernel32    
***  


#### The MapViewOfFile function maps a view of a file mapping into the address space of the calling process.
***  


## Code examples:
[Using File Mapping for enumerating files opened by Visual FoxPro](../../samples/sample_473.md)  
[Using shared memory to exchange data between applications (processes)](../../samples/sample_498.md)  

## Declaration:
```foxpro  
LPVOID MapViewOfFile(
  HANDLE hFileMappingObject,
  DWORD dwDesiredAccess,
  DWORD dwFileOffsetHigh,
  DWORD dwFileOffsetLow,
  SIZE_T dwNumberOfBytesToMap
);
  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE LONG MapViewOfFile IN kernel32;
	INTEGER hFileMappingObject,;
	INTEGER dwDesiredAccess,;
	LONG    dwFileOffsetHi,;
	LONG    dwFileOffsetLo,;
	LONG    dwNumberOfBytesToMap
  
```  
***  


## Parameters:
```txt  
hFileMappingObject
[in] Handle to an open handle of a file mapping object. The CreateFileMapping and OpenFileMapping functions return this handle.

dwDesiredAccess
[in] Type of access to the file mapping object, and therefore, the protection of the pages.

dwFileOffsetHigh
[in] High-order DWORD of the file offset where the view is to begin.

dwFileOffsetLow
[in] Low-order DWORD of the file offset where the view is to begin.

dwNumberOfBytesToMap
[in] Number of bytes of the file mapping to map to the view.  
```  
***  


## Return value:
If the function succeeds, the return value is the starting address of the mapped view.  
***  


## Comments:
Mapping a file makes the specified portion of the file visible in the address space of the calling process.  
  
For files that are larger than your address space, you can only map a small portion of the file data at a time. When you are through with the first view, then you unmap it and map a new view.  
  
Read an article on the Miscrosoft Help And Support web site: <a href="http://support.microsoft.com/default.aspx?scid=kb;en-us;188535">HOWTO: Sharing Data Between Processes Using Memory-Mapped Files</a>  
  
See also: MapViewOfFileEx, OpenFileMapping, UnmapViewOfFile.  
  
***  
