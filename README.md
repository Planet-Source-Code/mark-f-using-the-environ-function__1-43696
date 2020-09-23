<div align="center">

## Using the Environ function


</div>

### Description

This is something that hopefully will help someone who is looking for a fast way of getting some system environment settings.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Mark F](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/mark-f.md)
**Level**          |Beginner
**User Rating**    |4.9 (49 globes from 10 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/mark-f-using-the-environ-function__1-43696/archive/master.zip)





### Source Code

```
In the debug window type the following:
For x = 1 to 80: ? Environ(x): next x
What is returned can also be used in your code. The Environ function is inlcuded in the vb runtime.
e.g.
strWinDirectory = Environ("windir")
No need to vote, just hope this helps someone.
```

