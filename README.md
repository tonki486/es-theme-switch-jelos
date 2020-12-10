# Nintendo Switch Theme for EmulationStation on 480x320 displays
Over the last few days I have been working on this theme further. I updated all the icons a few days ago and decided to update the rest of the theme. 

(Pictures Below)

There are many changes in this newest version, including:

- The Switch Theme no longer has two separate versions. As of this update, the light and dark variants have now been combined into one theme. The colors are toggleable via the theme.xml file. 
- Colors updated to match system
- Selector bar has been added. Slim line next to selected game name. 
- Marquee is now centered under video

Another big thing is the slimming down of the theme. Between the combination of light and dark colors and compression on the tiles, the whole theme is now under 5mb! Also, the memory needed is shrunken as well. You can get away with as little as 20mb of VRAM. Good news to those with full game sets and videos!

Pictures

System View - Light and Dark

![https://i.imgur.com/aIRWDFB.png](https://i.imgur.com/aIRWDFB.png)

# Fork notes - Jetup13
- This fork was desgined for smaller displays that are around 480x320 (OGA, RGB10, RK2020, ect....)
- Added Gridview
- Added more system images and renamed some names
- Added a clock for supported emulationstation builds
- Changed font size for system, gamelist, and emulationstation main menu views
- Changed release date to show only year instead of M/D/Y. This can be changed by removing the line <format>%Y</format> in the theme.xml
- Added toggle options to switch between theme colors
- Added toggle option for on-screen help image to turn off or on
- Added toggle option to force system name to uppercase
- Added 11 new theme colors (Black, Yellow, Teal, Mint Green, Rose Pink, Red, Dark Crystal, Dark Indigo Crystal, Dark Blue Crystal, Dark Mint Crystal, Dark Red Crystal)
