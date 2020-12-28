[<img src="images/home.png"> Home ](https://github.com/vfp9/Win32API)  


# 按分组的示例列表
_翻译:xinjie  from 2020.12.27 to ..._

# ![](images/fox1.png) 原子(Atom)

## [检索全局原子名（Global Atom names）](samples/sample_116.md)

# ![](images/fox1.png) 认证方式

## [Smart Card 数据查询函数](samples/sample_539.md)

# ![](images/fox1.png) 权限

## [如何为应用程序启用 SE_SHUTDOWN_NAME 权限](samples/sample_552.md)
要关闭或重启系统（API 调用 ExitWindowsEx、InitiateShutdown 等），进程必须拥有 SE_SHUTDOWN_NAME 权限（Vista 的默认行为）。 
## [如何加载用户配置文件（user profile）](samples/sample_602.md)

## [读取和设置当前进程的系统访问权限](samples/sample_554.md)

# ![](images/fox1.png) 位图（Bitmap）

## [VFP 的 Bitmap Class](samples/sample_295.md)

## [转换图像文件到图标文件（ICO）](samples/sample_503.md)
此代码示例演示如何加载图像文件（BMP，GIF，JPEG，PNG，TIFF），缩放图像并将其另存为.ICO文件。 它创建一个简单的图标文件，其中包含一个32x32图标（每像素32位），并将新图标分配给Icon属性。  
## [使用增强的 Metafile API 函数将活动表单的图片复制到剪贴板。](samples/sample_404.md)

## [使用 BitBlt 和 StretchBlt 函数在 FoxPro 表单中显示动画图像。](samples/sample_355.md)

## [使用 AlphaBlend 函数显示位图](samples/sample_293.md)

## [使用 LoadBitmap 函数绘制 Windows 预定义位图](samples/sample_253.md)

## [表单放大镜](samples/sample_414.md)

## [GDI+: 将活动的 VFP 表单/图片文件拷贝到剪贴板](samples/sample_457.md)

## [GDI+: 如何可视化的抖动 VFP 控件](samples/sample_526.md)
抖动控制可能是吸引用户立即注意的好方法。 例如，当“采购订单”表单打开并且未输入或未输入运输日期时，对应的文本框可能会开始抖动，这样更容易使用户注意到问题。
## [GDI+: 将 FoxPro 表单的图像保存到图形文件中 (BMP, GIF, JPG, PNG, TIF)](samples/sample_454.md)

## [GDI+: 打印表单](samples/sample_455.md)

## [如何将位图文件转换为单色格式(1 bpp)](samples/sample_493.md)
这一切都源于我在 Universal Thread Visual FoxPro 论坛上注意到的一个问题：*有谁知道如何从VFP报告中创建一个单色位图或单色tiff文件？*
  
## [如何使用 Bitmap API 函数将表单的图像复制到剪贴板上](samples/sample_091.md)

## [如何让 VFP 表单在释放时渐渐消失(GDI版)](samples/sample_528.md)
当一个 VFP 表单被释放时，通常它会立即消失。如果能让表单慢慢（或不那么慢）消失，不是很好吗？

一个显而易见的方法是用另一个窗口覆盖表单，该窗口拥有原始表单的图像。一旦覆盖后，原表单就消失了。之后，覆盖窗口逐渐改变其不透明度（alpha通道），从不透明（255）到完全透明（0）。 
## [如何让 VFP 表单在释放时渐渐消失(GDI+版)](samples/sample_527.md)
当一个 VFP 表单被释放时，通常它会立即消失。如果能让表单慢慢（或不那么慢）消失，不是很好吗？

一个显而易见的方法是用另一个窗口覆盖表单，该窗口拥有原始表单的图像。一旦覆盖后，原表单就消失了。之后，覆盖窗口逐渐改变其不透明度（alpha通道），从不透明（255）到完全透明（0）。
## [如何打印表单](samples/sample_158.md)

## [如何打印表单 -- II](samples/sample_406.md)

## [如何打印一个位图文件](samples/sample_211.md)

## [如何在表单上实现水平滚动的文本（新闻、标语）](samples/sample_352.md)

## [How to put a vertical text scrolling on the form (a movie cast)](samples/sample_354.md)

## [Placing an arbitrary rectangular area of main VFP window on the Clipboard](samples/sample_081.md)

## [Splash Screen for the VFP application](samples/sample_294.md)

## [Storing content of the Clipboard to a bitmap file](samples/sample_189.md)

## [Storing screen shot of a form to bitmap file](samples/sample_187.md)

## [Storing screen shot of a form to enhanced metafile (*.emf)](samples/sample_402.md)

## [Subclassing CommandButton control to create BackColor property](samples/sample_392.md)

## [Using the GradientFill function](samples/sample_353.md)

## [Using the LoadImage function to have a bitmap file loaded and displayed on VFP main window](samples/sample_210.md)

## [Vertical Label control](samples/sample_398.md)

# ![](images/fox1.png) Brush group

## [Displaying dimmed window behind VFP top-level form](samples/sample_578.md)

## [How to make a VFP form fading out when released (GDI version)](samples/sample_528.md)
When a VFP form is released, usually it disappears immediately. Wouldn`t it be nice to have the form slowly (or less slowly) fading out?

An obvious way of doing that is covering the form with another window, which holds the image of the original form. Once covered, the original form disappears. After that the covering window gradually changes its opacity (alpha channel) from opaque (255) to completely transparent (0).  
## [How to put a horizontal text scrolling on the form (a news line, marquee)](samples/sample_352.md)

## [How to put a vertical text scrolling on the form (a movie cast)](samples/sample_354.md)

## [Subclassing CommandButton control to create BackColor property](samples/sample_392.md)

## [Using FrameRgn for displaying system colors](samples/sample_125.md)

## [Vertical Label control](samples/sample_398.md)

# ![](images/fox1.png) COM group

## [Accessing the list of Windows Recent Documents](samples/sample_094.md)

## [Browsing Windows Known Folders (Special Folders)](samples/sample_576.md)

## [Custom GDI+ class](samples/sample_450.md)

## [Enumerating devices installed on the local machine](samples/sample_545.md)
The PnP manager maintains a device tree that keeps track of the devices in the system.

The device tree contains information about the devices present on the system. The PnP manager builds this tree when the machine boots, using information from drivers and other components, and updates the tree as devices are added or removed.  
## [How to generate GUID values](samples/sample_456.md)

## [Reading and setting explicit Application User Model ID for the current process (Win7)](samples/sample_038.md)

## [Smart Card Database Query Functions](samples/sample_539.md)

## [Winsock: retrieving information about available transport protocols](samples/sample_223.md)

# ![](images/fox1.png) Clipboard group

## [Bitmap Class for Visual FoxPro application](samples/sample_295.md)

## [Converting Unicode data from the Clipboard to a character string using a given code page](samples/sample_316.md)

## [Copying picture of the active form to the Clipboard using Enhanced Metafile API functions](samples/sample_404.md)

## [Enumerating data formats currently available on the clipboard](samples/sample_032.md)

## [GDI+: Storing content of the Clipboard to a bitmap file](samples/sample_475.md)
Based on GdiPlus class, this code shows how to retrieve an image stored on the clipboard and save it to a graphics file in one of GDI+ supported formats, BMP, GIF. PNG, TIFF, JPEG.  
## [GDI+: copying to the Clipboard (a) image of active FoxPro window/form, (b) image file](samples/sample_457.md)

## [Getting a bit more than the _CLIPTEXT offers](samples/sample_278.md)

## [How to copy the image of a form to the Clipboard using Bitmap API functions](samples/sample_091.md)

## [How to disable the Windows Clipboard (VFP9)](samples/sample_488.md)
The Windows OS has a mechanism that allows to notify a window when the content of the clipboard changes. Any FoxPro window can be registered as a clipboard viewer. The notifications are actually window messages. And VFP9 handles window messages really good due to extended BINDEVENT() function.  
## [Monitoring clipboard content changes (VFP9)](samples/sample_601.md)

## [Number of clipboard formats available](samples/sample_031.md)

## [Passing data records between VFP applications via the Clipboard](samples/sample_346.md)

## [Placing an arbitrary rectangular area of main VFP window on the Clipboard](samples/sample_081.md)

## [Retrieving names for the registered clipboard formats](samples/sample_268.md)

## [Storing content of the Clipboard to a bitmap file](samples/sample_189.md)

## [Testing Clipboard functions: emptying the clipboard](samples/sample_028.md)

## [Who is the first in viewing the Clipboard](samples/sample_030.md)

## [Who owns the Windows Clipboard](samples/sample_029.md)

# ![](images/fox1.png) Color group

## [Using GetNearestColor](samples/sample_044.md)

# ![](images/fox1.png) Common Dialog Box group

## [Creating the Open dialog box to specify the drive, directory, and name of a file to open](samples/sample_363.md)

## [Creating the Save dialog box to specify the drive, directory, and name of a file to save](samples/sample_265.md)

## [Enhanced GetFont dialog](samples/sample_159.md)

## [Extracting the name and extension parts of a path string](samples/sample_118.md)

## [FindText -- the hopeless and useless Common Dialog](samples/sample_160.md)

## [GDI+: printing image file](samples/sample_452.md)

## [GDI+: sending image of FoxPro form to printer](samples/sample_455.md)

## [How to display a Task Dialog (Vista)](samples/sample_557.md)

## [How to display advanced Task Dialog (Vista)](samples/sample_558.md)

## [How to display the Print property sheet](samples/sample_531.md)

## [How to print FoxPro form](samples/sample_158.md)

## [How to print FoxPro form -- II](samples/sample_406.md)

## [How to print a bitmap file](samples/sample_211.md)

## [How to print picture stored in enhanced-format metafile (*.emf)](samples/sample_405.md)

## [Opening the Page Setup dialog box to specify the attributes of a printed page](samples/sample_272.md)

## [Retrieving Printer Device Context using PrintDlg function](samples/sample_150.md)

## [Retrieving graphic capabilities of default printer](samples/sample_155.md)

## [Using the ChooseColor function](samples/sample_264.md)

# ![](images/fox1.png) Console group

## [Creating a console window for Visual FoxPro application](samples/sample_474.md)
The code explains how to create and use console (DOS-like) window with Visual FoxPro application.  
## [Saying "Hello World!" with VFP and WinAPI](samples/sample_119.md)

# ![](images/fox1.png) Coordinate Space and Transformation group

## [Form Magnifier](samples/sample_414.md)

# ![](images/fox1.png) Cryptography Reference group

## [A class that encrypts and decrypts files using Cryptography API Functions](samples/sample_511.md)
This simple class uses several Cryptography API Functions to implement password-protected encryption and decryption of files.  
## [CryptoAPI: Collection of Providers class](samples/sample_463.md)
The CryptoAPI Providers class presents collection of cryptographic service providers (CSP) available on a computer. Each provider is described with type, name, collections of available containers and algorithms.  
## [Generating random cryptographic keys](samples/sample_590.md)
The CryptKeyHelper class defined in the code sample below is a wrapper around Windows API Cryptography functions. It implements methods allowing to generate a random cryptographic key, to export the key to a specified file, and to import a key from a specified file.  
## [How to create MD-5 and SHA-1 hash values from a string](samples/sample_483.md)
MD-5 is a one-way message-digest hash function. The algorithm processes input text and creates a 128-bit message digest which is unique to the message and can be used to verify data integrity. The example shows how to create an MD-5 hash for a string using CryptoAPI calls.  
## [How to fill a buffer with random bytes using Cryptography API Functions](samples/sample_053.md)

## [How to perform Base64 encoding/decoding using Cryptography API Functions](samples/sample_088.md)

## [Verifying a file using the Authenticode policy provider](samples/sample_569.md)

# ![](images/fox1.png) Cursor group

## [Clipping mouse cursor area](samples/sample_080.md)
Mauricio Henao Romero
maohenao@hotmail.com
http://www.codefox.net/modules.php?name=News&file=article&sid=193  
## [Creating a clipping region from the path selected into the device context of a form](samples/sample_144.md)

## [Form Magnifier](samples/sample_414.md)

## [GDI+: Implementing image scrolling with inertia](samples/sample_595.md)
The inertial scrolling can be described as below: 
After releasing the mouse button, the image scrolling coninues while decelerating slowly, simulating the presence of inertia. The level of the deceleration depends on the momentum the mouse cursor obtains at the button release.
  
## [Hiding mouse cursor](samples/sample_139.md)

## [Retrieving the rectangle area where the mouse cursor is confined](samples/sample_074.md)

## [Shortcut Menu Class](samples/sample_419.md)

## [Storing screen shot of a form to bitmap file](samples/sample_187.md)

## [Tracking mouse movement to detect when to start dragging](samples/sample_281.md)

## [Using FoxTray ActiveX control: System Tray Icon and menu attached to VFP form](samples/sample_336.md)

# ![](images/fox1.png) Data Decompression Library group

## [Compressing and decompressing files with Windows API Runtime Library routines](samples/sample_568.md)

# ![](images/fox1.png) Debugging group

## [Moving shortcut to a specified position on the Windows Desktop](samples/sample_581.md)

## [Obtaining names and positions for shortcuts located on the Windows Desktop](samples/sample_579.md)

# ![](images/fox1.png) Desktop Window Manager (DWM) group

## [Customizing the frame of top-level form: removing the standard frame (VFP9, Vista)](samples/sample_574.md)

# ![](images/fox1.png) Device Context group

## [An alternative way of setting Form.Closable to False](samples/sample_127.md)

## [Bitmap Class for Visual FoxPro application](samples/sample_295.md)

## [Configuring DEVMODE structure for a printer](samples/sample_384.md)

## [Converting image file to .ICO file](samples/sample_503.md)
This code sample shows how to load an image file (BMP, GIF, JPEG, PNG, TIFF), scale it and save as .ICO file. It creates a simple icon file containing one 32x32 icon in 32 bit per pixel format and assigns the new icon to the Icon property.  
## [Converting twips to pixels and vice versa](samples/sample_161.md)

## [Copying picture of the active form to the Clipboard using Enhanced Metafile API functions](samples/sample_404.md)

## [Creating a clipping region from the path selected into the device context of a form](samples/sample_144.md)

## [Creating a device context for the specified printer](samples/sample_145.md)

## [Creating a window using CreateWindowEx function](samples/sample_050.md)

## [Custom GDI+ class](samples/sample_450.md)

## [Displaying animated images on FoxPro form with BitBlt and StretchBlt functions](samples/sample_355.md)

## [Displaying bitmap using the AlphaBlend function](samples/sample_293.md)

## [Displaying dimmed window behind VFP top-level form](samples/sample_578.md)

## [Displaying the associated icons and descriptions for files and folders](samples/sample_530.md)
When the list of files and folders is to be displayed inside a VFP form, the ListBox VFP control and the ListView ActiveX control are probably the first two candidates for the job. 

The ListBox`s presentation style can only be described as the minimalistic :) , while the ListView shows items in much fancier manner, and can even accompany each file and folder with an icon.

