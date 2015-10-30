# How to build a keypad template #

The tutorial explains how to build a numeric keypad template which is usable to build apps such as Guess My Number game, Math Quiz workbook, and many others that you can think of.

Before we continue building the template, we need to know the size of the usable size of phone screens. We will use screen coordinates to place many buttons in the grid pattern for the keypad. The first step-by-step tutorial how to determine the size of usable screen is given in the [next page.](ScreenSize.md)

From the nini-tutorial, we figured out the size of the usable screen is 320 x 440 for the older phones. We can have a larger usable screen for newer phones but we will stick to the size of the older so that the app we create is able to run on all phones without having to scroll the screen up/down.

We need to partition four parts of the screen as following:
  * 320 x 110 for query/question/problem
  * 320 x 40  for user input
  * 320 x 110 for comments/instructions
  * 320 x 180 for keypad
The total height is 440 pixels. See the screenshot below:

<img src='http://i.imgur.com/3xhs4.jpg' alt='' />

Let us focus the keypad partition for now. The keypad will have three rows of 5 buttons as shown below:

<img src='http://i.imgur.com/cAArW.jpg' alt='' />

The two buttons on the top are not shown.

### Credits ###
  * Originator: Geo Massar
  * Supported/contributed users:
    * ...
### Edited/updated by: ###
  * Geo Massar
    * 01/07/2012 Continued writing the tutorial
  * ...