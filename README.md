# This is OUTDATED!
This project is **outdated** since 2019.

If you still want to use _**similar thing for streaming**_ (obs and other streaming softwares), You can use [_**This extension**_](https://chrome.google.com/webstore/detail/soundcloud-player/oackhlcggjandamnkggpfhfjbnecefej) ( [_github page_](https://github.com/S4WA/SoundCloud-Player) ) instead of this. But **without Discord Status** function. [Details (github wiki)](https://github.com/S4WA/SoundCloud-Player/wiki/For-Streamers-and-Gamers).

# Soundcloud Status
![image1](https://github.com/S4WA/files/blob/master/soundcloud-status/Screenshot_1.png?raw=true)  
![image2](https://github.com/S4WA/files/blob/master/soundcloud-status/Screenshot_2.png?raw=true)  

# Environment
 - Python 3.7.4
   - [pypresence](https://github.com/qwertyquerty/pypresence)
   - [urllib3](https://github.com/urllib3/urllib3)
 - Browser
   - [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
     - [Script](https://github.com/S4WA/soundcloud-status/raw/master/chrome/contents.user.js)

※ Only works in Windows

# How to install
1. Install [The script](https://github.com/S4WA/soundcloud-status/raw/master/chrome/contents.user.js) to Tampermonkey
2. Run ``server/start.bat`` 
3. Open the SoundCloud.com

# OBS
![image3](https://github.com/S4WA/files/blob/master/soundcloud-status/Screenshot_3.png?raw=true)  
Add a source for these pictures in OBS

``soundcloud-status/server``  
- ``artwork.jpg``  
- ``export.txt``  

![image4](https://github.com/S4WA/files/blob/master/soundcloud-status/Screenshot_4.png?raw=true)  

※ You can change format from here. [``server/config.ini``](https://github.com/S4WA/soundcloud-status/blob/master/server/config.ini)
