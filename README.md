# RDP-Protocol-Handler-Win10
Allows windows 10 to use basic URLs that also work on android/mac from here: 
https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/clients/remote-desktop-uri

Only works with URL in the format rdp://full%20address=s:SERVER:PORT
launches mstsc with server/port and attempts to connect immediately if you have creds saved for the server connection already. 
