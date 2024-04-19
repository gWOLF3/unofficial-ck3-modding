> written from linux user perspective coming into Windows ecosystem for game modding. 

## Reqs

- Windows Shell: Terminal for Windows
- VS Code Editor
- wsl
- steam (to buy/install ck3)




### my quickstart
1) open shell (defaults to powershell)
2) start `bash` -> kick into linux style env
3) 
4) 

> NOTE: this is not the only way to do it. might be helpful to get started by reading the modding wiki here if you want to use Steam for example; https://ck3.paradoxwikis.com/Modding

### important PATHS

1) CK3 run folder:
```
/mnt/c/Program Files (x86)/Steam/steamapps/common/Crusader Kings III/binaries
```

2) CK3 mod folder:
```
/mnt/c/Users/glenn/OneDrive/Documents/Paradox Interactive/Crusader Kings III/mod
```
> NOTE: you can find this by getting to the folder, right clicking and copying the path 

## Useful Launch options: 
`-debug_mode` - enables dev tooltips and interactions

`-develop` - enables hot reload of most files

`-nographics` - launches the game without creating a window or rendering anything and starts an observer game

`-continuelastsave` - can be used in a shortcut to ck3.exe to automatically load the last save, same as pressing Resume in the launcher 

`-mapeditor` - opens the map editor

`-benchmark` - runs an automated test for 1.5 years, moving the camera around and opening various windows. Outputs timer_dump logs showing how much time each tick took to process (convert them to tables and make graphs to analyze)

---

### Links

**Modding wiki (CK3)**: <--important https://ck3.paradoxwikis.com/Modding

"getting started" CK3 modding video: 
https://youtu.be/uu_Zxf4ul2g?si=wauTHtQ8AQvhLvk5

Starting in Debug mode: https://www.rockpapershotgun.com/crusader-kings-3-cheats-debug-mode-and-console-commands


Modding Wiki (CK3-AGOT): https://ck3.paradoxwikis.com/CK3AGOT

Modding Tools List: https://ck3.paradoxwikis.com/Modding_tools