<img src="images/sysimagelist.png" width=507 height=338>
And an imminent question arises: where are those icons stored and how to put them to work?  
## [Drawing Windows frame controls using the DrawFrameControl function](samples/sample_254.md)

## [Drawing Windows predefined bitmaps using the LoadBitmap functions](samples/sample_253.md)

## [Drawing a rectangle using Windows regular edges and borders](samples/sample_256.md)

## [Drawing a window caption using the DrawCaption routine](samples/sample_238.md)

## [Drawing cursors for the classes defined by the system (preregistered): BUTTON, EDIT, LISTBOX etc.](samples/sample_203.md)

## [Drawing icons associated with the VFP main window](samples/sample_202.md)

## [Drawing standard Windows icons](samples/sample_112.md)

## [Form Magnifier](samples/sample_414.md)

## [GDI+ fun: roach-infested desktop](samples/sample_548.md)

## [GDI+: Color Transparency](samples/sample_549.md)
With the GDI+, an image can be drawn on a Graphics object having a selected single color or a range of colors made transparent.  
## [GDI+: Creating thumbnails to preview images in a directory](samples/sample_547.md)
This code sample displays thumbnails for JPEG images found in a specified directory. The thumbnails on the form are dynamically highlighted following the movements of the cursor.  
## [GDI+: Implementing image scrolling with inertia](samples/sample_595.md)
The inertial scrolling can be described as below: 
After releasing the mouse button, the image scrolling coninues while decelerating slowly, simulating the presence of inertia. The level of the deceleration depends on the momentum the mouse cursor obtains at the button release.
  
## [GDI+: Scrolling through large image using the mouse](samples/sample_546.md)

## [GDI+: copying to the Clipboard (a) image of active FoxPro window/form, (b) image file](samples/sample_457.md)

## [GDI+: custom control, base class](samples/sample_599.md)

## [GDI+: how to make VFP controls visually shake and shudder](samples/sample_526.md)
Shuddering control may appear a good way to get user`s immediate attention. For example, when Purchase Order form opens, and the shipping date is not entered or overdue, the textbox hosting this value may start vibrate and thus can be easily spotted by the user.  
## [GDI+: printing image file](samples/sample_452.md)

## [GDI+: saving image of FoxPro form to graphics file (BMP, GIF, JPG, PNG, TIF)](samples/sample_454.md)

## [GDI+: sending image of FoxPro form to printer](samples/sample_455.md)

## [How to change display settings: screen resolution, screen refresh rate](samples/sample_374.md)
Even if it is not always bright idea to change display resolution from your application, still it is comfortable to know that there is a way to do it.  
## [How to change the name and the size of the font in the MessageBox dialog](samples/sample_434.md)

## [How to convert a bitmap file to monochrome format (1 bpp)](samples/sample_493.md)
It all started with a question I have noticed in the Universal Thread Visual FoxPro forum:*Does anyone know how to create a monochrome bitmap or monochrome tiff file from a VFP report? *
  
## [How to copy the image of a form to the Clipboard using Bitmap API functions](samples/sample_091.md)

## [How to create transparent areas inside a form -- punching holes in the form](samples/sample_126.md)

## [How to detect if additional monitor is connected and active](samples/sample_542.md)
Nowadays having two monitors connected to a PC becomes more a common place rather than exception. This code sample explains how to detect all available monitors through enumerating display devices and their properties.  
## [How to display picture stored in enhanced-format metafile (*.emf)](samples/sample_403.md)

## [How to draw custom Window Caption on FoxPro form](samples/sample_499.md)
This code sample shows how to hide the Caption and the border of FoxPro form and replace them with eight Image controls and one Label control. The form is resizable, closable and can be clicked on its caption and dragged.
  
## [How to find which fonts Windows uses for drawing captions, menus and message boxes](samples/sample_556.md)
Calling SystemParametersInfo with SPI_GETNONCLIENTMETRICS input parameter populates the NONCLIENTMETRICS structure. This structure contains the metrics associated with the nonclient area of a nonminimized window. Among the metrics included are the settings for 5 fonts, the OS uses for drawing captions, small captions, menus, status bars and message boxes.  
## [How to make a VFP form fading out when released (GDI version)](samples/sample_528.md)
When a VFP form is released, usually it disappears immediately. Wouldn`t it be nice to have the form slowly (or less slowly) fading out?

An obvious way of doing that is covering the form with another window, which holds the image of the original form. Once covered, the original form disappears. After that the covering window gradually changes its opacity (alpha channel) from opaque (255) to completely transparent (0).  
## [How to make a VFP form fading out when released (GDI+ version)](samples/sample_527.md)
When a VFP form is released, usually it disappears immediately. Wouldn`t it be nice to have the form slowly (or less slowly) fading out?

An obvious way of doing that is covering the form with another window, which holds the image of the original form. Once covered, the original form disappears. After that the covering window gradually changes its opacity (alpha channel) from opaque (255) to completely transparent (0).  
## [How to play AVI file on the _screen](samples/sample_430.md)

## [How to print FoxPro form](samples/sample_158.md)

## [How to print FoxPro form -- II](samples/sample_406.md)

## [How to print a bitmap file](samples/sample_211.md)

## [How to print picture stored in enhanced-format metafile (*.emf)](samples/sample_405.md)

## [How to put a horizontal text scrolling on the form (a news line, marquee)](samples/sample_352.md)

## [How to put a vertical text scrolling on the form (a movie cast)](samples/sample_354.md)

## [How to view icons stored in executable files (Icon Viewer)](samples/sample_113.md)

## [How to view icons stored in executable files (Icon Viewer) - II](samples/sample_019.md)

## [Obtaining the bounding rectangle for the specified device context](samples/sample_237.md)

## [Placing On-screen Alert on top of all windows](samples/sample_504.md)
Sometimes I think that the WAIT WINDOW has insufficient appeal. Too ordinary look may cause the message passed unnoticed. So if one wants to treat the users with a real stuff, he should use the On-screen Alert.

The idea is simple -- the always-on-top window with transparent background. A combination of window styles makes it not just visually transparent, but also transparent for the keyboard and mouse messages.  
## [Placing an arbitrary rectangular area of main VFP window on the Clipboard](samples/sample_081.md)

## [Printing Image File, programmatically set print page orientation to landscape](samples/sample_555.md)

## [Printing text on the client area of the main VFP window](samples/sample_034.md)

## [Printing text on the main VFP window](samples/sample_035.md)

## [Printing text with the Escape function](samples/sample_357.md)

## [Reading metrics for the currently selected font](samples/sample_339.md)

## [Reading the structure of VFP main menu](samples/sample_337.md)

## [Retrieving Printer Device Context using PrintDlg function](samples/sample_150.md)

## [Retrieving graphic capabilities of default printer](samples/sample_155.md)

## [Retrieving graphic capabilities of your display](samples/sample_188.md)

## [Round FoxPro form](samples/sample_143.md)

## [Splash Screen for the VFP application](samples/sample_294.md)

## [Storing content of the Clipboard to a bitmap file](samples/sample_189.md)

## [Storing screen shot of a form to bitmap file](samples/sample_187.md)

## [Storing screen shot of a form to enhanced metafile (*.emf)](samples/sample_402.md)

## [Subclassing CommandButton control to create BackColor property](samples/sample_392.md)

## [The original LoadPicture() function in VFP returns valid handles to bitmaps, icons, cursors, and metafiles](samples/sample_296.md)

## [Using Common Controls: the Header Control](samples/sample_298.md)

## [Using Font and Text functions](samples/sample_304.md)

## [Using FrameRgn for displaying system colors](samples/sample_125.md)

## [Using GetNearestColor](samples/sample_044.md)

## [Using the DrawText function](samples/sample_303.md)

## [Using the GradientFill function](samples/sample_353.md)

## [Using the LoadImage function to have a bitmap file loaded and displayed on VFP main window](samples/sample_210.md)

## [Vertical Label control](samples/sample_398.md)

# ![](images/fox1.png) Device Input and Output group

## [Obtaining physical parameters for a drive: sectors, clusters, cylinders...](samples/sample_101.md)
The code shows how to obtain number of cylinders, tracks, sectors and clusters for a given device like HD, floppy or CD.  
# ![](images/fox1.png) Dialog Box group

## [Extended MessageBox Class](samples/sample_418.md)

## [How to change the name and the size of the font in the MessageBox dialog](samples/sample_434.md)

## [How to display a user-defined icon in the MessageBox dialog](samples/sample_500.md)

## [Using the MessageBox Win32 function](samples/sample_048.md)

# ![](images/fox1.png) Dynamic-Link Library group

## [Creating a unique filename based on existing filename](samples/sample_014.md)

## [Displaying dimmed window behind VFP top-level form](samples/sample_578.md)

## [Displaying icons in the system tray (VFP9)](samples/sample_235.md)

## [Drawing icons associated with the VFP main window](samples/sample_202.md)

## [Exporting DLL icon resources as .ICO files](samples/sample_502.md)
This code includes definitions for three classes: IconGroups, IconGroupResource and IconResource. The IconGroups is a collection of the IconGroupResource objects. The icons property of the IconGroupResource class is a collection of the IconResource objects.

The IconGroupResource and IconResource classes include SaveToFile method that saves the resource to .ICO file.
  
## [Finding the path to the VFP executable running](samples/sample_086.md)

## [GDI+: Storing DLL icon resources in image files](samples/sample_501.md)

## [GDI+: custom Clock Control](samples/sample_597.md)

## [How to display a user-defined icon in the MessageBox dialog](samples/sample_500.md)

## [How to display the Properties dialog box for a file (ShellExecuteEx)](samples/sample_320.md)

## [How to view icons stored in executable files (Icon Viewer)](samples/sample_113.md)

## [Loading a string resource from an executable file](samples/sample_213.md)

## [Retrieving Window Class information for the VFP window](samples/sample_201.md)

## [Retrieving a handle to DLL and address of an exported function in it](samples/sample_085.md)

## [Retrieving file information for the VFP executable running](samples/sample_242.md)

## [Retrieving information about the main VFP window](samples/sample_111.md)

## [Retrieving information about the specified icon](samples/sample_206.md)

## [Storing registration key in the resources of an executable file](samples/sample_401.md)
This sample shows how to save a registration key -- actually it can be any binary data -- in the resources of any VFP application (executable file) any time after its compilation.

You know about "Other Files" section inside the Project Manager. I think, that would be handy to have a similar section named "Resources", where files like icons, bitmaps, sounds, strings and others could be added. And after the file compiled into an executable, they could be reached through the Resource API calls LoadResource, LoadString, LoadImage and so on.  
## [Using FoxTray ActiveX control: System Tray Icon and menu attached to VFP form](samples/sample_336.md)

## [Using GetBinaryType (WinNT only) to determine the type of an executable file](samples/sample_115.md)

## [Using LoadLibrary](samples/sample_007.md)

# ![](images/fox1.png) Error Handling group

## [A class that encrypts and decrypts files using Cryptography API Functions](samples/sample_511.md)
This simple class uses several Cryptography API Functions to implement password-protected encryption and decryption of files.  
## [Adding printer to the list of supported printers for the specified server](samples/sample_335.md)

## [Basic Volume information](samples/sample_098.md)

## [Capturing keyboard activity of another application with the Raw Input API (VFP9)](samples/sample_572.md)

## [Closing Windows](samples/sample_036.md)

## [Compressing and decompressing files with Windows API Runtime Library routines](samples/sample_568.md)

## [Connecting a local device to a network resource](samples/sample_318.md)

## [Controlling master audio volume by sending WM_APPCOMMAND messages](samples/sample_592.md)
The WM_APPCOMMAND message allows to acquire medium level of control over several OS areas: speakers, microphone, media, browser, mail, default applications. This code sample shows how to mute, unmute and change the volume of the speakers. This technique provides no means of reading the volume level or the mute status.  
## [Converting Unicode data from the Clipboard to a character string using a given code page](samples/sample_316.md)

## [Converting command-line string to a set of Unicode argument strings](samples/sample_212.md)

## [Converting long file names to the short format and vice versa](samples/sample_055.md)

## [Copying files as a transacted operation (Vista)](samples/sample_540.md)

## [Creating a console window for Visual FoxPro application](samples/sample_474.md)
The code explains how to create and use console (DOS-like) window with Visual FoxPro application.  
## [Creating a device context for the specified printer](samples/sample_145.md)

## [Creating a folder](samples/sample_001.md)

## [Creating a mailslot](samples/sample_267.md)

## [CryptoAPI: Collection of Providers class](samples/sample_463.md)
The CryptoAPI Providers class presents collection of cryptographic service providers (CSP) available on a computer. Each provider is described with type, name, collections of available containers and algorithms.  
## [Custom FTP Class for Visual FoxPro application](samples/sample_344.md)

## [Custom HttpRequest class (WinHTTP)](samples/sample_397.md)

## [Custom HttpRequest class (WinINet)](samples/sample_185.md)
This class is used for sending "GET" and "POST" HTTP requests to webserver and receiving responses.  
## [Determining if an Active Network Connection is Available](samples/sample_324.md)

## [DiskFreeSpace class](samples/sample_100.md)

## [Displaying bitmap using the AlphaBlend function](samples/sample_293.md)

## [Displaying dimmed window behind VFP top-level form](samples/sample_578.md)

## [Encapsulating access to the Windows Services in a class](samples/sample_476.md)
The winservices class, subclassed from the Collection class, enumerates Windows Services found in the default service control manager database on local computer. Each item in the collection is an instance of the winservice class that wraps the members of ENUM_SERVICE_STATUS structure for a given service. The winservice object exposes methods StartService, StopService and PauseService.  
## [Enumerating Processes -- WinNT](samples/sample_162.md)

## [Enumerating forms supported by a specified printer](samples/sample_390.md)

## [Enumerating ports that are available for printing on a specified server](samples/sample_334.md)

## [Enumerating print jobs and retrieving information for default printer (JOB_INFO_1 structures)](samples/sample_368.md)

## [Enumerating print processors and supporting data types installed on the specified server](samples/sample_333.md)

## [Enumerating printer drivers installed](samples/sample_082.md)

## [Enumerating the subkeys of a user-specific key](samples/sample_129.md)

## [Finding parameters for the region specified](samples/sample_124.md)

## [Generating random cryptographic keys](samples/sample_590.md)
The CryptKeyHelper class defined in the code sample below is a wrapper around Windows API Cryptography functions. It implements methods allowing to generate a random cryptographic key, to export the key to a specified file, and to import a key from a specified file.  
## [GetFileOwner - Get the owner of an NTFS file](samples/sample_433.md)

## [Getting a bit more than the _CLIPTEXT offers](samples/sample_278.md)

## [HOWTO: Use the Win32 API to Access File Dates and Times](samples/sample_177.md)

## [How to Start a Process as Another User (NT/XP/2K)](samples/sample_426.md)

## [How to access a file using not its name but an alias (hard link)](samples/sample_018.md)

## [How to adjust monitor brightness (Vista, monitor with DDC support)](samples/sample_543.md)
The Monitor Configuration API was first made available in Windows Vista. These functions are applicable only if the monitor supports the Display Data Channel (DDC/CI) connection with the graphics adapter.  
## [How to block the ALT+TAB shortcut (WinXP)](samples/sample_432.md)

## [How to block the PrintScreen key](samples/sample_489.md)
The PrintScreen key sends to the Clipboard either whole screen or just the active window (if pressed together with ALT key). To prevent windows of your application to be captured and printed by users through pressing this key, use RegisterHotKey API function. Still this solution does not provide absolute protection. A determined user may use third-party screen capturing utility that is not associated with the PrintScreen key and the Clipboard.   
## [How to create MD-5 and SHA-1 hash values from a string](samples/sample_483.md)
MD-5 is a one-way message-digest hash function. The algorithm processes input text and creates a 128-bit message digest which is unique to the message and can be used to verify data integrity. The example shows how to create an MD-5 hash for a string using CryptoAPI calls.  
## [How to create a service object](samples/sample_517.md)

## [How to delete IE cookies, clear IE history and delete files in Temporary Internet Files directory](samples/sample_471.md)
The following example presents session class *CacheEntry* and collection class *CacheEntries*. The latter, when created, enumerates Internet cache entries, either cookies or history or cached files depending on the search pattern. Cache entries can be deleted through *DeleteCacheEntry* and *DeleteCacheEntries* methods of the collection class.  
## [How to delete a service object](samples/sample_518.md)

## [How to delete all print jobs for a printer](samples/sample_370.md)

## [How to display a user-defined icon in the MessageBox dialog](samples/sample_500.md)

## [How to display the Properties dialog box for a file (ShellExecuteEx)](samples/sample_320.md)

## [How to display the port-configuration dialog box for a port on the specified server](samples/sample_362.md)

## [How to download this reference`s archive through WinInet functions using InternetOpenUrl](samples/sample_110.md)

