# Aurora

![](../assets/images/Aurora1.png){: style="width: 49%; height: auto"}
![](../assets/images/Aurora2.png){: style="width: 49%; height: auto"}

## What Is It?

Aurora is a custom dashboard focused around the coverflow design of its game launcher. Features include customizable skins, automatic download of game updates and cover art, the ability to organize games into categories, FTP support, integrated system link online play using LiNK, and a plugin system.

It is the most recently updated dashboard, with an official website at XboxUnity.net and an official support forum at RealModScene.com. An FAQ can be found here.

## Features

* FTP Support
* Skin Customization
* Title Update Support
* Trainers

## Downloads

| File                  | Version | Link                                                                                           |
|-----------------------|:-------:|------------------------------------------------------------------------------------------------|
| `Aurora`              | 0.7b.2  | [Download](http://phoenix.xboxunity.net/downloads/Aurora%200.7b.2%20-%20Release%20Package.rar) |
| `Aurora Asset Editor` |  1.4.2  | [Download](https://github.com/XboxUnity/AuroraAssetEditor/releases)                            |
| `Aurora Trainer Pack` |    -    | [Download](https://drive.google.com/file/d/1a46uoDem1OvK80HhVk1Mvwdrtku9jS7g/view?usp=sharing) |

!!! Note

    Aurora Asset Editor is not necessary for Aurora installation. It is a graphic editor for Aurora's .asset files. See below for more details.

## Prerequisites

* [x] [XeXMenu](../xexmenu.md)
* [x] [Dashlaunch](../dashlaunch)

## Installation

Download the latest Aurora build from XboxUnity.net and extract the files into a new folder named Aurora. Copy this folder to your Xbox 360’s hard drive. Launch the Aurora.xex to start the dashboard, or set it as your default dashboard using DashLaunch.

## File Structure

``` { .yaml .no-copy }
Cache (partition 0)
Content
Emulators
Homebrew/Apps
    Aurora (Place unzipped Aurora folder here)
        Data
            Logs
        Media
            Assets
            Effects
            Fonts
            Layouts
            Scripts
        Plugins
        Skins (Place aurora skins or .xzp files here)
        User
            Backgrounds
            Icons
            Import
            Scripts
            Trainers
        Aurora.xex
        live.json
        nxeart
    ... other applications
```

## Controls

A: Enter / Confirm / Launch

B: View Settings / Back

X: Browse/Search games / Select multiple files or folders in file manager

Y: Game details / Sync windows’ working directories in file manager

Start: Settings

Back: System info / tools

LB/RB: Change content category

LT/RT: Scroll through content (fast)

Left Thumbstick: Scroll through content (slow)

Right Thumbstick: Peek left/right

DPAD: Move left/right

## Settings



## Plugins



## Skins

## Trainers

Aurora 0.5b and below:
``` { .yaml .no-copy }
Cache (partition 0)
Content
Emulators
Homebrew/Apps
    Aurora 
        Trainers (place trainer folders here)
```

Aurora 0.6b+:
``` { .yaml .no-copy }
Cache (partition 0)
Content
Emulators
Homebrew/Apps
    Aurora 
        User
            Trainers (place trainer folders here)
```

## FAQ

---

## Aurora Asset Editor

### What is it?

Aurora Asset Editor is a program for Windows PC that allows you to update/edit boxart/covers, backgrounds, icons/banners, screenshots, as well as other aurora game assets. 

### Installation

1. Download and unpack the .zip folder to your desktop. 
2. Run AuroraAssetEditor.exe

!!! note "FTP Assets"

    If you have not messed with the FTP settings with in Aurora itself the default Username & Password will already be populated for you. If this is not the case the default Username & Password are both `xboxftp`

