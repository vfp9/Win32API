<link rel="stylesheet" type="text/css" href="../../css/win32api.css">  
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

## Functionname : CloseEnhMetaFile
Group: Metafile - Library: gdi32    
***  


#### The CloseEnhMetaFile function closes an enhanced-metafile device context and returns a handle that identifies an enhanced-format metafile.
***  


## Code examples:
[Storing screen shot of a form to enhanced metafile (*.emf)](../../samples/sample_402.md)  
[Copying picture of the active form to the Clipboard using Enhanced Metafile API functions](../../samples/sample_404.md)  
[How to print FoxPro form -- II](../../samples/sample_406.md)  

## Declaration:
```foxpro  
HENHMETAFILE CloseEnhMetaFile(
  HDC hdc   // handle to enhanced-metafile DC
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER CloseEnhMetaFile IN gdi32;
	INTEGER hdc
  
```  
***  


## Parameters:
```txt  
hdc
[in] Handle to an enhanced-metafile device context.  
```  
***  


## Return value:
If the function succeeds, the return value is a handle to an enhanced metafile.  
***  


## Comments:
When the application no longer needs the enhanced metafile handle, it should release the handle by calling the DeleteEnhMetaFile function.   
  
***  
