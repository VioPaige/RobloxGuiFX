# GuiFX
this roblox module contains functions for the coolest gui effects that fit your game!




## Download
You can get the model that contains this modulescript [here](https://www.roblox.com/library/8556157102/GuiFX) in order to use it





## Description of functions

**Make sure to remember, if a function returns nil, it doesn't mean that the function returned false, instead the function failed to retrieve the player data**

***This module only supports effects for gui objects with anchor point (0,0); Support for different anchor points will be added later***

### Module.CircleGuiObject(guiobject, pixelwidth, color, uicorner, speed)
* this function starts circling a gui object to get the player's attention (or as decoration)

### Module.DeCircleGuiObject(guiobject)
* this function stops the circling of a gui object





## Api
```
Module.CircleGuiObject()
  - required arguments:
    - guiobject : Instance (the gui object you want circled - this can be a frame, image, label, button, etc.)
  - optional arguments:
    - pixelwidth : Integer (the thickness you want the circling line to have in pixels - the default is 5 pixels)
    - color : Color3 OR ColorSequence (the colour you want the circling line to be - default is RGB(0, 255, 0)
    - uicorner : Instance (if you want the circling to have a different ui corner than the circled object, you can provide a custom uicorner instance here)
    - speed : Integer (the length of one full rotation of the circling in seconds - default is 3 seconds)
  - Effect:
    - Starts circling around the gui object with the specified speed, color, thickness, and corner
    
Module.DeCircleGuiObject()
  - required arguments:
    - guiobject : Instance (the guiobject that is currently circling that you want to stop)
```