## [How to enable the SE_SHUTDOWN_NAME privilege for the application](samples/sample_552.md)
To shut down or to reboot the system (API calls ExitWindowsEx, InitiateShutdown and others) the process must have the SE_SHUTDOWN_NAME privilege (default behaviour on Vista).  
## [How to enumerate cookies and URL History entries in the cache of the local computer](samples/sample_350.md)

## [How to enumerate sessions and processes on a specified terminal server](samples/sample_519.md)

## [How to enumerate terminal servers within the specified Windows domain](samples/sample_520.md)

## [How to extract frames from AVI files](samples/sample_484.md)
The example presents the AviBrowser class. This class can open AVI file and convert its frames into bitmap files. The AviBrowser object is shown used as a control on FoxPro form. For that reason, it is subclassed from the Image control.  
## [How to fill a buffer with random bytes using Cryptography API Functions](samples/sample_053.md)

## [How to find the application associated with a file name](samples/sample_138.md)

## [How to find when the application started](samples/sample_534.md)

## [How to find which fonts Windows uses for drawing captions, menus and message boxes](samples/sample_556.md)
Calling SystemParametersInfo with SPI_GETNONCLIENTMETRICS input parameter populates the NONCLIENTMETRICS structure. This structure contains the metrics associated with the nonclient area of a nonminimized window. Among the metrics included are the settings for 5 fonts, the OS uses for drawing captions, small captions, menus, status bars and message boxes.  
## [How to initiate System shutdown](samples/sample_122.md)

## [How to load a user profile](samples/sample_602.md)

## [How to make application automatically close all documents it opened](samples/sample_491.md)
Imagine FoxPro application that has opened several windows like Word, Excel, PDF, browser, picture viewer etc. Closing all those documents automatically on exit from the application, sometimes this can be a good idea.

Here is one of several possible ways to get it done. Windows XP/2K introduces a Job Object, a tool that can manage a group of processes as a single process. In other words, operations performed on the job object affect all processes associated with it.
  
## [How to make the caption of a VFP application flashing in the Windows task bar](samples/sample_228.md)

## [How to ping a remote site using IP Helper API calls](samples/sample_382.md)

## [How to play AVI file on the _screen](samples/sample_430.md)

## [How to prevent users from accessing the Windows Desktop and from switching to other applications](samples/sample_492.md)
Sometimes you may need a computer with a single application running on it, and with all other applications and resources hidden from users. An example, Indigo Book Store customers can only search books when using public computers in the store.
  
## [How to remove FTP directory](samples/sample_070.md)

## [How to retrieve configuration data for a specified printer stored in the registry (PrinterDriverData key)](samples/sample_369.md)

## [How to retrieve information about a cache entry (Internet Explorer)](samples/sample_332.md)

## [How to retrieve the number of print jobs queued for the printer](samples/sample_367.md)

## [How to retrieve version information for the specified file](samples/sample_480.md)
The FileVersionInfo class encapsulates GetFileVersionInfo API call and provides read-only access to structures VS_VERSIONINFO and VS_FIXEDFILEINFO.  
## [How to run FoxPro application under different user name (impersonating user)](samples/sample_470.md)
This example shows how to switch to another domain user within FoxPro application. It can be used for providing limited access to network resources (files, printers) for network users.  
## [How to save registry key including its subkeys and values to a file](samples/sample_135.md)

## [How to set Creation Date/Time for a folder (WinNT)](samples/sample_399.md)

## [How to test file attributes (key method for FileExists and DirectoryExists routines)](samples/sample_097.md)

## [How to write and read Window Properties for the specified window](samples/sample_205.md)

## [Locking and unlocking file of a VFP table](samples/sample_154.md)

## [Locking the workstation](samples/sample_300.md)

## [Monitoring changes occurring within a directory](samples/sample_400.md)

## [Monitoring clipboard content changes (VFP9)](samples/sample_601.md)

## [Obtaining I/O counts for the current process](samples/sample_535.md)

## [Obtaining physical parameters for a drive: sectors, clusters, cylinders...](samples/sample_101.md)
The code shows how to obtain number of cylinders, tracks, sectors and clusters for a given device like HD, floppy or CD.  
## [Peer-to-peer LAN messenger built with Mailslot API functions](samples/sample_410.md)

## [Placing an arbitrary rectangular area of main VFP window on the Clipboard](samples/sample_081.md)

## [Printing Image File, programmatically set print page orientation to landscape](samples/sample_555.md)

## [Reading and setting system access privileges for the current process](samples/sample_554.md)

## [Reading current hardware profile](samples/sample_134.md)

## [Reading entries from Event logs](samples/sample_524.md)

## [Reading security permissions for NTFS files and folders](samples/sample_516.md)
This code sample includes a set of classes implementing several NTFS access control objects. Through these objects, like Access Control List (ACL) and Access Control Entry (ACE) and others, the OS defines access rights to files, folders (in particular) for different users and user groups.  
## [Reading the structure of VFP main menu](samples/sample_337.md)

## [Retrieveing information about the active window (even if it is not owned by the calling process)](samples/sample_371.md)

## [Retrieving System Error message strings](samples/sample_056.md)

## [Retrieving a handle to DLL and address of an exported function in it](samples/sample_085.md)

## [Retrieving graphic capabilities of default printer](samples/sample_155.md)

## [Retrieving local computer and user names](samples/sample_041.md)

## [Retrieving the System Time adjustment](samples/sample_072.md)

## [Retrieving the name of the default printer for the current user on the local computer (Win NT/XP)](samples/sample_360.md)
This code sample retrieves the name of default printer on local computer and obtains detailed information for this printer in PRINTER_INFO_5 format.   
## [Scanning a hierarchy of child windows down from the Windows Desktop](samples/sample_045.md)

## [Setting default printer](samples/sample_589.md)

## [Setting the Window Region for a form](samples/sample_120.md)

## [Setting the date and time that a file was created](samples/sample_065.md)

## [Setting the last-error code for the FoxPro](samples/sample_058.md)

## [Setting the volume label](samples/sample_151.md)

## [Simple printer queue monitor: deletes, pauses, resumes print jobs for local printer](samples/sample_373.md)

## [Start an executable from VFP application by using the CreateProcess](samples/sample_003.md)

## [Starting external program from VFP and waiting for its termination](samples/sample_377.md)

## [Storing registration key in the resources of an executable file](samples/sample_401.md)
This sample shows how to save a registration key -- actually it can be any binary data -- in the resources of any VFP application (executable file) any time after its compilation.

You know about "Other Files" section inside the Project Manager. I think, that would be handy to have a similar section named "Resources", where files like icons, bitmaps, sounds, strings and others could be added. And after the file compiled into an executable, they could be reached through the Resource API calls LoadResource, LoadString, LoadImage and so on.  
## [Terminating VFP application using the FatalAppExit](samples/sample_229.md)

## [Testing serial ports](samples/sample_308.md)
In Windows all input/output ports are presented as files, so work with ports is performed through file functions like *CreateFile, CloseHandle, ReadFile, ReadFileEx, WriteFile* and *WriteFileEx*.  
## [The DetectAutoProxyUrl function identifies the auto-config script location](samples/sample_341.md)

## [Using Beep and Sleep functions to make the old tin <s>buzz</s> sing (WinNT only?)](samples/sample_240.md)

## [Using Change Notification Objects to monitor changes to the printer or print server](samples/sample_485.md)
The code explains how to use FindFirstPrinterChangeNotification and FindNextPrinterChangeNotification API calls to monitor changes in jobs for a specified local or network printer. Not an easy job for Visual FoxPro, considering its unique attitude to API structures and pointers. This functionality can be used to build a print monitor, though in a way limited by the single-thread nature of Visual FoxPro.  
## [Using EnumPrinters function to enumerate locally installed printers](samples/sample_146.md)

