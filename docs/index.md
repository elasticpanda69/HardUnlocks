---
hide:
  - navigation
---

# HardUnlocks Guide

## What is the Reset Glitch Hack (RGH)

Reset Glitch Hack (RGH) is a hardware modification which allows you to run unsigned code, mods, game 
backups, and homebrew. The hack relies on a vulnerability in the hardware found by GliGli that is 
triggered by sending a reset pulse to the processor at a specific moment, resulting in a power glitch 
that causes a bootloader hash check to return "valid" no matter what you have flashed in place of the 
stock bootloader. The timing of when and how long the pulse should be sent is dependent on the console 
and it may take some tweaking until it "glitches" and boots.

---

## What does this guide install?



## Requirements

* A basic toolkit which includes torx bits
* A device to read the consoles nand (xFlasher, NAND-X, JR-Programmer, MTX Flasher, Raspberry Pi Pico)
* Some 28-30awg single core wrapping wire (sometimes known as Kynar wire)
* A soldering iron and some soldering experience as you’ll be working with tiny points.


## Determining your motherboard model


## What exploitation method to use?

|   Exploit   |       Xenon        |       Zephyr       |    Falcon/Opus     |       Jasper       |      Tonasket      |      Trinity       |      Coronas       | Winchester |
|:-----------:|:------------------:|:------------------:|:------------------:|:------------------:|:------------------:|:------------------:|:------------------:|:----------:|
|   `JTAG`    | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |        :x:         |        :x:         |        :x:         |    :x:     |
|  `R-JTAG`   |  :material-minus:  |  :material-minus:  | :white_check_mark: | :white_check_mark: | :white_check_mark: |        :x:         |        :x:         |    :x:     |
|  `R-JSTOP`  |  :material-minus:  |  :material-minus:  | :white_check_mark: | :white_check_mark: | :white_check_mark: |        :x:         |        :x:         |    :x:     |
|   `RGH1`    |  :material-minus:  |  :material-minus:  | :white_check_mark: | :white_check_mark: | :white_check_mark: |        :x:         |        :x:         |    :x:     |
|  `RGH1.2`   |  :material-minus:  |  :material-minus:  | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |    :x:     |
|   `RGH2`    |        :x:         |  :material-minus:  |  :material-minus:  |  :material-minus:  |  :material-minus:  | :white_check_mark: | :white_check_mark: |    :x:     |
|   `S-RGH`   |        :x:         |  :material-minus:  |  :material-minus:  |  :material-minus:  |  :material-minus:  | :white_check_mark: | :white_check_mark: |    :x:     |
|   `Mufas`   |        :x:         |        :x:         |        :x:         |        :x:         |        :x:         | :white_check_mark: | :white_check_mark: |    :x:     |
|  `EXT_CLK`  | :white_check_mark: | :white_check_mark: |        TBD         |        TBD         |        TBD         |        TBD         |        TBD         |    :x:     |
|   `RGH3`    |        :x:         |        :x:         | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |    :x:     |