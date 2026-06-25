### The overlays are meant to be resized in OBS to half size or smaller to smooth out jagged edges. You should turn on Bilinear Scale Filtering for the OBS source by right clicking, going into the "Scale Filtering" submenu, and selecting "Bilinear". It will look much nicer.

**INSTALL THIS FIRST.** These presets are made to be used with the Input Overlay plugin for OBS (tested with version 5.0.6): https://github.com/univrsal/input-overlay Version 5.1.0 works better for some people too.

After installing the above plugin, simply download matching json and png files to use with the OBS plugin (or download the zip file with all of them in the [releases](https://github.com/Phetri-A/Phetri-input-overlays/releases) section).

The png files have only have a few colors with no gradients to make for easy editing to suite your tastes. There are also 13 pre-made colors if you don't know how to change it or just can't be bothered.

Making your own preset is not that hard to do if you want yours to look a different way. Here's a video I made explaining how the config and texture files work: https://www.youtube.com/watch?v=D9M6xqsPZ-Q

So far there are PS4, PS5, and Xbox controller presets based on the first-party controller designs.

Note that input overlays are not automatically synchronized with gameplay capture. You can add a render delay to the overlay with a filter in OBS to compensate, if you care. The best method I found is to go into the menu in a game and see what the delay is between the input overlay showing a directional input and the game menu responding. Then you can adjust the render delay until the two are more-or-less in sync. Personally, a 45-millisecond delay works pretty well.

***

![preview gif of controller overlays](https://github.com/Phetri-A/Phetri-input-overlays/blob/main/PREVIEW.gif)

***

![preview of 13 available colors](https://github.com/Phetri-A/Phetri-input-overlays/blob/main/controller%20colors%20PREVIEW.png)

(colors also available for PS4 and PS5 presets)