## [Using File Mapping for enumerating files opened by Visual FoxPro](samples/sample_473.md)
*File mapping* is the association of the contents of a file with a portion of the virtual address space of a process. API function GetMappedFileName called in combination with CreateFileMapping and MapViewOfFile functions is able to retrieve the name for a given file handle.  
## [Using FlashWindowEx to flash the taskbar button of the VFP application](samples/sample_271.md)

## [Using FtpCommand](samples/sample_059.md)

## [Using LoadLibrary](samples/sample_007.md)

## [Using MessageBeep](samples/sample_037.md)

## [Using named pipes for interprocess communication](samples/sample_522.md)
This code sample contains definitions of two classes, NamedPipeServer and NamedPipeClient, encapsulating named pipes API functionality. The Pipes, as well as mailslots, can be used for transferring data between processes running on same computer or on different computers.  
## [Using shared memory to exchange data between applications (processes)](samples/sample_498.md)

## [Using the CreateFile](samples/sample_010.md)

## [Using the NetMessageBufferSend to send messages on the network](samples/sample_494.md)
The code sample explains how to broadcast system alerts using the NetMessageBufferSend as an alternative to NET SEND command.  
## [Using the Semaphore object](samples/sample_008.md)

## [Using the Semaphore object to allow only one instance of VFP application running](samples/sample_147.md)

## [Using the SetErrorMode for determining if a floppy drive is ready](samples/sample_227.md)

## [Validating the heap of the calling process](samples/sample_200.md)

## [Wininet last error description](samples/sample_109.md)

## [Winsock: retrieving information from a host database for a given host name](samples/sample_216.md)

## [Writing entries to custom Event Log](samples/sample_564.md)
This code sample explains how to add entries to event logs using Event Logging API.  
# ![](images/fox1.png) Event Logging group

## [Reading entries from Event logs](samples/sample_524.md)

## [Writing entries to custom Event Log](samples/sample_564.md)
This code sample explains how to add entries to event logs using Event Logging API.  
# ![](images/fox1.png) Extensible Storage Engine (ESE, Jet Blue) group

## [Extensible Storage Engine class library](samples/sample_532.md)

# ![](images/fox1.png) File Management group

## [A procedure for setting file times](samples/sample_128.md)

## [Building a tree of subdirectories for a given path using FindFile functions](samples/sample_236.md)

## [Changing file attributes](samples/sample_103.md)

## [Comparing file times](samples/sample_171.md)

## [Converting long file names to the short format and vice versa](samples/sample_055.md)

## [Converting path to original case](samples/sample_102.md)

## [Copying files as a transacted operation (Vista)](samples/sample_540.md)

## [Creating a file, then moving it to another destination](samples/sample_015.md)

## [Creating a folder](samples/sample_001.md)

## [Creating a unique filename based on existing filename](samples/sample_014.md)

## [Current directory of the application](samples/sample_004.md)

## [Detecting changes in connections to removable drives (VFP9)](samples/sample_573.md)

## [Disconnecting USB Mass Storage Device programmatically](samples/sample_553.md)

## [Displaying the drive type value](samples/sample_012.md)

## [HOWTO: Use the Win32 API to Access File Dates and Times](samples/sample_177.md)

## [How to access a file using not its name but an alias (hard link)](samples/sample_018.md)

## [How to convert a bitmap file to monochrome format (1 bpp)](samples/sample_493.md)
It all started with a question I have noticed in the Universal Thread Visual FoxPro forum:*Does anyone know how to create a monochrome bitmap or monochrome tiff file from a VFP report? *
  
## [How to set Creation Date/Time for a folder (WinNT)](samples/sample_399.md)

## [How to test file attributes (key method for FileExists and DirectoryExists routines)](samples/sample_097.md)

## [Locking and unlocking file of a VFP table](samples/sample_154.md)

## [Mapping and disconnecting network drives](samples/sample_387.md)

## [Monitoring changes in a directory](samples/sample_117.md)

## [Monitoring changes occurring within a directory](samples/sample_400.md)

## [Obtaining physical parameters for a drive: sectors, clusters, cylinders...](samples/sample_101.md)
The code shows how to obtain number of cylinders, tracks, sectors and clusters for a given device like HD, floppy or CD.  
## [Passing data records between VFP applications via the Clipboard](samples/sample_346.md)

## [Peer-to-peer LAN messenger built with Mailslot API functions](samples/sample_410.md)

## [Retrieving file information for the VFP executable running](samples/sample_242.md)

## [Retrieving information about MS-DOS device names using QueryDosDevice (WinNT only)](samples/sample_241.md)

## [Retrieving list of available disk drives](samples/sample_013.md)

## [Running MSDOS Shell as a child process with redirected input and output (smarter RUN command)](samples/sample_477.md)
The msdos class allows issuing a set of MSDOS commands and getting back a response as a string. The MSDOS window is present but not visible. The code creates a child process running an msdos session and redirects its standard input and output handles to anonymous pipes.  
## [Searching for the specified file using the SearchPath](samples/sample_250.md)

## [Setting the date and time that a file was created](samples/sample_065.md)

## [Storing content of the Clipboard to a bitmap file](samples/sample_189.md)

## [Storing screen shot of a form to bitmap file](samples/sample_187.md)

## [Subclassing CommandButton control to create BackColor property](samples/sample_392.md)

## [Testing serial ports](samples/sample_308.md)
In Windows all input/output ports are presented as files, so work with ports is performed through file functions like *CreateFile, CloseHandle, ReadFile, ReadFileEx, WriteFile* and *WriteFileEx*.  
## [Using File Mapping for enumerating files opened by Visual FoxPro](samples/sample_473.md)
*File mapping* is the association of the contents of a file with a portion of the virtual address space of a process. API function GetMappedFileName called in combination with CreateFileMapping and MapViewOfFile functions is able to retrieve the name for a given file handle.  
## [Using GetBinaryType (WinNT only) to determine the type of an executable file](samples/sample_115.md)

## [Using GetFileSize](samples/sample_114.md)

## [Using InternetSetFilePointer when resuming interrupted download from the Internet](samples/sample_191.md)

## [Using mailslots to send messages on the network](samples/sample_269.md)

## [Using named pipes for interprocess communication](samples/sample_522.md)
This code sample contains definitions of two classes, NamedPipeServer and NamedPipeClient, encapsulating named pipes API functionality. The Pipes, as well as mailslots, can be used for transferring data between processes running on same computer or on different computers.  
## [Using the CopyFile](samples/sample_009.md)

## [Using the CreateFile](samples/sample_010.md)

## [Using the DeleteFile](samples/sample_011.md)

## [Using the GetLogicalDriveStrings](samples/sample_017.md)

## [Using the GetTempFileName](samples/sample_016.md)

## [Vertical Label control](samples/sample_398.md)

# ![](images/fox1.png) File Mapping group

## [Using File Mapping for enumerating files opened by Visual FoxPro](samples/sample_473.md)
*File mapping* is the association of the contents of a file with a portion of the virtual address space of a process. API function GetMappedFileName called in combination with CreateFileMapping and MapViewOfFile functions is able to retrieve the name for a given file handle.  
## [Using shared memory to exchange data between applications (processes)](samples/sample_498.md)

# ![](images/fox1.png) File System group

## [Basic Volume information](samples/sample_098.md)

## [Detecting changes in connections to removable drives (VFP9)](samples/sample_573.md)

## [Disconnecting USB Mass Storage Device programmatically](samples/sample_553.md)

## [Disk in drive A:](samples/sample_319.md)

## [DiskFreeSpace class](samples/sample_100.md)

## [Enumerating Volumes and Volume Mounting Points (NTFS)](samples/sample_087.md)

## [Obtaining physical parameters for a drive: sectors, clusters, cylinders...](samples/sample_101.md)
The code shows how to obtain number of cylinders, tracks, sectors and clusters for a given device like HD, floppy or CD.  
## [Passing data records between VFP applications via the Clipboard](samples/sample_346.md)

## [Retrieving information about MS-DOS device names using QueryDosDevice (WinNT only)](samples/sample_241.md)

## [Retrieving list of available disk drives](samples/sample_013.md)

## [Setting the volume label](samples/sample_151.md)

## [Using File Mapping for enumerating files opened by Visual FoxPro](samples/sample_473.md)
*File mapping* is the association of the contents of a file with a portion of the virtual address space of a process. API function GetMappedFileName called in combination with CreateFileMapping and MapViewOfFile functions is able to retrieve the name for a given file handle.  
## [Using GetCompressedFileSize (WinNT only)](samples/sample_192.md)

## [Using GetFileSize](samples/sample_114.md)

## [Using InternetSetFilePointer when resuming interrupted download from the Internet](samples/sample_191.md)

## [Using the GetLogicalDriveStrings](samples/sample_017.md)

# ![](images/fox1.png) Filled Shape group

