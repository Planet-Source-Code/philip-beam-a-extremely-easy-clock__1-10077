<div align="center">

## A Extremely Easy Clock


</div>

### Description

This code is the easiest clock ever... The code doesnt get any easier. If you like it vote for it.
 
### More Info
 
You need a Timer (named Timer1) and a label (named Label1)... Do not rename the form. Leave it Form1.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Philip Beam](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/philip-beam.md)
**Level**          |Beginner
**User Rating**    |4.5 (50 globes from 11 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/philip-beam-a-extremely-easy-clock__1-10077/archive/master.zip)





### Source Code

```
Private Sub Form_Load()
  Timer1.Interval = 1
End Sub
Private Sub Timer1_Timer()
  Label1.Caption = Time
End Sub
```

