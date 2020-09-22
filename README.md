<div align="center">

## best way to disable taskmgr


</div>

### Description

how to disable and enable taskmngr few lines only... no API no complicated stuff "i red that somewhere in psc"
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Dherar Z\. AL\-Rashoud](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/dherar-z-al-rashoud.md)
**Level**          |Beginner
**User Rating**    |4.0 (16 globes from 4 users)
**Compatibility**  |VB 6\.0
**Category**       |[Files/ File Controls/ Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/files-file-controls-input-output__1-3.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/dherar-z-al-rashoud-best-way-to-disable-taskmgr__1-65881/archive/master.zip)





### Source Code

```
dont give me the credits because i'm not the one who thought of it... i cant remember the guy's name who thought of it so please whoever knows the name just lemme know i'll edit this article to give him the credits...
anyways... the best way to disable taskmgr is to open it for binary access write... this way just try to press alt+ctrl+del and it wouldn't work...
i tried that for like lotsa times and it worked on Winxp pro
Open "C:\windows\system32\taskmgr.exe" For Binary Access Write Lock Read As #1
to enable it just
close #1
easier than writin' to registry or doin' some long codes to disable it
```