## [How to make a VFP form fading out when released (GDI version)](samples/sample_528.md)
When a VFP form is released, usually it disappears immediately. Wouldn`t it be nice to have the form slowly (or less slowly) fading out?

An obvious way of doing that is covering the form with another window, which holds the image of the original form. Once covered, the original form disappears. After that the covering window gradually changes its opacity (alpha channel) from opaque (255) to completely transparent (0).  
## [How to put a horizontal text scrolling on the form (a news line, marquee)](samples/sample_352.md)

## [How to put a vertical text scrolling on the form (a movie cast)](samples/sample_354.md)

## [Subclassing CommandButton control to create BackColor property](samples/sample_392.md)

## [Vertical Label control](samples/sample_398.md)

# ![](images/fox1.png) Font and Text group

## [Creating a clipping region from the path selected into the device context of a form](samples/sample_144.md)

## [Creating a window using CreateWindowEx function](samples/sample_050.md)

## [How to change the name and the size of the font in the MessageBox dialog](samples/sample_434.md)

## [How to put a horizontal text scrolling on the form (a news line, marquee)](samples/sample_352.md)

## [How to put a vertical text scrolling on the form (a movie cast)](samples/sample_354.md)

## [Placing On-screen Alert on top of all windows](samples/sample_504.md)
Sometimes I think that the WAIT WINDOW has insufficient appeal. Too ordinary look may cause the message passed unnoticed. So if one wants to treat the users with a real stuff, he should use the On-screen Alert.

The idea is simple -- the always-on-top window with transparent background. A combination of window styles makes it not just visually transparent, but also transparent for the keyboard and mouse messages.  
## [Printing text on the client area of the main VFP window](samples/sample_034.md)

## [Printing text on the main VFP window](samples/sample_035.md)

## [Printing text with the Escape function](samples/sample_357.md)

## [Reading metrics for the currently selected font](samples/sample_339.md)

## [Splash Screen for the VFP application](samples/sample_294.md)

## [Subclassing CommandButton control to create BackColor property](samples/sample_392.md)

## [Using Common Controls: the Header Control](samples/sample_298.md)

## [Using Font and Text functions](samples/sample_304.md)

## [Using FrameRgn for displaying system colors](samples/sample_125.md)

## [Using the DrawText function](samples/sample_303.md)

## [Vertical Label control](samples/sample_398.md)

# ![](images/fox1.png) GDI+ group

## [Custom GDI+ class](samples/sample_450.md)

## [GDI+: retrieving list of available image encoders and image decoders](samples/sample_459.md)

# ![](images/fox1.png) GDI+ Bitmap group

## [Custom GDI+ class](samples/sample_450.md)

## [GDI+: Color Transparency](samples/sample_549.md)
With the GDI+, an image can be drawn on a Graphics object having a selected single color or a range of colors made transparent.  
# ![](images/fox1.png) GDI+ Brush group

## [Adding a background image to VFP report (VFP9, ReportListener)](samples/sample_562.md)

## [Custom GDI+ class](samples/sample_450.md)

# ![](images/fox1.png) GDI+ Font group

## [Custom GDI+ class](samples/sample_450.md)

# ![](images/fox1.png) GDI+ Graphics group

## [Adding a background image to VFP report (VFP9, ReportListener)](samples/sample_562.md)

## [Custom GDI+ class](samples/sample_450.md)

## [GDI+ fun: roach-infested desktop](samples/sample_548.md)

## [GDI+: Color Transparency](samples/sample_549.md)
With the GDI+, an image can be drawn on a Graphics object having a selected single color or a range of colors made transparent.  
## [GDI+: Drawing a Pie Chart](samples/sample_514.md)
This code sample shows how to use PieChart GDI+ functions to build a simple chart and store it in a graphics file.  
## [GDI+: Scrolling through large image using the mouse](samples/sample_546.md)

## [GDI+: Using Scale and Shear transformations](samples/sample_479.md)
A transformation is a process that changes graphics objects from one state to another. Rotation, scaling, reflection, translation, and shearing are some examples of transformation. Transformations can be applied to graphics shapes, curves, images and to image colors.
  
# ![](images/fox1.png) GDI+ Image group

## [Adding a background image to VFP report (VFP9, ReportListener)](samples/sample_562.md)

## [Custom GDI+ class](samples/sample_450.md)

## [Displaying the color palette stored in an image file](samples/sample_529.md)
Depending on its bit per pixel mode, an image file can store a color palette inside its data. GDI+ functions GdipGetImagePalette and GdipGetImagePaletteSize allow to retrieve the palette in a form of ColorPalette structure.
  
## [GDI+: reading and writing metadata in JPEG and TIFF files](samples/sample_461.md)
The code shows how to store and retrieve metadata in image files. **Metadata** is defined as *"Data about data, or information known about the image in order to provide access to the image"*. It may be, for example, a shatter speed value for your digital camera or description to a birthday party picture.  
# ![](images/fox1.png) GDI+ ImageAttributes group

## [GDI+: Color Transparency](samples/sample_549.md)
With the GDI+, an image can be drawn on a Graphics object having a selected single color or a range of colors made transparent.  
# ![](images/fox1.png) GDI+ Matrix group

## [Custom GDI+ class](samples/sample_450.md)

## [GDI+: Using Scale and Shear transformations](samples/sample_479.md)
A transformation is a process that changes graphics objects from one state to another. Rotation, scaling, reflection, translation, and shearing are some examples of transformation. Transformations can be applied to graphics shapes, curves, images and to image colors.
  
# ![](images/fox1.png) GDI+ PathGradient Brush group

## [GDI+: creating a gradient](samples/sample_596.md)

# ![](images/fox1.png) GDI+ Pen group

## [Custom GDI+ class](samples/sample_450.md)

# ![](images/fox1.png) GDI+ StringFormat group

## [Custom GDI+ class](samples/sample_450.md)

# ![](images/fox1.png) GDI+ Text group

## [Custom GDI+ class](samples/sample_450.md)

# ![](images/fox1.png) HTTP Functions (WinHTTP) group

## [Custom HttpRequest class (WinHTTP)](samples/sample_397.md)

# ![](images/fox1.png) Handle and Object group

## [Comparing file times](samples/sample_171.md)

## [Copying files as a transacted operation (Vista)](samples/sample_540.md)

## [Creating a console window for Visual FoxPro application](samples/sample_474.md)
The code explains how to create and use console (DOS-like) window with Visual FoxPro application.  
## [Creating a file, then moving it to another destination](samples/sample_015.md)

## [Creating a mailslot](samples/sample_267.md)

## [Enumerating Processes -- Win9*](samples/sample_164.md)

## [Enumerating Processes -- WinNT](samples/sample_162.md)

## [HOWTO: Use the Win32 API to Access File Dates and Times](samples/sample_177.md)

## [How to Start a Process as Another User (NT/XP/2K)](samples/sample_426.md)

## [How to check whether the system is 32-bit or 64-bit](samples/sample_580.md)

## [How to convert a bitmap file to monochrome format (1 bpp)](samples/sample_493.md)
It all started with a question I have noticed in the Universal Thread Visual FoxPro forum:*Does anyone know how to create a monochrome bitmap or monochrome tiff file from a VFP report? *
  
## [How to enable the SE_SHUTDOWN_NAME privilege for the application](samples/sample_552.md)
To shut down or to reboot the system (API calls ExitWindowsEx, InitiateShutdown and others) the process must have the SE_SHUTDOWN_NAME privilege (default behaviour on Vista).  
## [How to find when the application started](samples/sample_534.md)

## [How to load a user profile](samples/sample_602.md)

## [How to make application automatically close all documents it opened](samples/sample_491.md)
Imagine FoxPro application that has opened several windows like Word, Excel, PDF, browser, picture viewer etc. Closing all those documents automatically on exit from the application, sometimes this can be a good idea.

Here is one of several possible ways to get it done. Windows XP/2K introduces a Job Object, a tool that can manage a group of processes as a single process. In other words, operations performed on the job object affect all processes associated with it.
  
## [How to prevent users from accessing the Windows Desktop and from switching to other applications](samples/sample_492.md)
Sometimes you may need a computer with a single application running on it, and with all other applications and resources hidden from users. An example, Indigo Book Store customers can only search books when using public computers in the store.
  
## [How to run FoxPro application under different user name (impersonating user)](samples/sample_470.md)
This example shows how to switch to another domain user within FoxPro application. It can be used for providing limited access to network resources (files, printers) for network users.  
## [How to set Creation Date/Time for a folder (WinNT)](samples/sample_399.md)

## [How to suspend or hibernate your system](samples/sample_395.md)

## [Locking and unlocking file of a VFP table](samples/sample_154.md)

## [Memory usage info for current VFP session (WinNT only)](samples/sample_172.md)

## [Monitoring changes occurring within a directory](samples/sample_400.md)

## [Moving shortcut to a specified position on the Windows Desktop](samples/sample_581.md)

## [Obtaining I/O counts for the current process](samples/sample_535.md)

## [Obtaining names and positions for shortcuts located on the Windows Desktop](samples/sample_579.md)

## [Obtaining physical parameters for a drive: sectors, clusters, cylinders...](samples/sample_101.md)
The code shows how to obtain number of cylinders, tracks, sectors and clusters for a given device like HD, floppy or CD.  
## [Passing data records between VFP applications via the Clipboard](samples/sample_346.md)

## [Peer-to-peer LAN messenger built with Mailslot API functions](samples/sample_410.md)

## [Reading and setting system access privileges for the current process](samples/sample_554.md)

## [Reading and setting the priority class values for the current process and thread](samples/sample_218.md)

## [Retrieving file information for the VFP executable running](samples/sample_242.md)

## [Running MSDOS Shell as a child process with redirected input and output (smarter RUN command)](samples/sample_477.md)
The msdos class allows issuing a set of MSDOS commands and getting back a response as a string. The MSDOS window is present but not visible. The code creates a child process running an msdos session and redirects its standard input and output handles to anonymous pipes.  
## [Setting the date and time that a file was created](samples/sample_065.md)

## [Starting external program from VFP and waiting for its termination](samples/sample_377.md)

## [Storing content of the Clipboard to a bitmap file](samples/sample_189.md)

## [Storing screen shot of a form to bitmap file](samples/sample_187.md)

## [Subclassing CommandButton control to create BackColor property](samples/sample_392.md)

## [Terminating all running applications from a VFP program](samples/sample_243.md)

## [Testing serial ports](samples/sample_308.md)
In Windows all input/output ports are presented as files, so work with ports is performed through file functions like *CreateFile, CloseHandle, ReadFile, ReadFileEx, WriteFile* and *WriteFileEx*.  
## [Using File Mapping for enumerating files opened by Visual FoxPro](samples/sample_473.md)
*File mapping* is the association of the contents of a file with a portion of the virtual address space of a process. API function GetMappedFileName called in combination with CreateFileMapping and MapViewOfFile functions is able to retrieve the name for a given file handle.  
## [Using GetFileSize](samples/sample_114.md)

## [Using InternetSetFilePointer when resuming interrupted download from the Internet](samples/sample_191.md)

## [Using mailslots to send messages on the network](samples/sample_269.md)

## [Using named pipes for interprocess communication](samples/sample_522.md)
This code sample contains definitions of two classes, NamedPipeServer and NamedPipeClient, encapsulating named pipes API functionality. The Pipes, as well as mailslots, can be used for transferring data between processes running on same computer or on different computers.  
## [Using shared memory to exchange data between applications (processes)](samples/sample_498.md)

## [Using the CreateFile](samples/sample_010.md)

## [Using the DeleteFile](samples/sample_011.md)

## [Using the Semaphore object](samples/sample_008.md)

## [Using the Semaphore object to allow only one instance of VFP application running](samples/sample_147.md)

## [Vertical Label control](samples/sample_398.md)

# ![](images/fox1.png) IP Helper group

## [Displaying all TCP connections for the local system](samples/sample_222.md)

## [How to ping a remote site using ICMP API calls](samples/sample_486.md)
The Ping class uses several API functions -- IcmpCreateFile, IcmpCloseHandle, IcmpSendEcho and others -- to send an ICMP Echo request and get a reply (RTT, round-trip time).   
## [How to ping a remote site using IP Helper API calls](samples/sample_382.md)

## [How to release and renew a lease on an IP address previously obtained through Dynamic Host Configuration Protocol (DHCP)](samples/sample_349.md)

## [How to retrieve adapter information for the local computer (including MAC address)](samples/sample_347.md)

## [How to retrieve network parameters for the local computer (including Host name, Domain name, and DNS Server)](samples/sample_348.md)

## [Obtaining MAC address through Address Resolution Protocol (ARP) request](samples/sample_585.md)

## [Obtaining addresses for the adapters on the local computer (Win XP/2003/Vista)](samples/sample_506.md)

## [Retrieving IP statistics for the computer](samples/sample_248.md)

## [Retrieving statistics for the TCP protocol running on the local computer](samples/sample_231.md)

## [Retrieving the IP-to-physical address mapping table](samples/sample_230.md)

## [Retrieving the User Datagram Protocol (UDP) listener table](samples/sample_234.md)

## [Retrieving the interface�to�IP address mapping table](samples/sample_233.md)

# ![](images/fox1.png) Icon group

## [Browsing Windows Known Folders (Special Folders)](samples/sample_576.md)

## [Converting image file to .ICO file](samples/sample_503.md)
This code sample shows how to load an image file (BMP, GIF, JPEG, PNG, TIFF), scale it and save as .ICO file. It creates a simple icon file containing one 32x32 icon in 32 bit per pixel format and assigns the new icon to the Icon property.  
## [Detecting changes in connections to removable drives (VFP9)](samples/sample_573.md)

## [Displaying icons in the system tray (VFP9)](samples/sample_235.md)

## [Displaying the associated icons and descriptions for files and folders](samples/sample_530.md)
When the list of files and folders is to be displayed inside a VFP form, the ListBox VFP control and the ListView ActiveX control are probably the first two candidates for the job. 

The ListBox`s presentation style can only be described as the minimalistic :) , while the ListView shows items in much fancier manner, and can even accompany each file and folder with an icon.

<img src="images/sysimagelist.png" width=507 height=338>
And an imminent question arises: where are those icons stored and how to put them to work?  
## [Drawing cursors for the classes defined by the system (preregistered): BUTTON, EDIT, LISTBOX etc.](samples/sample_203.md)

## [Drawing icons associated with the VFP main window](samples/sample_202.md)

## [Drawing standard Windows icons](samples/sample_112.md)

## [GDI+: Storing DLL icon resources in image files](samples/sample_501.md)

## [GDI+: custom Clock Control](samples/sample_597.md)

## [How to view icons stored in executable files (Icon Viewer)](samples/sample_113.md)

## [How to view icons stored in executable files (Icon Viewer) - II](samples/sample_019.md)

## [Retrieving information about the specified icon](samples/sample_206.md)

## [Storing screen shot of a form to bitmap file](samples/sample_187.md)

## [System Image List Viewer](samples/sample_021.md)

## [Using FoxTray ActiveX control: System Tray Icon and menu attached to VFP form](samples/sample_336.md)

## [Windows Shell Icons displayed and exported to ICO files (Vista)](samples/sample_575.md)

# ![](images/fox1.png) Internet Functions (WinInet) group

## [Another way to go online (it is not about choosing an ISP)](samples/sample_141.md)

## [Converting an HTTP time/date string to a SYSTEMTIME structure](samples/sample_328.md)

## [Creating a directory on the FTP](samples/sample_047.md)

## [Custom FTP Class for Visual FoxPro application](samples/sample_344.md)

## [Custom HttpRequest class (WinINet)](samples/sample_185.md)
This class is used for sending "GET" and "POST" HTTP requests to webserver and receiving responses.  
## [Dial the Net Automatically](samples/sample_140.md)

## [Downloading files from the FTP server using InternetReadFile](samples/sample_063.md)

## [How to delete IE cookies, clear IE history and delete files in Temporary Internet Files directory](samples/sample_471.md)
The following example presents session class *CacheEntry* and collection class *CacheEntries*. The latter, when created, enumerates Internet cache entries, either cookies or history or cached files depending on the search pattern. Cache entries can be deleted through *DeleteCacheEntry* and *DeleteCacheEntries* methods of the collection class.  
## [How to delete file on FTP server](samples/sample_071.md)

## [How to download a file from the FTP server using FtpGetFile](samples/sample_043.md)

## [How to download this reference`s archive through WinInet functions using InternetOpenUrl](samples/sample_110.md)

## [How to enumerate cookies and URL History entries in the cache of the local computer](samples/sample_350.md)

## [How to remove FTP directory](samples/sample_070.md)

## [How to retrieve information about a cache entry (Internet Explorer)](samples/sample_332.md)

## [How to retrieve the size of a remote file (FTP)](samples/sample_069.md)

## [Initiating Inet connection using a modem](samples/sample_312.md)

## [Managing Cookies](samples/sample_186.md)

## [Opening access to the Microsoft Internet functions for the application](samples/sample_042.md)

## [Reading Internet Query options](samples/sample_060.md)

## [Reading list of folders and files on FTP server](samples/sample_340.md)

## [Retrieving list of files on the FTP directory](samples/sample_046.md)

## [Retrieving the state of your Internet connection](samples/sample_068.md)

## [Testing if a connection to an Url can be established](samples/sample_327.md)

## [The DetectAutoProxyUrl function identifies the auto-config script location](samples/sample_341.md)

## [URL: converting unsafe characters and spaces into escape sequences](samples/sample_183.md)

