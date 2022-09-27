---
description: Sony
---

# Playstation 3

![](<../../.gitbook/assets/image (5).png>)

Type: Game Console

Lifespan: 2006 - 2017

Wikipedia page : [https://en.wikipedia.org/wiki/PlayStation\_3](https://en.wikipedia.org/wiki/PlayStation\_3)

Emulator page : [https://rpcs3.net/](https://rpcs3.net/)

Emulator wiki : [https://wiki.rpcs3.net/index.php?title=Main\_Page](https://wiki.rpcs3.net/index.php?title=Main\_Page)

## Information

**Emulators/cores:**

* rpcs3

**Roms folder:**

* roms/ps3

**Roms formats:**

m3u, ps3, iso, 7z, zip, rar, squashfs

## Bios Information

PS3UPDAT.PUP file needs to be installed directly in rpcs3 emulator.

Run rpcs3.exe file in /emulators/rpcs3/ folder and install firmware:

<figure><img src="https://i.imgur.com/18HE0DC.png" alt=""><figcaption></figcaption></figure>

Select the PS3UPDAT.PUP and run firmware installation.

Firmware will appear at the bottom of the emulator:

<figure><img src="https://i.imgur.com/JFjxamH.png" alt=""><figcaption></figcaption></figure>

## Controls

Retrobat does not offer automatic controller configuration for rpcs3.

Controller configuration should be performed directly in the emulator:

<figure><img src="https://i.imgur.com/YoW67OI.png" alt=""><figcaption></figcaption></figure>

## Specific system information

### Adding PS3 games

PS3 games in rpcs3 are installed in the **\emulators\rpcs3\dev\_hdd0\disc** folder for games in disk format and **\emulators\rpcs3\dev\_hdd0\game** for dematerialized games.

\
Once the emulator is configured and the game has been added to the emulator from the "Install package" or/and "Add games" menu AND IT IS WORKING DIRECTLY FROM THE EMULATOR, create a m3u file in the "/roms/ps3" folder that points to the **EBOOT.BIN** file of the game in the dev\_hdd0 game folder :&#x20;

<figure><img src="https://i.imgur.com/EGr0uq3.png" alt=""><figcaption><p>m3u file must point to the EBOOT.BIN file in the game folder</p></figcaption></figure>

{% hint style="info" %}
BATGUI tool offers an automatic m3u creation tool. Refer to the [BATGUI ](../../advanced-features/batgui.md)section of the wiki.
{% endhint %}

### Emulator configuration

There are some required settings to be enabled directly in rpcs3:

<figure><img src="https://i.imgur.com/Frjj2kY.png" alt=""><figcaption></figcaption></figure>
