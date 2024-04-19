# SeTcbPrivilege Abuse - TcbElevation
Compiled executables for [@splinter_code](https://twitter.com/splinter_code) and [@decoder_it](https://twitter.com/decoder_it)'s [TcbElevation exploit](https://gist.github.com/antonioCoco/19563adef860614b56d010d92e67d178). 
All credit to original authors.

Tested and confirmed working on Offsec's PG Practice **Symbolic** machine, achieving privileged reverse shell (msfvenom) from unprivileged user account with *SeTcbPrivilege* present/enabled.

Usage:
```
.\TcbElevation.exe somestring "C:\path\to\your.exe"
```

![image1](https://raw.githubusercontent.com/jlmitra/SeTcbPrivilege-Abuse/main/image1.png)
![image2](https://raw.githubusercontent.com/jlmitra/SeTcbPrivilege-Abuse/main/image2.png)
