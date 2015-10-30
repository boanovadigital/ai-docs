[TOC](TableOfContents.md) > [KeypadTemplate](KeypadTemplate.md) > ScreenSize

---

# How to determine a viewable screen size #

This is a mini-tutorial for building a keypad template. In order to place buttons properly in grid pattern for the keypad at the bottom of the screen like the virtual keyboard in Android, we need to know what exact viewable screen size would be. The screen size of some older phone models is 320 by 480 pixels in portrait mode. The current version of App Inventor (Android API 8) uses that size. The screen includes notification bar and title bar at the top. How much is the rest of the screen for an app to display?

Let's build an app in App Inventor to determine the viewable screen size.

  1. Open a new project named ScreenSize.
  1. Change Screen1 properties as following:
    * BackgroundColor to Black
    * ScreenOrientation to Portrait
    * Title to Screen Size
    * Be sure Scrollable is checked
  1. Place a label on the screen named WhiteScreen and change its properties:
    * BackgroundColor to White
    * Text to Screen Size 320 x 400
    * Width to 320 pixels
    * Height to 400 pixels
  1. Place a label on the screen below the first label named BlueStrip and change its properties:
    * BackgroundColor to Blue
    * Text to blank
    * Width to 320 pixels
    * Height to 20 pixels
  1. Open the Blocks Editor if not done.
  1. Start a new emulator if not done.
  1. Connect to the emulator.
  1. If the blue strip is shown on the screen, increase the height of the first label by say 10 pixels until the blue strip disappears.

The final value of the height of the first label (WhiteScreen) is the height of the viewable screen.

The source is available in the Downloads section of this project.