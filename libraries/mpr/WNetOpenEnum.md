<link rel="stylesheet" type="text/css" href="../../css/win32api.css">  
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

## Functionname : WNetOpenEnum
Group: Windows Networking - Library: mpr    
***  


#### The WNetOpenEnum function starts an enumeration of network resources or existing connections. You can continue the enumeration by calling the WNetEnumResource function.
***  


## Code examples:
[Enumerating network resources](../../samples/sample_313.md)  

## Declaration:
```foxpro  
DWORD WNetOpenEnum(
  DWORD dwScope,                // scope of enumeration
  DWORD dwType,                 // resource types to list
  DWORD dwUsage,                // resource usage to list
  LPNETRESOURCE lpNetResource,  // resource structure
  LPHANDLE lphEnum              // enumeration handle buffer
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER WNetOpenEnum IN mpr;
	INTEGER   dwScope,;
	INTEGER   dwType,;
	INTEGER   dwUsage,;
	INTEGER   lpNetResource,;
	INTEGER @ lphEnum  
```  
***  


## Parameters:
```txt  
dwScope
[in] Specifies the scope of the enumeration.

dwType
[in] Specifies the resource types to enumerate.

dwUsage
[in] Specifies the resource usage type to enumerate.

lpNetResource
[in] Pointer to a NETRESOURCE structure that specifies the container to enumerate.

lphEnum
[out] Pointer to an enumeration handle that can be used in a subsequent call to WNetEnumResource.
  
```  
***  


## Return value:
If the function succeeds, the return value is NO_ERROR.   
***  
