---
description: Sony
---

# Playstation 3

<div align="left">

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/5149a33eed46b2af638b06119397d4023b75131f/art/logos/ps3.svg" alt=""><figcaption></figcaption></figure>

</div>

Game Console - Lifespan: 2006 - 2017

{% embed url="https://en.wikipedia.org/wiki/PlayStation_3" %}

## Information

| **Emulators**      | <ul><li>rpcs3</li></ul>                              |
| ------------------ | ---------------------------------------------------- |
| **File folder**    | :open\_file\_folder: roms \ :open\_file\_folder: ps3 |
| **File extension** | .m3u .ps3 .iso .7z .zip .rar .squashfs               |

## Features

| Retroachievements | NetPlay |
| ----------------- | ------- |
| NO                | NO      |

## BIOS

| BIOS file    | Folder  | md5                              |
| ------------ | ------- | -------------------------------- |
| PS3UPDAT.PUP | `\bios` | 95307e1b51d3bcc33a274db91488d29f |

#### Automatic firmware installation

The first time the rpcs3 emulator is launched, if the PS3UPDAT.PUP file is present in you \bios folder, the emulator will automatically prompt to install the firmware, once the firmware installed you can close and relaunch the game.

<div align="left">

<figure><img src="https://i.imgur.com/1ovzizA.png" alt=""><figcaption></figcaption></figure>

</div>

#### Manual firmware installation

Run rpcs3.exe file in `\emulators\rpcs3` folder and **install firmware**

<div align="left">

<figure><img src="https://i.imgur.com/18HE0DC.png" alt=""><figcaption></figcaption></figure>

</div>

Select the **PS3UPDAT.PUP** and run firmware installation.

Firmware will appear at the bottom of the emulator:

<div align="left">

<figure><img src="https://i.imgur.com/JFjxamH.png" alt=""><figcaption></figcaption></figure>

</div>

## Controls

{% hint style="info" %}
The following controllers can be autoconfigured from Retrobat to RPCS3:

* XInput controllers
* Dualshock & DualSense controllers
* Nintendo Switch Pro controller
{% endhint %}

| RetroBat key                                                                              | Playstation 3 key  |
| ----------------------------------------------------------------------------------------- | ------------------ |
| START                                                                                     | START              |
| SELECT / BACK                                                                             | SELECT             |
| D-PAD                                                                                     | D-PAD              |
| Left analog stick                                                                         | Left analog stick  |
| Right analog stick                                                                        | Right analog stick |
| ![A](<../../../../.gitbook/assets/image (1) (2) (1).png>)                                 | Cross              |
| ![B](<../../../../.gitbook/assets/image (4) (1).png>)                                     | Circle             |
| <img src="../../../../.gitbook/assets/image (3) (1) (2).png" alt="" data-size="original"> | Triangle           |
| <img src="../../../../.gitbook/assets/image (2) (1) (1).png" alt="" data-size="line">     | Square             |
| L1                                                                                        | L1                 |
| R1                                                                                        | R1                 |
| L2                                                                                        | L2                 |
| R2                                                                                        | R2                 |
| L3                                                                                        | L3                 |
| R3                                                                                        | R3                 |

## System Features

### Adding PS3 games

There are 2 types of PS3 games available: Blu-Ray discs and PlayStation Network titles (PSN):

* Title IDs that start with a B are Blu-Ray disc titles.
* Title IDs that start with a N are PSN titles.

<div align="left">

<figure><img src="https://i.imgur.com/EsmEoB4.png" alt=""><figcaption></figcaption></figure>

</div>

Blu-ray disc titles can be copied directly in the  `\roms\ps3` folder while PSN titles need to be added in the `\emulators\rpcs3\dev_hdd0\game` folder of your RetroBat installation.

#### Adding Blu-ray disc title

Simply copy the game folder to the `\roms\ps3` folder of your RetroBat installation and rename the folder with a .ps3 extension:

<div align="left">

<figure><img src="https://i.imgur.com/E98BUs9.png" alt=""><figcaption></figcaption></figure>

</div>

The game will directly be available in RetroBat.

#### Adding PSN titles

\
Once the game has been added to the emulator from the "**Install package**" or/and "**Add games**" menu and the game is working succesfully from the emulator, create a m3u file in the `\roms\ps3` folder that points to the **EBOOT.BIN** file of the game in the `\emulators\rpcs3\dev_hdd0\game` game folder:



<div align="left">

<figure><img src="https://i.imgur.com/E1igTL6.png" alt=""><figcaption></figcaption></figure>

</div>

<div align="left">

<figure><img src="https://i.imgur.com/LmL6NUh.png" alt=""><figcaption></figcaption></figure>

</div>

{% hint style="info" %}
BATGUI tool offers an automatic m3u creation tool. Refer to the [BATGUI ](../../../../advanced-features/batgui.md)section of the wiki.
{% endhint %}
