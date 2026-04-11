### The overlays are meant to be resized in OBS to half size or smaller to smooth out jagged edges. You should turn on Bilinear Scale Filtering for the OBS source by right clicking, going into the "Scale Filtering" submenu, and selecting "Bilinear". It will look much nicer.

These presets are made to be used with the Input Overlay plugin for OBS (tested with version 5.0.6): https://github.com/univrsal/input-overlay

Simply download matching json and png files to use with the OBS plugin.

The png files have only have a few colors with no gradients to make for easy editing to suite your tastes.

Making your own preset is not that hard to do if you want yours to look a different way.

So far there are PS4, PS5, and Xbox controller presets based on the first-party controller designs.

Note that input overlays are not automatically synchronized with gameplay capture. You can add a render delay to the overlay with a filter in OBS to compensate, if you care. The best method I found is to go into the menu in a game and see what the delay is between the input overlay showing a directional input and the game menu responding. Then you can adjust the render delay until the two are more-or-less in sync. Personally, a 45-millisecond delay works pretty well.

***

![preview gif of controller overlays](https://github.com/Phetri-A/Phetri-input-overlays/blob/main/PREVIEW.gif)
