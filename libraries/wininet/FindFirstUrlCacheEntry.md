<link rel="stylesheet" type="text/css" href="../../css/win32api.css">  
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

## Functionname : FindFirstUrlCacheEntry
Group: Internet Functions (WinInet) - Library: wininet    
***  


#### Begins the enumeration of the Internet cache.
***  


## Code examples:
[How to enumerate cookies and URL History entries in the cache of the local computer](../../samples/sample_350.md)  
[How to delete IE cookies, clear IE history and delete files in Temporary Internet Files directory](../../samples/sample_471.md)  

## Declaration:
```foxpro  
HANDLE FindFirstUrlCacheEntry(
  LPCTSTR lpszUrlSearchPattern,
  LPINTERNET_CACHE_ENTRY_INFO lpFirstCacheEntryInfo,
  LPDWORD lpdwFirstCacheEntryInfoBufferSize
);
  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER FindFirstUrlCacheEntry In wininet;
	STRING  lpszUrlSearchPattern,;
	LONG    lpFirstCacheEntryInfo,;
	LONG  @ lpdwFirstCacheEntryInfoBufferSize
  
```  
***  


## Parameters:
```txt  
lpszUrlSearchPattern
[in] Pointer to a string that contains the source name pattern to search for.

lpFirstCacheEntryInfo
[out] Pointer to an INTERNET_CACHE_ENTRY_INFO structure.

lpdwFirstCacheEntryInfoBufferSize
[in, out] Pointer to a variable that specifies the size of the lpFirstCacheEntryInfo buffer.  
```  
***  


## Return value:
Returns a handle that the application can use in the FindNextUrlCacheEntry function to retrieve subsequent entries in the cache. If the function fails, the return value is NULL.  
***  
