# How to design a keypad grid on the screen #


  1. Create a new project named KeypadGrid and change its properties as following:
    * BackgroundColor to Black
    * ScreenOrientation to Portrait
    * Title to Keypad Design
    * Uncheck Scrollable
  1. Place TableArrangement (in the Screen Arrangement category) on the top of the screen and change properties:
    * Rename TableArrangement1 to KeypadGrid
    * Column to 10
    * Row to 5
    * Width to 320 pixels
    * Height to 180 pixels
### First row of buttons ###
  1. Place a label to the leftmost, uppermost corner of the table.
    * Rename Label1 to WideSpacer
    * Text to blank
    * Width to 12
    * Height to 55
  1. Place a button on the top row next to WideSpacer
    * Rename the button to ClearButton
    * BackgroundColor to Cyan
    * Check FontBold
    * FontSize to 24
    * Text to <<
    * Width to 55
    * Height to 55
  1. Place a label on the top next to ClearButton
    * Rename the label to VSpacer1
    * Text to blank
    * Width to 5
    * Height to 55
  1. Place a button on the top next to VSpacer1
    * Rename the button to BsButton
    * BackgroundColor to Cyan
    * Check FontBold
    * FontSize to 24
    * Text to <
    * Width to 55
    * Height to 55
  1. Place a label on the top next to BsButton
    * Rename the label to VSpacer2
    * Text to blank
    * Width to 5
    * Height to 55
  1. Place a button on the top next to Vspacer2
    * Rename the button to Unused1
    * Text to blank
    * Width to 55
    * Height to 55
  1. Repeat the last 2 steps for VSpacer3 and Unused2
  1. Repeat the step 5 for VSpacer4 next to Unused2 button.
  1. Place a button on the top next to VSpacer4
    * Rename the button to OkButton
    * BackgroundColor to Green
    * Check FontBold
    * FontSize to 24
    * Text to Ok
    * Width to 55
    * Height to 55
### Second row of buttons ###
  1. Place a label just below the ClearButton
    * Rename the label to HSpacer1
    * Text to blank
    * Width to 55
    * Height to 5
  1. Place a button just below the HSpacer1
    * Leave the button name as Button1
    * BackgroundColor to Pink
    * Check FontBold
    * FontSize to 24
    * Text to 1
    * Width to 55
    * Height to 55
  1. Place a button on the second row next to Button1
    * Leave the button name as Button2
    * BackgroundColor to Pink
    * Check FontBold
    * FontSize to 24
    * Text to 2
    * Width to 55
    * Height to 55
  1. Repeat the step 3 for Button3, Button4 and Button5
### Third row of buttons ###
  * Repeat the same as the second row for Button6 thru Button9 except the last button
  1. Place a button on the third row next to Button9
    * Rename the button to Button0
    * BackgroundColor to Gray
    * Uncheck Enabled
    * Check FontBold
    * FontSize to 24
    * Text to 0
    * Width to 55
    * Height to 55
### Final steps ###
  1. Delete the two unused buttons from the first row
  1. Compare your finished keypad grid against the screenshot below:

<img src='http://i.imgur.com/zqHip.jpg' />

[Return to the main tutorial](KeypadTemplate.md)

### Edited by: ###
  * Geo Massar, 01/09/2012





