---
description: Sony
---

# Playstation 3

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/5149a33eed46b2af638b06119397d4023b75131f/art/logos/ps3.svg" alt=""><figcaption></figcaption></figure>

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

<figure><img src="https://i.imgur.com/1ovzizA.png" alt=""><figcaption></figcaption></figure>

#### Manual firmware installation

Run rpcs3.exe file in `\emulators\rpcs3` folder and **install firmware**

<figure><img src="https://i.imgur.com/18HE0DC.png" alt=""><figcaption></figcaption></figure>

Select the **PS3UPDAT.PUP** and run firmware installation.

Firmware will appear at the bottom of the emulator:

<figure><img src="https://i.imgur.com/JFjxamH.png" alt=""><figcaption></figcaption></figure>

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

PS3 games in rpcs3 are installed in the `\emulators\rpcs3\dev_hdd0\disc` folder for games in disk format and `\emulators\rpcs3\dev_hdd0\game` for dematerialized games.

\
Once the emulator is configured, the game has been added to the emulator from the "**Install package**" or/and "**Add games**" menu and the game is working succesfully from the emulator, create a m3u file in the `\roms\ps3` folder that points to the **EBOOT.BIN** file of the game in the `\emulators\rpcs3\dev_hdd0` game folder :&#x20;

<figure><img src="https://i.imgur.com/EGr0uq3.png" alt=""><figcaption><p>m3u file must point to the EBOOT.BIN file in the game folder</p></figcaption></figure>

{% hint style="info" %}
BATGUI tool offers an automatic m3u creation tool. Refer to the [BATGUI ](../../../../advanced-features/batgui.md)section of the wiki.
{% endhint %}
