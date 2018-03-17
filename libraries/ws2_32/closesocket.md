<link rel="stylesheet" type="text/css" href="../../css/win32api.css">  
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

## Functionname : closesocket
Group: Windows Sockets 2 (Winsock) - Library: ws2_32    
***  


#### The closesocket function closes an existing socket.
***  


## Code examples:
[How to build UDP responder](../../samples/sample_052.md)  
[Winsock: creating a socket that is bound to a specific service provider](../../samples/sample_226.md)  
[Winsock: reading and setting socket options](../../samples/sample_232.md)  
[Winsock: retrieving Web pages using sockets (HTTP, port 80)](../../samples/sample_383.md)  
[Winsock: sending email messages (SMTP, port 25)](../../samples/sample_385.md)  
[Winsock: retrieving directory listing from an FTP server using passive data connection (FTP, port 21)](../../samples/sample_386.md)  
[Winsock: reading email messages (POP3, port 110)](../../samples/sample_388.md)  
[Winsock: connecting to a news server (NNTP, port 119)](../../samples/sample_389.md)  
[How to create non-blocking Winsock server](../../samples/sample_412.md)  
[A client for testing non-blocking Winsock server](../../samples/sample_413.md)  

## Declaration:
```foxpro  
int closesocket(
  SOCKET s
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER closesocket IN ws2_32;
	INTEGER s  
```  
***  


## Parameters:
```txt  
s
[in] Descriptor identifying the socket to close.  
```  
***  


## Return value:
If no error occurs, closesocket returns zero. Otherwise, a value of SOCKET_ERROR (-1) is returned.  
***  
