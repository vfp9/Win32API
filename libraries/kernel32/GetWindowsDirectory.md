<link rel="stylesheet" type="text/css" href="../../css/win32api.css">  
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

## Functionname : GetWindowsDirectory
Group: System Information - Library: kernel32    
***  


#### The GetWindowsDirectory function retrieves the path of the Windows directory. The Windows directory contains such files as applications, initialization files, and help files.

***  


## Code examples:
[Obtaining the System and Windows folder names](../../samples/sample_005.md)  
[Reading data from INI files](../../samples/sample_133.md)  

## Declaration:
```foxpro  
UINT GetWindowsDirectory(
  LPTSTR lpBuffer,  // buffer for Windows directory
  UINT uSize        // size of directory buffer
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER GetWindowsDirectory IN kernel32;
	STRING @ lpBuffer,;
	INTEGER  nSize  
```  
***  


## Parameters:
```txt  
lpBuffer
[out] Pointer to the buffer to receive the null-terminated string containing the path

uSize
[in] Specifies the maximum size of the buffer  
```  
***  


## Return value:
If the function succeeds, the return value specifies the number of characters written to the buffer, not including the terminating null character  
***  


## Comments:
Alternatives to calling this API function:  
<div class="precode">? GETENV("windir")  
? GETENV("SystemRoot")  
</div>  
See also: GetSystemDirectory, SHGetFolderPath   
  
***  
