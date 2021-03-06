
# WebPageFont.ProportionalFont Property (Office)

Sets or gets the proportional font setting in the host application. Read/write.


## Syntax

 _expression_. **ProportionalFont**

 _expression_ A variable that represents a **WebPageFont** object.


## Remarks

When you set the  **ProportionalFont** property, the host application does not check the value for validity.


## Example

This example sets the proportional font and proportional font size for the English/Western European/Other Latin Script character set in the active application.


```vb
Application.DefaultWebOptions. _ 
Fonts(msoCharacterSetEnglishWesternEuropeanOtherLatinScript) _ 
.ProportionalFont = "Tahoma" 
Application.DefaultWebOptions. _ 
Fonts(msoCharacterSetEnglishWesternEuropeanOtherLatinScript) _ 
.ProportionalFontSize = 14.5
```


## See also


#### Concepts


[WebPageFont Object](daf3c079-520d-68bd-ec02-027776074505.md)
