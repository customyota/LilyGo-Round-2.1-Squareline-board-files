# LilyGo-Round-2.1-Squareline-board-files
This repository contains the files necessary to add the LilyGo Round 2.1 TRGB display to Squareline using their Open Board Platform system.

It was created for Squareline Studio 1.4.1 utilizing Arduino_GFX 1.4.7 as the display driver and TouchLib 0.0.2 for touch support.

This was put together specifically for the Round 2.1 display, but TouchLib supports the drivers for all three boards. You should be able to just uncomment the appropriate define in main.cpp to use the other displays, but this is untested as I only have the 2.1 Round display.

To install, simply copy the folder and contents into your Squareline/boards directory.

This is set up for PlatformIO, using in the Arduino IDE will require you adjust the folder structure or to install Arduino_GFX and TouchLib separately.
