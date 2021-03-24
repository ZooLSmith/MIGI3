# Multiple Items_Game Includer v3
 
Contains builds and info for the autoupdater. The project is closed source to fight cheating on public servers.

![preview](https://raw.githubusercontent.com/ZooLSmith/MIGI3/main/preview.png)

## Info

MIGI3 is a full rewrite of MIGI (C# WPF) in Python+Angular.

MIGI is used to combine CS:GO mod addons together in order to toy with Valve's items_game and various other core game files, but also to give mappers, modders, a more friendly environement when working on CS:GO projects, allowing them to tweak a lot of aspects of the game without interfering with their vanilla install.

Visit [ZooL's Discord (MIGI's home)](http://zoolsmith.free.fr/discord) for more information, addons download, help on modding with it and more.

## Use cases

- Modding the game for fun, to add or edit weapons, retexture, skins..
- Testing mods without the hassle of editing pak01, breaking your install or making a mess in your game folder..
- Easier mapping environement, replacing ugly ERROR models, weapon tools to help mappers in-game..
- Run through [HLAE](https://github.com/advancedfx/advancedfx) for movie making purposes, tweaks on textures, sounds, models, particles...

## Installation

#### Windows
- Grab the latest [migi.exe](http://raw.githubusercontent.com/ZooLSmith/MIGI3/main/migi.exe)
- Make MIGI.EXE an exception for your anti-virus
- Put it inside your CSGO installation next to CSGO.EXE
- Run as admin to build the symbolic links (no visuals will show up)
- Run normally
- Create/Download M_ and P_ addons
- Generate Pak01 with the tool
- Run CS:GO through the tool or with "-game migi/csgo"

#### Linux
Almost the same steps. Linux version is only a CLI for now.
- Download [migi_linux](http://raw.githubusercontent.com/ZooLSmith/MIGI3/main/migi_linux)
- Put it next to csgo.sh
- Run it.

## Modules in this project

| Python | Web |
|:-:|:-:|
|[pywebview](https://pywebview.flowrl.com/)|[Angular](https://angular.io/)|
|[PyInstaller](https://www.pyinstaller.org/)|[ngx-slimscroll](https://www.npmjs.com/package/ngx-slimscroll)|
|[vpk](https://github.com/ValvePython/vpk)||

## Disclaimer

This tool isn't associated or meant to be used with cheats, any mention of sv_pure bypassing or using the tool alongside cheats will get you banned from communities using MIGI the way it's meant to be used.
