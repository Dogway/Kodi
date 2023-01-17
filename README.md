# Kodi Nexus/Omega - QoL fixes

This repo includes some userdata defaults to fix some issues like HQ scaling being hard-code disabled (on Android at least), better episode regex, network buffer improvements, no splash screen, etc. Basically base Kodi with some common sense changes.

Also includes a "mod" of Estuary that includes 'year', 'rating' and 'my rating' on the title bar on InfoWall view mode. Removes some redundant and unneeded horizontal slider sections, and adds some shiny icons for the video info at the bottom (see image below).

I also uploaded a modified version of the 'Tag Overview' addon that works on Nexus, and revamped its GUI. I rely on this addon quite a lot to tag movies so they go into their own Nodes (I also supplied a few default nodes that might be of your interest, aside from the bundled ones)

![](https://github.com/Dogway/Kodi/blob/main/images/A_logos.png)

![](https://github.com/Dogway/Kodi/blob/main/images/B_collections.png)

------

## Full Changelog:

### Kodi
*   No Splash screen
*   Enable HQ scaling for other than H263 files (if passes the HQ & rule in settings)
*   Improve regex for Movie Title detection
*   Improve regex for TV Shows skipping parsing episodes CRC strings (wrong episode detection bug)
*   Increase <songinfoduration> to keep song info on screen by default
*   Adjust default values for watched status
*   Adjust network buffer settings
*   Change default Estuary color theme to Concrete
*   Change font to "Arial" for displaying Asian typefaces
### Estuary
*   Add 'year', 'rating' and 'my rating' on the title bar on InfoWall 
*   Include both FileList and Plot on Collections
*   Remove some horizontal slider sections (recently added/watched/InProgress)
*   Replace video/music info icons
*   Nodes list increased from 20 to 25
*   Added Artist to Musicvideos
*   Reordered MusicVideo title to "Artist - Song"
*   Remove watched for musicvideos
*   Add 16:10 entry for Tablets
### Tag Overview
*   Make it work back on Nexus/Omega
*   Update GUI to current Estuary
### Node Editor
*   Add option to sort by My Rating (userrating)
*   Add some default convenience nodes (ALL, Rating, To Watch, 4k, 720p, SD, decades, superheroes, etc)