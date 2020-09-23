<div align="center">

## Center a form


</div>

### Description

This is, I think, the easiest way to center a form. It is the way reccomended by Microsoft and Microsoft Press. Just stick it into your form_load.
 
### More Info
 
just stick this into your form_load place! Easy!


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[SeeD](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/seed.md)
**Level**          |Unknown
**User Rating**    |4.0 (48 globes from 12 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/seed-center-a-form__1-2798/archive/master.zip)





### Source Code

```
Private Sub Form_Load
 Left = (Screen.Width - Width) \ 2
 Top = (Screen.Height - Height) \ 2
End Sub
```

