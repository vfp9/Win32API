<link rel="stylesheet" type="text/css" href="../../css/win32api.css">  
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

## Functionname : SHGetSpecialFolderLocation
Group: Shell Functions - Library: shell32    
***  


#### Retrieves a pointer to the ITEMIDLIST structure of a special folder.
***  


## Code examples:
[Browsing Windows Known Folders (Special Folders)](../../samples/sample_576.md)  

## Declaration:
```foxpro  
HRESULT SHGetSpecialFolderLocation(
  __in   HWND hwndOwner,
  __in   int nFolder,
  __out  PIDLIST_ABSOLUTE *ppidl
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER SHGetSpecialFolderLocation IN shell32;
	INTEGER hwndOwner,;
	INTEGER nFolder,;
	INTEGER @ppidl
  
```  
***  


## Parameters:
```txt  
hwndOwner [in]
Reserved.

nFolder [in]
A CSIDL value that identifies the folder of interest.

ppidl [out]
A PIDL specifying the folder"s location relative to the root of the namespace (the desktop).  
```  
***  


## Return value:
If the method succeeds, it returns S_OK (0). Otherwise, it returns an HRESULT error code.  
***  


## Comments:
 It is the responsibility of the calling application to free the returned IDList by using CoTaskMemFree.  
  
See also: SHGetFolderPath, SHGetKnownFolderPath, SHGetPathFromIDList   
  
***  
