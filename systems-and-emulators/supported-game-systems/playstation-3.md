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

## Bios Information

PS3UPDAT.PUP file needs to be installed directly in rpcs3 emulator.

Run rpcs3.exe file in `\emulators\rpcs3` folder and **install firmware**

<figure><img src="https://i.imgur.com/18HE0DC.png" alt=""><figcaption></figcaption></figure>

Select the **PS3UPDAT.PUP** and run firmware installation.

Firmware will appear at the bottom of the emulator:

<figure><img src="https://i.imgur.com/JFjxamH.png" alt=""><figcaption></figcaption></figure>

## Controls

Controller configuration must be performed in the emulator.

<figure><img src="https://i.imgur.com/YoW67OI.png" alt=""><figcaption></figcaption></figure>

## Specific system information

### Adding PS3 games

PS3 games in rpcs3 are installed in the `\emulators\rpcs3\dev_hdd0\disc` folder for games in disk format and `\emulators\rpcs3\dev_hdd0\game` for dematerialized games.

\
Once the emulator is configured, the game has been added to the emulator from the "**Install package**" or/and "**Add games**" menu and the game is working succesfully from the emulator, create a m3u file in the `\roms\ps3` folder that points to the **EBOOT.BIN** file of the game in the `\emulators\rpcs3\dev_hdd0` game folder :&#x20;

<figure><img src="https://i.imgur.com/EGr0uq3.png" alt=""><figcaption><p>m3u file must point to the EBOOT.BIN file in the game folder</p></figcaption></figure>

{% hint style="info" %}
BATGUI tool offers an automatic m3u creation tool. Refer to the [BATGUI ](../../advanced-features/batgui.md)section of the wiki.
{% endhint %}

### Emulator configuration

Enable the following settings directly in rpcs3.

<figure><img src="https://i.imgur.com/Frjj2kY.png" alt=""><figcaption></figcaption></figure>