## [URL: splitting into its component parts](samples/sample_184.md)

## [Uploading file to the FTP server using InternetWriteFile](samples/sample_062.md)

## [Uploading local file to FTP server with FtpPutFile](samples/sample_061.md)

## [Using FtpCommand](samples/sample_059.md)

## [Using InternetGoOnline function](samples/sample_067.md)

## [Using InternetSetFilePointer when resuming interrupted download from the Internet](samples/sample_191.md)

## [Wininet last error description](samples/sample_109.md)

# ![](images/fox1.png) Kernel Transaction Manager group

## [Copying files as a transacted operation (Vista)](samples/sample_540.md)

# ![](images/fox1.png) Keyboard Input group

## [Adding an ODBC data source with the SQLConfigDataSource; use automatic or interactive mode](samples/sample_381.md)

## [An alternative way of setting Form.Closable to False](samples/sample_127.md)

## [Animating a transition of the VFP form (a wire-frame rectangle)](samples/sample_255.md)

## [Attaching menu to a top-level form](samples/sample_208.md)

## [Bitmap Class for Visual FoxPro application](samples/sample_295.md)

## [Capturing keyboard activity of another application with the Raw Input API (VFP9)](samples/sample_572.md)

## [Comparing dimensions of the VFP main window with _SCREEN properties](samples/sample_078.md)

## [Configuring DEVMODE structure for a printer](samples/sample_384.md)

## [Confining Windows calculator inside the VFP main window](samples/sample_245.md)

## [Copying picture of the active form to the Clipboard using Enhanced Metafile API functions](samples/sample_404.md)

## [Creating a clipping region from the path selected into the device context of a form](samples/sample_144.md)

## [Creating a window using CreateWindowEx function](samples/sample_050.md)

## [Creating an Open dialog box to specify the drive, directory, and name of a file to open (Shell32 version)](samples/sample_365.md)

## [Creating the Open dialog box to specify the drive, directory, and name of a file to open](samples/sample_363.md)

## [Creating the Save dialog box to specify the drive, directory, and name of a file to save](samples/sample_265.md)

## [Deleting files into the Recycle Bin](samples/sample_321.md)

## [Disabling drawing in the VFP form](samples/sample_257.md)

## [Disabling mouse and keyboard input for the main VFP window (with the app still running)](samples/sample_083.md)

## [Displaying animated images on FoxPro form with BitBlt and StretchBlt functions](samples/sample_355.md)

## [Displaying bitmap using the AlphaBlend function](samples/sample_293.md)

## [Displaying printer-properties Property Sheet for the specified printer](samples/sample_372.md)

## [Displaying system dialog that selects a folder](samples/sample_364.md)

## [Dragging files from Explorer window and dropping them on FoxPro control (requires VFP9)](samples/sample_323.md)

## [Drawing Windows frame controls using the DrawFrameControl function](samples/sample_254.md)

## [Drawing Windows predefined bitmaps using the LoadBitmap functions](samples/sample_253.md)

## [Drawing a rectangle using Windows regular edges and borders](samples/sample_256.md)

## [Drawing a window caption using the DrawCaption routine](samples/sample_238.md)

## [Drawing cursors for the classes defined by the system (preregistered): BUTTON, EDIT, LISTBOX etc.](samples/sample_203.md)

## [Drawing icons associated with the VFP main window](samples/sample_202.md)

## [Drawing standard Windows icons](samples/sample_112.md)

## [Establishing connection using the SQLDriverConnect](samples/sample_290.md)

## [Extended MessageBox Class](samples/sample_418.md)

## [FindText -- the hopeless and useless Common Dialog](samples/sample_160.md)

## [Form Magnifier](samples/sample_414.md)

## [GDI+: Implementing image scrolling with inertia](samples/sample_595.md)
The inertial scrolling can be described as below: 
After releasing the mouse button, the image scrolling coninues while decelerating slowly, simulating the presence of inertia. The level of the deceleration depends on the momentum the mouse cursor obtains at the button release.
  
## [GDI+: copying to the Clipboard (a) image of active FoxPro window/form, (b) image file](samples/sample_457.md)

## [GDI+: saving image of FoxPro form to graphics file (BMP, GIF, JPG, PNG, TIF)](samples/sample_454.md)

## [GDI+: sending image of FoxPro form to printer](samples/sample_455.md)

## [GetFocus returns a HWND value](samples/sample_090.md)

## [Getting a bit more than the _CLIPTEXT offers](samples/sample_278.md)

## [How to activate Windows Calculator](samples/sample_026.md)

## [How to block the ALT+TAB shortcut (WinXP)](samples/sample_432.md)

## [How to block the PrintScreen key](samples/sample_489.md)
The PrintScreen key sends to the Clipboard either whole screen or just the active window (if pressed together with ALT key). To prevent windows of your application to be captured and printed by users through pressing this key, use RegisterHotKey API function. Still this solution does not provide absolute protection. A determined user may use third-party screen capturing utility that is not associated with the PrintScreen key and the Clipboard.   
## [How to browse and connect to printers on a network (WinNT)](samples/sample_376.md)

## [How to change the name and the size of the font in the MessageBox dialog](samples/sample_434.md)

## [How to copy the image of a form to the Clipboard using Bitmap API functions](samples/sample_091.md)

## [How to create transparent areas inside a form -- punching holes in the form](samples/sample_126.md)

## [How to display a dialog box with which the user can add a data source (DSN)](samples/sample_380.md)

## [How to display picture stored in enhanced-format metafile (*.emf)](samples/sample_403.md)

## [How to display the Properties dialog box for a file (ShellExecuteEx)](samples/sample_320.md)

## [How to display the port-configuration dialog box for a port on the specified server](samples/sample_362.md)

## [How to drag a Form not using its Titlebar or Caption](samples/sample_195.md)

## [How to intercept window messages sent to VFP form](samples/sample_307.md)

## [How to make the caption of a VFP application flashing in the Windows task bar](samples/sample_228.md)

## [How to play AVI file on the _screen](samples/sample_430.md)

## [How to position the GETPRINTER() dialog](samples/sample_482.md)
The GETPRINTER() dialog normaly appears at the left top corner of the main window of FoxPro. What if you want it to popup in the middle of the screen? The interface has no input parameters that can be used to position the dialog. Still the Timer control and several API calls can solve this small problem.  
## [How to print FoxPro form](samples/sample_158.md)

## [How to print FoxPro form -- II](samples/sample_406.md)

## [How to print a bitmap file](samples/sample_211.md)

## [How to print picture stored in enhanced-format metafile (*.emf)](samples/sample_405.md)

## [How to put a horizontal text scrolling on the form (a news line, marquee)](samples/sample_352.md)

## [How to put a vertical text scrolling on the form (a movie cast)](samples/sample_354.md)

## [How to remove a directory that is not empty](samples/sample_541.md)
As you know, the RMDIR generates an error message when an attempt made to remove a directory that is not empty. This example shows how to remove a directory with files based on the SHFileOperation call.  
## [How to start the screen saver and how to find whether the screen saver is active](samples/sample_196.md)

## [How to view icons stored in executable files (Icon Viewer)](samples/sample_113.md)

## [Initiating Inet connection using a modem](samples/sample_312.md)

## [Locking mouse and keyboard input for the VFP application](samples/sample_084.md)

## [Minimizing all running applications](samples/sample_244.md)

## [Obtaining the bounding rectangle for the specified device context](samples/sample_237.md)

## [Obtaining window class name for the main VFP window](samples/sample_049.md)

## [Placing a button on the VFP form as a new child window](samples/sample_274.md)

## [Placing an arbitrary rectangular area of main VFP window on the Clipboard](samples/sample_081.md)

## [Printing text on the client area of the main VFP window](samples/sample_034.md)

## [Printing text on the main VFP window](samples/sample_035.md)

## [Reading metrics for the currently selected font](samples/sample_339.md)

## [Reading the state of mouse buttons within DO WHILE loop](samples/sample_280.md)

## [Reading the structure of VFP main menu](samples/sample_337.md)

## [Reading virtual key status values and key names](samples/sample_305.md)

## [Retrieving Window Class information for the VFP window](samples/sample_201.md)

## [Retrieving information about the main VFP window](samples/sample_111.md)

## [Retrieving long values associated with the class of the VFP window](samples/sample_204.md)

## [Retrieving national language settings](samples/sample_077.md)

## [Retrieving top-child window for the VFP form](samples/sample_209.md)

## [Retrieving window and menu help context identifiers](samples/sample_025.md)

## [Round FoxPro form](samples/sample_143.md)

## [Running a regular FoxPro form while main VFP window is minimized](samples/sample_246.md)

## [Scanning the hierarchy of child windows down from the main VFP window](samples/sample_261.md)

## [Sending a standard message with one or more attached files using default email client](samples/sample_273.md)

## [Setting the Window Region for a form](samples/sample_120.md)

## [Setting the mouse capture to the specified window](samples/sample_282.md)

## [Shortcut Menu Class](samples/sample_419.md)

## [Simple MAPI: how to pick an email recipient from Outlook Express address book](samples/sample_407.md)

## [Splash Screen for the VFP application](samples/sample_294.md)

## [Starting a dialog box for connecting to network resources (mapping network drive)](samples/sample_309.md)

## [Storing content of the Clipboard to a bitmap file](samples/sample_189.md)

## [Storing screen shot of a form to bitmap file](samples/sample_187.md)

## [Storing screen shot of a form to enhanced metafile (*.emf)](samples/sample_402.md)

## [Switching between keyboard layouts](samples/sample_275.md)

## [Terminating all running applications from a VFP program](samples/sample_243.md)

## [Testing Clipboard functions: emptying the clipboard](samples/sample_028.md)

## [The window and its ancestors](samples/sample_266.md)

## [Tracking mouse movement to detect when to start dragging](samples/sample_281.md)

## [Using Common Controls: the Header Control](samples/sample_298.md)

## [Using FlashWindowEx to flash the taskbar button of the VFP application](samples/sample_271.md)

## [Using Font and Text functions](samples/sample_304.md)

## [Using FrameRgn for displaying system colors](samples/sample_125.md)

## [Using GetNearestColor](samples/sample_044.md)

## [Using InternetGoOnline function](samples/sample_067.md)

## [Using IsChild() for testing ThisForm.ShowWindow property](samples/sample_207.md)

## [Using the ChooseColor function](samples/sample_264.md)

## [Using the DrawText function](samples/sample_303.md)

## [Using the GradientFill function](samples/sample_353.md)

## [Using the IsWindowEnabled function](samples/sample_306.md)

## [Using the LoadImage function to have a bitmap file loaded and displayed on VFP main window](samples/sample_210.md)

## [Using the MessageBox Win32 function](samples/sample_048.md)

## [Using the RestartDialog function -- restarting Windows](samples/sample_361.md)

## [Who is the first in viewing the Clipboard](samples/sample_030.md)

## [Who owns the Windows Clipboard](samples/sample_029.md)

# ![](images/fox1.png) MSHTML Reference group

## [Yet another modal dialog: now HTML-based](samples/sample_561.md)

# ![](images/fox1.png) Mailslot group

## [Creating a mailslot](samples/sample_267.md)

## [Peer-to-peer LAN messenger built with Mailslot API functions](samples/sample_410.md)

# ![](images/fox1.png) Memory Management group

## [Accessing LSA Policy object (Local Security Authority)](samples/sample_427.md)

## [Adding and deleting Scheduled Tasks using NetScheduleJob API functions](samples/sample_490.md)
With Scheduled Tasks, you can schedule any script, program, or document to run at a time that is most convenient for you. Scheduled Tasks starts each time you start Windows XP and runs in the background.  
## [Adding and deleting User Accounts](samples/sample_478.md)
FoxPro class UserAccount wraps NetUserAdd, NetUserDel, NetUserGetInfo and NetUserSetInfo API calls to add, delete and modify user accounts on a server.  
## [Adding printer to the list of supported printers for the specified server](samples/sample_335.md)

## [Adding user-defined items to the Control Menu of VFP form (requires VFP9)](samples/sample_512.md)
User-defined items can be added to the Control Menu of any VFP form. In VFP9 it is also possible to link such menu items to a method of the form.
  
## [Attaching menu to a top-level form](samples/sample_208.md)

## [Browsing Windows Known Folders (Special Folders)](samples/sample_576.md)

## [Changing pitch and speed of a wave file](samples/sample_422.md)

## [Class for sound recording](samples/sample_420.md)

## [Compressing and decompressing files with Windows API Runtime Library routines](samples/sample_568.md)

## [Connecting a local device to a network resource](samples/sample_318.md)

## [Converting command-line string to a set of Unicode argument strings](samples/sample_212.md)

## [Copying strings through the global memory block](samples/sample_156.md)

## [Creating a folder](samples/sample_001.md)

## [Creating the Open dialog box to specify the drive, directory, and name of a file to open](samples/sample_363.md)

## [Creating the Save dialog box to specify the drive, directory, and name of a file to save](samples/sample_265.md)

## [Custom FTP Class for Visual FoxPro application](samples/sample_344.md)

## [Custom HttpRequest class (WinHTTP)](samples/sample_397.md)

## [Deleting files into the Recycle Bin](samples/sample_321.md)

## [Displaying OS Memory Status](samples/sample_020.md)

