# How to build a flashlight app #

## Screen designing ##

  1. Create a new project named `FlashlightApp` and change its properties as following:
    * `BackgroundColor` to Black
    * `ScreenOrientation` to Portrait
    * Title to Flashlight
    * Uncheck Scrollable
  1. Place `HorizontalArrangement` (in the Screen Arrangement category) on the screen and change its width to Fit Parent
  1. Place a button inside of the `HorizontalArrangement` and rename Button1 to `ToggleButton`, Change its properties:
    * `BackgroundColor` to Cyan (or any color you like)
    * `FontBold` to checked
    * Text to `Turn on`}
  1. Place `VerticalArrangement` at the left of the button
    * Width to Fit Parent
    * Height to Fit Parent
  1. Place `VerticalArrangement` at the right of the button
    * Width to Fit Parent
    * Height to Fit Parent
  1. Place Canvas on the top of the screen
    * `BackgroundColor` to Black
    * Width to Fit Parent
    * Height to Fit Parent

### Finished Design ###

<img src='http://i.imgur.com/BM4I0.png' alt='' />

## Block building ##

  1. In Definition drawer under Built-in tab, drag out _def_ **Variable** block
    * Change **Variable** to **`toggleValue`**
    * Attach _as_ { _number_ **1** }
  1. In `ToggleButton` drawer under My Blocks tab, drag out _when_ **`ToggleButton`.Click** block
  1. In My Definitions drawer under My Blocks tab, drag out _set global_ **`toggleValue`** into the _when_ block
    * Attach _to_, { { _number_ **2** } / { _global_ **`toggleValue`** } }
  1. In Control drawer under Built-in tab, drag out _ifelse_ block into the _when_ block
    * Attach _test_ { { _global_ **`toggleValue`** } = { _number_ **2** } }
    * Add blocks to _then-do_ clause as following:
      * In Canvas1 drawer under My Blocks, drag out **Canvas1.`BackgroundColor`** block and set it to _color_ **White**
      * In the `ToggleButton` drawer, drag out _set_ **`ToggleButton`.Text** block and set it to _text_ `Turn off`
    * Repeat the last two steps for _else-do_ clause:
      * Set **Canvas1.`BackgroundColor`** to _color_ **Black**
      * Set **`ToggleButton`.Text** to `Turn off`

> ### Finished Block Diagram ###

<img src='http://i.imgur.com/06WY6.png' alt='' />

> ## Run the app ##

<img src='http://i.imgur.com/BM4I0.png' alt='' />

<img src='http://i.imgur.com/BkhIl.png' alt='' />

### The source is available in the Downloads section. <a href='http://code.google.com/p/ai-docs/downloads/detail?name=FlashlightPack.1.0.zip'> Fetch it.</a> ###

### Edited by: ###
  * Geo Massar, 2012-01-22
