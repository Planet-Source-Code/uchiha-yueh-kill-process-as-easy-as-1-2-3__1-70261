<div align="center">

## Kill process as easy as 1\-2\-3


</div>

### Description

Killing a process/program as easy as 1-2-3. No API, just as little piece of code.

Just sharing.

Enjoy!!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Uchiha Yueh](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/uchiha-yueh.md)
**Level**          |Beginner
**User Rating**    |5.0 (40 globes from 8 users)
**Compatibility**  |VB 5\.0, VB 6\.0, VB Script, ASP \(Active Server Pages\) 
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/uchiha-yueh-kill-process-as-easy-as-1-2-3__1-70261/archive/master.zip)





### Source Code

```
Dim Process
For Each Process In GetObject("winmgmts:"). _
   ExecQuery("select name from Win32_Process where name='notepad.exe'")
  Process.Terminate (0)
Next
```