## [Displaying dimmed window behind VFP top-level form](samples/sample_578.md)

## [Displaying standard progress dialog box when copying files](samples/sample_508.md)
If you have ever thought about retiring ageing VFP commands COPY FILE and RENAME then give this code a try. 

The SHFileOperation copies, deletes and moves a file or multiple files. A variety of flags the fFlags member can take provides great flexibility. For example, in a single SHFileOperation call a group of files can be copied not to just one but to several destinations. The process is accompanied with familiar OS dialogs showing the progress or sending a reminder when existing file is about  to be replaced.  
## [Displaying system dialog that selects a folder](samples/sample_364.md)

## [Dynamic strings implemented through VFP Custom class](samples/sample_157.md)

## [Encapsulating access to the Windows Services in a class](samples/sample_476.md)
The winservices class, subclassed from the Collection class, enumerates Windows Services found in the default service control manager database on local computer. Each item in the collection is an instance of the winservice class that wraps the members of ENUM_SERVICE_STATUS structure for a given service. The winservice object exposes methods StartService, StopService and PauseService.  
## [Enhanced GetFont dialog](samples/sample_159.md)

## [Enumerating data formats currently available on the clipboard](samples/sample_032.md)

## [Enumerating files opened on the network](samples/sample_121.md)

## [Enumerating forms supported by a specified printer](samples/sample_390.md)

## [Enumerating network resources](samples/sample_313.md)
The code uses WNet API calls to enumerate all resources on the network.  
## [Enumerating ports that are available for printing on a specified server](samples/sample_334.md)

## [Enumerating print jobs and retrieving information for default printer (JOB_INFO_1 structures)](samples/sample_368.md)

## [Enumerating printer drivers installed](samples/sample_082.md)

## [Extensible Storage Engine class library](samples/sample_532.md)

## [FindText -- the hopeless and useless Common Dialog](samples/sample_160.md)

## [GDI+: reading and writing metadata in JPEG and TIFF files](samples/sample_461.md)
The code shows how to store and retrieve metadata in image files. **Metadata** is defined as *"Data about data, or information known about the image in order to provide access to the image"*. It may be, for example, a shatter speed value for your digital camera or description to a birthday party picture.  
## [GetFileOwner - Get the owner of an NTFS file](samples/sample_433.md)

## [How to assemble an array of strings and pass it to external function](samples/sample_487.md)
The PathFindOnPath function is anything but special. Whatever it does, can be accomplished by using FILE() and GETENV() FoxPro functions. Though it gives me a chance to demonstrate a technique of assembling an array of strings for being passed to external function.  
## [How to browse and connect to printers on a network (WinNT)](samples/sample_376.md)

## [How to convert a bitmap file to monochrome format (1 bpp)](samples/sample_493.md)
It all started with a question I have noticed in the Universal Thread Visual FoxPro forum:*Does anyone know how to create a monochrome bitmap or monochrome tiff file from a VFP report? *
  
## [How to delete IE cookies, clear IE history and delete files in Temporary Internet Files directory](samples/sample_471.md)
The following example presents session class *CacheEntry* and collection class *CacheEntries*. The latter, when created, enumerates Internet cache entries, either cookies or history or cached files depending on the search pattern. Cache entries can be deleted through *DeleteCacheEntry* and *DeleteCacheEntries* methods of the collection class.  
## [How to display a user-defined icon in the MessageBox dialog](samples/sample_500.md)

## [How to display advanced Task Dialog (Vista)](samples/sample_558.md)

## [How to display the Print property sheet](samples/sample_531.md)

## [How to display the Properties dialog box for a file (ShellExecuteEx)](samples/sample_320.md)

## [How to enumerate cookies and URL History entries in the cache of the local computer](samples/sample_350.md)

## [How to enumerate sessions and processes on a specified terminal server](samples/sample_519.md)

## [How to enumerate terminal servers within the specified Windows domain](samples/sample_520.md)

## [How to enumerate, add and delete shares on the local computer (WinNT/XP)](samples/sample_351.md)

## [How to extract frames from AVI files](samples/sample_484.md)
The example presents the AviBrowser class. This class can open AVI file and convert its frames into bitmap files. The AviBrowser object is shown used as a control on FoxPro form. For that reason, it is subclassed from the Image control.  
## [How to load a user profile](samples/sample_602.md)

## [How to ping a remote site using ICMP API calls](samples/sample_486.md)
The Ping class uses several API functions -- IcmpCreateFile, IcmpCloseHandle, IcmpSendEcho and others -- to send an ICMP Echo request and get a reply (RTT, round-trip time).   
## [How to prevent users from accessing the Windows Desktop and from switching to other applications](samples/sample_492.md)
Sometimes you may need a computer with a single application running on it, and with all other applications and resources hidden from users. An example, Indigo Book Store customers can only search books when using public computers in the store.
  
## [How to print FoxPro form](samples/sample_158.md)

## [How to print a bitmap file](samples/sample_211.md)

## [How to remove a directory that is not empty](samples/sample_541.md)
As you know, the RMDIR generates an error message when an attempt made to remove a directory that is not empty. This example shows how to remove a directory with files based on the SHFileOperation call.  
## [How to write and read Window Properties for the specified window](samples/sample_205.md)

## [Loading a string resource from an executable file](samples/sample_213.md)

## [MapiSendMail class for Visual FoxPro application](samples/sample_342.md)

## [Mapping and disconnecting network drives](samples/sample_387.md)

## [Moving shortcut to a specified position on the Windows Desktop](samples/sample_581.md)

## [Obtaining addresses for the adapters on the local computer (Win XP/2003/Vista)](samples/sample_506.md)

## [Obtaining heap handles and enumerating memory blocks for the current VFP session (WinNT only)](samples/sample_176.md)

## [Obtaining list of tables stored in an ODBC Data Source](samples/sample_409.md)

## [Obtaining names and positions for shortcuts located on the Windows Desktop](samples/sample_579.md)

## [Obtaining names of local and global groups for current user (WinNT/XP/2K)](samples/sample_431.md)

## [Opening the Page Setup dialog box to specify the attributes of a printed page](samples/sample_272.md)

## [Passing data records between VFP applications via the Clipboard](samples/sample_346.md)

## [Playing WAV sounds simultaneously](samples/sample_523.md)
This code is written in response to a question posted on UT: Ride two WAVs at once? As I found, the sndPlaySound was not suitable for this. To play multiple sounds simultaneously, the waveOut* functions must be used...  
## [Pocket PC: base class](samples/sample_440.md)
This class is used as a base class for several custom RAPI classes created to access objects stored on Pocket PC: system registry, object store databases, files and folder, remote routines.  
## [Printing Image File, programmatically set print page orientation to landscape](samples/sample_555.md)

## [Quering Audio Mixer Device](samples/sample_423.md)

## [Reading and setting explicit Application User Model ID for the current process (Win7)](samples/sample_038.md)

## [Reading entries from Event logs](samples/sample_524.md)

## [Reading security permissions for NTFS files and folders](samples/sample_516.md)
This code sample includes a set of classes implementing several NTFS access control objects. Through these objects, like Access Control List (ACL) and Access Control Entry (ACE) and others, the OS defines access rights to files, folders (in particular) for different users and user groups.  
## [Reading the structure of VFP main menu](samples/sample_337.md)

## [Retrieving System Error message strings](samples/sample_056.md)

## [Retrieving configuration information for the specified server (Win2000/XP)](samples/sample_425.md)

## [Retrieving local computer and user names](samples/sample_041.md)

## [Retrieving the command line for the VFP session](samples/sample_051.md)

## [Retrieving the name of the default printer for the current user on the local computer (Win NT/XP)](samples/sample_360.md)
This code sample retrieves the name of default printer on local computer and obtains detailed information for this printer in PRINTER_INFO_5 format.   
## [Sending email messages with Simple MAPI](samples/sample_193.md)

## [Shortcut Menu Class](samples/sample_419.md)

## [Simple printer queue monitor: deletes, pauses, resumes print jobs for local printer](samples/sample_373.md)

## [Starting a dialog box for connecting to network resources and passing input parameters](samples/sample_551.md)
This code sample is an extension of  "#309. Starting a dialog box for connecting to network resources". The code is written around the WNetConnectionDialog1 function and provides a better control of the network connection dialog through input parameters.  
## [Storing content of the Clipboard to a bitmap file](samples/sample_189.md)

## [Storing screen shot of a form to bitmap file](samples/sample_187.md)

## [Storing the environment strings in cursor](samples/sample_089.md)

## [StrDup returns a pointer to the duplicate of a source VFP string](samples/sample_181.md)

## [Subclassing CommandButton control to create BackColor property](samples/sample_392.md)

## [Testing serial ports](samples/sample_308.md)
In Windows all input/output ports are presented as files, so work with ports is performed through file functions like *CreateFile, CloseHandle, ReadFile, ReadFileEx, WriteFile* and *WriteFileEx*.  
## [URL: splitting into its component parts](samples/sample_184.md)

## [Using Change Notification Objects to monitor changes to the printer or print server](samples/sample_485.md)
The code explains how to use FindFirstPrinterChangeNotification and FindNextPrinterChangeNotification API calls to monitor changes in jobs for a specified local or network printer. Not an easy job for Visual FoxPro, considering its unique attitude to API structures and pointers. This functionality can be used to build a print monitor, though in a way limited by the single-thread nature of Visual FoxPro.  
## [Using Common Controls: the Header Control](samples/sample_298.md)

## [Using EnumPrinters function to enumerate locally installed printers](samples/sample_146.md)

## [Using FillMemory](samples/sample_198.md)

## [Using FoxTray ActiveX control: System Tray Icon and menu attached to VFP form](samples/sample_336.md)

## [Using WM_COPYDATA for interprocess communication (VFP9)](samples/sample_536.md)
An application sends the WM_COPYDATA message to pass data to another application running on the same PC. The C# and VFP versions of this code sample are functionally identical. That allows exchanging data between .NET and VFP forms (applications).  
## [Using the ChooseColor function](samples/sample_264.md)

## [Using the heap of the calling process to allocate memory blocks](samples/sample_199.md)

## [Validating the heap of the calling process](samples/sample_200.md)

## [Verifying a file using the Authenticode policy provider](samples/sample_569.md)

## [Vertical Label control](samples/sample_398.md)

## [WAV file player](samples/sample_417.md)

## [Windows Shell Icons displayed and exported to ICO files (Vista)](samples/sample_575.md)

## [Winsock: connecting to a news server (NNTP, port 119)](samples/sample_389.md)

## [Winsock: retrieving information from a host database for a given host name](samples/sample_216.md)

## [Writing entries to custom Event Log](samples/sample_564.md)
This code sample explains how to add entries to event logs using Event Logging API.  
# ![](images/fox1.png) Menu group

## [Accessing Adobe Reader 7.0 main menu from VFP application](samples/sample_495.md)
I was looking for a simple way of closing Adobe Reader document and leaving intact other open PDF documents and the reader itself. Presented AdobeAcrobat7 class enumerates opened pdf documents. It also can close any Acrobat document window or all document windows and more.  
## [Adding user-defined items to the Control Menu of VFP form (requires VFP9)](samples/sample_512.md)
User-defined items can be added to the Control Menu of any VFP form. In VFP9 it is also possible to link such menu items to a method of the form.
  
## [Attaching menu to a top-level form](samples/sample_208.md)

## [How to control Adobe Reader 9.0 (SDI mode) from VFP application](samples/sample_550.md)
Each Adobe Reader 9 window is created from window class AcrobatSDIWindow and parented by the Windows Desktop.  Enumeration of child windows of this class within the Desktop window returns the exact number of open Adobe Acrobat 9 documents.

The AdobeReaderSDIWindow class is able to virtually "click on" an item in the main menu of Adobe Reader 9 window and in this way to control some of the functionality.  
## [Programmatically removing submenus from VFP main menu](samples/sample_258.md)

## [Reading the structure of VFP main menu](samples/sample_337.md)

## [Retrieving window and menu help context identifiers](samples/sample_025.md)

## [Shortcut Menu Class](samples/sample_419.md)

## [Simple Window Viewer](samples/sample_057.md)
This code enumerates all windows starting from the Desktop window and displays results in TreeView control.  
## [Using FoxTray ActiveX control: System Tray Icon and menu attached to VFP form](samples/sample_336.md)

# ![](images/fox1.png) Message and Message Queue group

## [Accessing Adobe Reader 7.0 main menu from VFP application](samples/sample_495.md)
I was looking for a simple way of closing Adobe Reader document and leaving intact other open PDF documents and the reader itself. Presented AdobeAcrobat7 class enumerates opened pdf documents. It also can close any Acrobat document window or all document windows and more.  
## [Browsing Windows Known Folders (Special Folders)](samples/sample_576.md)

## [Controlling master audio volume by sending WM_APPCOMMAND messages](samples/sample_592.md)
The WM_APPCOMMAND message allows to acquire medium level of control over several OS areas: speakers, microphone, media, browser, mail, default applications. This code sample shows how to mute, unmute and change the volume of the speakers. This technique provides no means of reading the volume level or the mute status.  
## [Creating irregularly shaped FoxPro form using transparency color key](samples/sample_033.md)
The SetLayeredWindowAttributes function can be used to define the transparency color for the top-level FoxPro form. That means all areas on the form with this color, including native windowless FoxPro controls, become transparent.   
## [Detecting changes in connections to removable drives (VFP9)](samples/sample_573.md)

