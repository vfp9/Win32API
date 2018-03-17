<link rel="stylesheet" type="text/css" href="../../css/win32api.css">  
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

## Functionname : AVIStreamGetFrameOpen
Group: Windows Multimedia - Library: avifil32    
***  


#### The AVIStreamGetFrameOpen function prepares to decompress video frames from the specified video stream.
***  


## Code examples:
[How to play AVI file on the _screen](../../samples/sample_430.md)  
[How to extract frames from AVI files](../../samples/sample_484.md)  

## Declaration:
```foxpro  
STDAPI_(PGETFRAME) AVIStreamGetFrameOpen(
  PAVISTREAM pavi,
  LPBITMAPINFOHEADER lpbiWanted
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER AVIStreamGetFrameOpen IN avifil32;
	INTEGER pavi,;
	INTEGER lpbiWanted
  
```  
***  


## Parameters:
```txt  
pavi
Pointer to the video stream used as the video source.

lpbiWanted
Pointer to a structure that defines the desired video format. Specify NULL to use a default format.
  
```  
***  


## Return value:
Returns a GetFrame object that can be used with the AVIStreamGetFrame function.  
***  
