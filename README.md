# CSharp_Run_Powershell_Script

C# class to run powershell from c# binary/dll without powershell.exe. 

Also for some reason...i couldnt find powershell logs for what is run via this code.

Script must be on disk with the current way its coded.

Sorry red team. 

#VNC Apps (Can use 443)

http://www.tightvnc.com/download.php

#Tor/Tunnel

https://www.torproject.org/download/download.html.en

#Compile Windows

Client Side Complies: cd \Windows\Microsoft.NET\Framework\v{Version Number} csc.exe /unsafe /reference:{Call all in .cs File 1 ref arg per ref} /win32icon:C:\p0wnedShell{ProjName}.ico /out:C:{ProjName\Path}.{Extension}(ie exe or DLL) /platform:x86 "C:{Proj location}*.cs"

BUT its not to much work to change that, but thats up to you. Dont use for evil.
