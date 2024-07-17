# SNES Emulators

## SNES360

!!! warning
    
    This emulator has achievements. For that reason it is very important not to be on Xbox Live while using this emulator.

### Features

- Graphics/Sound
- Achievements 
- XUI user interface
- SRAM save support linked to a user profile
- Filters : Simple2x, Scanlines, TV Mode, Super Eagle, Super 2xSAI, HQ2x
- Turbo Mode (Right Trigger)
- Aspect Ratio/Stretch Mode support
- SaveStates (currently 1 per rom)
- Previews

### Downloads

| File      | Version | Link                                                                                           |
|-----------|:-------:|------------------------------------------------------------------------------------------------|
| `SNES360` |  0.32   | [Download](https://drive.google.com/file/d/1IoPp5nIQ45Col3lWyLkCBBJdyKXijkMO/view?usp=sharing) |

### Installation 

Download from the link above and extract the folder SNES360. Copy this 
folder to your Xbox 360’s hard drive. Launch the Snes360.xex.

### File Structure
```
Cache
Content
Emulators
    SNES360
        media
        roms
            Super Mario World (USA).sfc
            2020 Super Baseball (U).smc
            ... other SNES roms
        settings.xml
        Snes360.xex
```

!!! Note
    
    Roms can not be in their own folder. They must be placed exactly like the file structure above.

### settings.xml

```
<Settings>
	<MappedDrive DriveName="GAME (XeX Location)" Path="GAME:\roms\"/>
	<MappedDrive DriveName="HDD" Path="HDD:\Emulators\SNES360\roms\"/>
	<PreviewPath>hdd:\Emulators\SNES360\preview\</PreviewPath> 
</Settings>
```

Use this to define where your roms will go. You can add as many MappedDrive tags as you need. Valid Devices are:
``` { .yaml .no-copy }
GAME:
USB0:
USB1:
USB2:
DVD:
HDD:
MEMUNIT0:
MEMUNIT1:
```

The PreviewPath tag will specify where you want your Preview Images to be stored. Default is:
```
hdd:\Emulators\SNES360\Preview\
```

!!! Note

    If you downloaded SNES360 from an alternative source and not from the link below your PreviewPath will be different 
    from that of this tutorial.

### Controls

Right & Left Thumbstick pressed simultaneously will take you to the options menu.
