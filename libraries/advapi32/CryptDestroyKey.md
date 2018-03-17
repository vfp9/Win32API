<link rel="stylesheet" type="text/css" href="../../css/win32api.css">  
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

## Functionname : CryptDestroyKey
Group: Cryptography Reference - Library: advapi32    
***  


#### Releases the handle referenced by the hKey parameter. After a key handle has been released, it becomes invalid and cannot be used again.
***  


## Code examples:
[CryptoAPI: Collection of Providers class](../../samples/sample_463.md)  
[A class that encrypts and decrypts files using Cryptography API Functions](../../samples/sample_511.md)  
[Generating random cryptographic keys](../../samples/sample_590.md)  

## Declaration:
```foxpro  
BOOL WINAPI CryptDestroyKey(
	HCRYPTKEY hKey
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER CryptDestroyKey IN advapi32;
	INTEGER hKey  
```  
***  


## Parameters:
```txt  
hKey
[in] Handle of the key to be destroyed.  
```  
***  


## Return value:
If the function succeeds, the return value is nonzero (TRUE).  
***  


## Comments:
Keys take up both operating system"s memory space and the CSP"s memory space. Some CSPs are implemented in hardware with limited memory resources. Applications must destroy all keys with the CryptDestroyKey function when they are finished with them.  
  
***  
