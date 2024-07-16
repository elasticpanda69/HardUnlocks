# Installing Multi-Disc Games with Aurora

## Prerequisites

Dashlaunch > Behaviors > autoswap[enabled]

!!! autoswap
    
    This allows for Aurora to automatically switch back and forth between 2 or more play discs.

!!! warning 

    Do not enable autoswap if you use FSD or swap.xex for this!

## Extracted Files Format

### Two Discs (An "Install Disc" & A "Play Disc")

Install Disc: 

1.  Install normally through the retail dash by inserting the disc and running it. 

!!! Note

    Once you have installed the mandatory content from the "Install Disc," you don't need to keep the disc on your HDD. Either delete it, or save it on a PC to save space on your console.

Play Disc:

1.  Insert the Play Disc and in Aurora go to File Manager > DVD > Press the X button on every file, except $SystemUpdate, to select them. 
2.  Press DPAD Left > select Copy
3.  Press RB and select HDD1/Games/[Title of Game]/[Paste files here]

``` { .yaml .no-copy }
Cache
Content
Games
    Halo 4
        [place extracted files here]
```

### Two Discs (Two "Play" Discs)

Disc 1: 

1.  Insert the Play Disc and in Aurora go to File Manager > DVD > Press the X button on every file, except $SystemUpdate, to select them. 
2.  Press DPAD Left > select Copy
3.  Press RB and select HDD1/Games/[Title of Game]/[Disc 1]/[Paste files here]

Disc 2: 

1.  Insert the Play Disc and in Aurora go to File Manager > DVD > Press the X button on every file, except $SystemUpdate, to select them. 
2.  Press DPAD Left > select Copy
3.  Press RB and select HDD1/Games/[Title of Game]/[Disc 2]/[Paste files here]

``` { .yaml .no-copy }
Cache
Content
Games
    The Witcher 2
        Disc 1
            [place extracted files here]
        Disc 2
            [place extracted files here]
```

## GoD Container Format

### Prerequisites

Aurora Disc to GOD Installer
!!! Note

    You can download scripts in Aurora by going to System > Scripts > Aurora Repo Browser > Utility Scripts > Aurora Disc to GOD installer. 


### Two Discs (An "Install Disc" & A "Play Disc")

Install Disc: 

1.  Install normally through the retail dash by inserting the disc and running it. 

Play Disc:

1.  Insert the Play Disc and in Aurora go to System > Scripts > Aurora Disc to GOD press A to launch.
2.  Select the directory you want to save the GOD Container to. HDD1 > Content > highlight 0000000000000000 (16 zeroes) and press Y to select.
3.  Create content directories? Select Yes

### Two Discs (Two "Play" Discs)

Play Disc 1:

1.  Insert the Play Disc and in Aurora go to System > Scripts > Aurora Disc to GOD press A to launch.
2.  Select the directory you want to save the GOD Container to. HDD1 > Content > highlight 0000000000000000 (16 zeroes) and press Y to select.
3.  Create content directories? Select Yes

Play Disc 2:

1.  Insert the Play Disc and in Aurora go to System > Scripts > Aurora Disc to GOD press A to launch.
2.  Select the directory you want to save the GOD Container to. HDD1 > Content > highlight 0000000000000000 (16 zeroes) and press Y to select.
3.  Create content directories? Select Yes