## [Displaying hypertext links with the SysLink control (VFP9, Comctl32.dll)](samples/sample_559.md)

## [Displaying the associated icons and descriptions for files and folders](samples/sample_530.md)
When the list of files and folders is to be displayed inside a VFP form, the ListBox VFP control and the ListView ActiveX control are probably the first two candidates for the job. 

The ListBox`s presentation style can only be described as the minimalistic :) , while the ListView shows items in much fancier manner, and can even accompany each file and folder with an icon.

<img src="images/sysimagelist.png" width=507 height=338>
And an imminent question arises: where are those icons stored and how to put them to work?  
## [Enumerating devices installed on the local machine](samples/sample_545.md)
The PnP manager maintains a device tree that keeps track of the devices in the system.

The device tree contains information about the devices present on the system. The PnP manager builds this tree when the machine boots, using information from drivers and other components, and updates the tree as devices are added or removed.  
## [Extended MessageBox Class](samples/sample_418.md)

## [How to activate Windows Calculator](samples/sample_026.md)

## [How to change the name and the size of the font in the MessageBox dialog](samples/sample_434.md)

## [How to control Adobe Reader 9.0 (SDI mode) from VFP application](samples/sample_550.md)
Each Adobe Reader 9 window is created from window class AcrobatSDIWindow and parented by the Windows Desktop.  Enumeration of child windows of this class within the Desktop window returns the exact number of open Adobe Acrobat 9 documents.

The AdobeReaderSDIWindow class is able to virtually "click on" an item in the main menu of Adobe Reader 9 window and in this way to control some of the functionality.  
## [How to disable the Windows Clipboard (VFP9)](samples/sample_488.md)
The Windows OS has a mechanism that allows to notify a window when the content of the clipboard changes. Any FoxPro window can be registered as a clipboard viewer. The notifications are actually window messages. And VFP9 handles window messages really good due to extended BINDEVENT() function.  
## [How to drag a Form not using its Titlebar or Caption](samples/sample_195.md)

## [How to draw custom Window Caption on FoxPro form](samples/sample_499.md)
This code sample shows how to hide the Caption and the border of FoxPro form and replace them with eight Image controls and one Label control. The form is resizable, closable and can be clicked on its caption and dragged.
  
## [How to start the screen saver and how to find whether the screen saver is active](samples/sample_196.md)

## [How to view icons stored in executable files (Icon Viewer) - II](samples/sample_019.md)

## [How to view system icons for the classes installed on the local machine](samples/sample_544.md)
The bitmap images for the classes installed on the machine are stored in some system area. These images are more of a general kind and illustrate functionality groups rather than individual classes. With a few API calls VFP application can access these images and display them in TreeView and ListView controls as icons.  
## [MSMQ: how to open a queue](samples/sample_603.md)

## [Moving shortcut to a specified position on the Windows Desktop](samples/sample_581.md)

## [Obtaining names and positions for shortcuts located on the Windows Desktop](samples/sample_579.md)

## [Round FoxPro form](samples/sample_143.md)

## [Simulating DOEVENTS](samples/sample_163.md)

## [System Image List Viewer](samples/sample_021.md)

## [Terminating all running applications from a VFP program](samples/sample_243.md)

## [Using Common Controls: the Header Control](samples/sample_298.md)

## [Using Month Calendar Control (VFP9, Comctl32.dll)](samples/sample_560.md)

## [Using Video Capture: displaying on FoxPro form frames and previewing video obtained from a digital camera](samples/sample_437.md)
The code sample shows how to display preview from a digital camera using Video Capture API. As well this API can display still frames and save frames to DIB files.  
## [Using WM_COPYDATA for interprocess communication (VFP9)](samples/sample_536.md)
An application sends the WM_COPYDATA message to pass data to another application running on the same PC. The C# and VFP versions of this code sample are functionally identical. That allows exchanging data between .NET and VFP forms (applications).  
## [Windows Shell Icons displayed and exported to ICO files (Vista)](samples/sample_575.md)

# ![](images/fox1.png) Metafile group

## [Copying picture of the active form to the Clipboard using Enhanced Metafile API functions](samples/sample_404.md)

## [How to display picture stored in enhanced-format metafile (*.emf)](samples/sample_403.md)

## [How to print FoxPro form -- II](samples/sample_406.md)

## [How to print picture stored in enhanced-format metafile (*.emf)](samples/sample_405.md)

## [Storing screen shot of a form to enhanced metafile (*.emf)](samples/sample_402.md)

# ![](images/fox1.png) Monitor Configuration (Vista) group

## [How to adjust monitor brightness (Vista, monitor with DDC support)](samples/sample_543.md)
The Monitor Configuration API was first made available in Windows Vista. These functions are applicable only if the monitor supports the Display Data Channel (DDC/CI) connection with the graphics adapter.  
# ![](images/fox1.png) Mouse Input group

## [Creating irregularly shaped FoxPro form using transparency color key](samples/sample_033.md)
The SetLayeredWindowAttributes function can be used to define the transparency color for the top-level FoxPro form. That means all areas on the form with this color, including native windowless FoxPro controls, become transparent.   
## [Displaying dimmed window behind VFP top-level form](samples/sample_578.md)

## [GDI+: Implementing image scrolling with inertia](samples/sample_595.md)
The inertial scrolling can be described as below: 
After releasing the mouse button, the image scrolling coninues while decelerating slowly, simulating the presence of inertia. The level of the deceleration depends on the momentum the mouse cursor obtains at the button release.
  
## [How to drag a Form not using its Titlebar or Caption](samples/sample_195.md)

## [How to draw custom Window Caption on FoxPro form](samples/sample_499.md)
This code sample shows how to hide the Caption and the border of FoxPro form and replace them with eight Image controls and one Label control. The form is resizable, closable and can be clicked on its caption and dragged.
  
## [Round FoxPro form](samples/sample_143.md)

## [Setting and retrieving the double-click time for the mouse](samples/sample_054.md)

## [Setting the mouse capture to the specified window](samples/sample_282.md)

## [Tracking mouse movement to detect when to start dragging](samples/sample_281.md)

# ![](images/fox1.png) Multiple Display Monitors group

## [How to adjust monitor brightness (Vista, monitor with DDC support)](samples/sample_543.md)
The Monitor Configuration API was first made available in Windows Vista. These functions are applicable only if the monitor supports the Display Data Channel (DDC/CI) connection with the graphics adapter.  
## [How to change display settings: screen resolution, screen refresh rate](samples/sample_374.md)
Even if it is not always bright idea to change display resolution from your application, still it is comfortable to know that there is a way to do it.  
## [How to detect if additional monitor is connected and active](samples/sample_542.md)
Nowadays having two monitors connected to a PC becomes more a common place rather than exception. This code sample explains how to detect all available monitors through enumerating display devices and their properties.  
# ![](images/fox1.png) National Language Support group

## [Analyzing character types in a specified string](samples/sample_600.md)

## [Retrieving national language settings](samples/sample_077.md)

## [Saving available locale records into a cursor](samples/sample_076.md)

# ![](images/fox1.png) Network Management group

## [Adding and deleting Scheduled Tasks using NetScheduleJob API functions](samples/sample_490.md)
With Scheduled Tasks, you can schedule any script, program, or document to run at a time that is most convenient for you. Scheduled Tasks starts each time you start Windows XP and runs in the background.  
## [Adding and deleting User Accounts](samples/sample_478.md)
FoxPro class UserAccount wraps NetUserAdd, NetUserDel, NetUserGetInfo and NetUserSetInfo API calls to add, delete and modify user accounts on a server.  
## [Enumerating connections made to a shared resource for the local computer (WinNT only)](samples/sample_168.md)

## [Enumerating files opened on the network](samples/sample_121.md)

## [Enumerating global and local group accounts on a server (WinNT/XP/2K)](samples/sample_411.md)

## [Enumerating network sessions established on a server](samples/sample_505.md)

## [Enumerating servers of the specified type (e.g. SQL Server) in the primary domain](samples/sample_165.md)

## [Finding out if the current user is the Guest account](samples/sample_566.md)
In this code sample, the CurrentUser class wraps call to the NetUserGetInfo that populates USER_INFO_1 structure. The usri1_priv member of this struture indicates if the user account is Guest or Admin.  
## [How to enumerate, add and delete shares on the local computer (WinNT/XP)](samples/sample_351.md)

## [Obtaining information about all user accounts on a server (WinNT only)](samples/sample_249.md)

## [Obtaining names of local and global groups for current user (WinNT/XP/2K)](samples/sample_431.md)

## [Retrieving configuration information for the specified server (Win2000/XP)](samples/sample_425.md)

## [Retrieving configuration information for the specified server (Win98/Me)](samples/sample_276.md)

## [Retrieving configuration information for the specified workstation (Win2000/XP)](samples/sample_436.md)

## [Retrieving information about all users currently logged on to the workstation (WinNT only)](samples/sample_167.md)

## [Retrieving the name of the primary domain controller (PDC) and join status information](samples/sample_166.md)

## [Using NetWkstaTransportEnum to obtain MAC Address of remote server](samples/sample_435.md)

## [Using the NetMessageBufferSend to send messages on the network](samples/sample_494.md)
The code sample explains how to broadcast system alerts using the NetMessageBufferSend as an alternative to NET SEND command.  
# ![](images/fox1.png) ODBC API group

## [Adding an ODBC data source with the SQLConfigDataSource; use automatic or interactive mode](samples/sample_381.md)

## [Enumerating ODBC Data Sources available on the local computer](samples/sample_284.md)
The code shows how to use SQLDataSources function to retrieve lists of available Data Sources (either System or User DSNs).  
## [Enumerating ODBC drivers available on the local computer](samples/sample_285.md)

## [Establishing connection using the SQLDriverConnect](samples/sample_290.md)

## [How to display a dialog box with which the user can add a data source (DSN)](samples/sample_380.md)

## [How to obtain the number of rows affected by remote UPDATE, INSERT or DELETE statement](samples/sample_416.md)

## [How to retrieve list of system DSNs (Data Source Name) with parameters](samples/sample_375.md)
The code shows how to use the SQLGetPrivateProfileString function to retrieve lists of current Data Sources (either System or User DSNs).  
## [List of ODBC drivers installed (read from the [ODBC Drivers] section)](samples/sample_378.md)

## [Obtaining list of tables stored in an ODBC Data Source](samples/sample_409.md)

## [Retrieveing general information about the driver and data source associated with an ODBC connection](samples/sample_289.md)

## [Retrieving current settings for an ODBC connection](samples/sample_292.md)

## [Testing an ODBC connection for supporting specific functionality](samples/sample_286.md)

## [The SQLGetProp() creates a bridge between Visual FoxPro and the ODBC API](samples/sample_291.md)

## [Using SQLBrowseConnect to connect to a data source through a number of iterative calls (SQL Server)](samples/sample_288.md)

## [Using vendor-neutral SQL constructs](samples/sample_287.md)

# ![](images/fox1.png) Painting and Drawing group

## [An alternative way of setting Form.Closable to False](samples/sample_127.md)

## [Animating a transition of the VFP form (a wire-frame rectangle)](samples/sample_255.md)

## [Bitmap Class for Visual FoxPro application](samples/sample_295.md)

## [Copying picture of the active form to the Clipboard using Enhanced Metafile API functions](samples/sample_404.md)

## [Creating a clipping region from the path selected into the device context of a form](samples/sample_144.md)

## [Creating irregularly shaped FoxPro form using transparency color key](samples/sample_033.md)
The SetLayeredWindowAttributes function can be used to define the transparency color for the top-level FoxPro form. That means all areas on the form with this color, including native windowless FoxPro controls, become transparent.   
## [Disabling drawing in the VFP form](samples/sample_257.md)

## [Displaying animated images on FoxPro form with BitBlt and StretchBlt functions](samples/sample_355.md)

## [Displaying bitmap using the AlphaBlend function](samples/sample_293.md)

## [Displaying the associated icons and descriptions for files and folders](samples/sample_530.md)
When the list of files and folders is to be displayed inside a VFP form, the ListBox VFP control and the ListView ActiveX control are probably the first two candidates for the job. 

The ListBox`s presentation style can only be described as the minimalistic :) , while the ListView shows items in much fancier manner, and can even accompany each file and folder with an icon.

<img src="images/sysimagelist.png" width=507 height=338>
And an imminent question arises: where are those icons stored and how to put them to work?  
## [Drawing Windows frame controls using the DrawFrameControl function](samples/sample_254.md)

## [Drawing Windows predefined bitmaps using the LoadBitmap functions](samples/sample_253.md)

## [Drawing a rectangle using Windows regular edges and borders](samples/sample_256.md)

## [Drawing a window caption using the DrawCaption routine](samples/sample_238.md)

## [Drawing cursors for the classes defined by the system (preregistered): BUTTON, EDIT, LISTBOX etc.](samples/sample_203.md)

## [Drawing icons associated with the VFP main window](samples/sample_202.md)

## [Form Ma
