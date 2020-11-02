# Nintendo Switch Theme for EmulationStation on 480x320 displays
Over the last few days I have been working on this theme further. I updated all the icons a few days ago and decided to update the rest of the theme. 

(Pictures Below)

There are many changes in this newest version, including:

- The Switch Theme no longer has two separate versions. As of this update, the light and dark variants have now been combined into one theme. The colors are toggleable via the theme.xml file. 
- You now have the option to switch between Playstation and Xbox buttons. (Also toggleable via the theme.xml) 
- The theme now supports 4:3 aspect ratio (Theme.xml)
- Colors updated to match system
- Selector bar has been added. Slim line next to selected game name. 
- Marquee is now centered under video

Another big thing is the slimming down of the theme. Between the combination of light and dark colors and compression on the tiles, the whole theme is now under 5mb! Also, the memory needed is shrunken as well. You can get away with as little as 20mb of VRAM. Good news to those with full game sets and videos!

Pictures

System View - Light and Dark

![https://snag.gy/I2vYSK.jpg](https://snag.gy/I2vYSK.jpg)

PS & Xbox Buttons

![](https://snag.gy/Q62Z9q.jpg)

# Fork notes - Jetup13
- This fork was desgined for smaller displays that are around 480x320 (OGA, RGB10, RK2020, ect....)
- Added more system images and renamed some names
- Added a clock for supported emulationstation builds
- Changed font size for gamelist and description to make it more visable
- Changed release date to show only year instead of M/D/Y. This can be changed by removing the line <format>%Y</format> in the theme.xml
- Added Toggle options to switch between Dark and Light themes
- Added Gridview
