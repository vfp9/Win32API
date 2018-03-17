<link rel="stylesheet" type="text/css" href="../../css/win32api.css">  
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

## Functionname : DestroyMenu
Group: Menu - Library: user32    
***  


#### The DestroyMenu function destroys the specified menu and frees any memory that the menu occupies.
***  


## Code examples:
[Attaching menu to a top-level form](../../samples/sample_208.md)  
[Shortcut Menu Class](../../samples/sample_419.md)  

## Declaration:
```foxpro  
BOOL DestroyMenu(
  HMENU hMenu  // handle to menu
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER DestroyMenu IN user32;
	INTEGER hMenu  
```  
***  


## Parameters:
```txt  
hMenu
[in] Handle to the menu to be destroyed.  
```  
***  


## Return value:
If the function succeeds, the return value is nonzero. If the function fails, the return value is zero.  
***  


## Comments:
DestroyMenu is recursive, that is, it will destroy the menu and all its submenus.  
  
***  
