# Multiperson-chat-server
This is a command line interface based multiperson chat server built using sockets.
# CONTENTS
1. showip.c - This function shows the IP address of a host given on the command line.
2. gittingHostName.c - This function returns the name of the computer our program is running on.
3. pollserver.c - The is the main program of our chat server.
# PLATFORM AND COMPILER
The codes were complied on a LINUX system usig GNU's gcc compiler. If you are on a Windows or Solaris/SunOS, please refer to the reference attached below.
## 1. showip.c
Simply compile the file using ```gcc showip.c```.<br/>
Run using ```./a.out www.example.net```
## 2. gettingHostName.c
Compile using ```gcc gettingHostName.c```.<br/>
Run using ```./a.out```.<br/>
This will return the name of your system which you can use during telnet.
## 3. pollserver.c
Run it on one window<br/>
```gcc pollserver.c```<br/>
```./a.out```<br/>
Then, ```telnet localhost 9034``` from a number of other terminal windows.<br/>
# References
<a>https://beej.us/guide/bgnet/pdf/bgnet_a4_c_1.pdf
