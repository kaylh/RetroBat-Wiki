---
description: ScummVM Team
---

# ScummVM

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/5149a33eed46b2af638b06119397d4023b75131f/art/logos/scummvm.svg" alt=""><figcaption></figcaption></figure>

Emulator - Creation year: 2001

{% embed url="https://en.wikipedia.org/wiki/ScummVM" %}

## Information

| **Emulators**      | <ul><li>Libretro: scummvm</li><li>scummvm</li></ul>      |
| ------------------ | -------------------------------------------------------- |
| **File folder**    | :open\_file\_folder: roms \ :open\_file\_folder: scummvm |
| **File extension** | .scummvm .7z .zip .rar .squashfs                         |

## Features

| Retroachievements | NetPlay |
| ----------------- | ------- |
| NO                | NO      |

## BIOS

No specific BIOS is required to play ScummVM games.

## Controls

Most of the games are point-and-click games designed to be played with a mouse. If you don't have a mouse, the left analog stick can be used too.

Manual controls can be configured by adding a [pad2key ](../../../controllers/pad2key.md)profile for the game.

## System Features

### Adding games

Scummvm games must be in separate folders, in the `\roms\scummvm` folder.

<figure><img src="https://i.imgur.com/qfDZ5Np.png" alt=""><figcaption></figcaption></figure>

In each games folder, create a .txt file with the name of the game, for example **Full Throttle.txt** for Full Throttle.

<figure><img src="https://i.imgur.com/zNotr1I.png" alt=""><figcaption></figcaption></figure>

In the .txt file, enter the ScummVM **game shortname**, refer to [https://www.scummvm.org/compatibility/](https://www.scummvm.org/compatibility/) to get the correct shortname.

{% hint style="info" %}
When using the standalone emulator, you might need for some games to put the full shortname with the game engine.

For example for "Indiana Jones and The Fate Of Atlantis", you will need to write `scumm:atlantis` in the atlantis.scummvm file, as there is a second game `cryomni3d:atlantis`.
{% endhint %}

Finally, rename the \*._txt_ files into \*._scummvm_ file, for example:\
\
Full Throttle.**txt**  **==>** Full Throttle.**scummvm**

### Accessing ScummVM menu (libretro core)

When the option "Game Focus" is enabled, use CTRL + F5 to access ScummVM menu, as usual RetroArch hotkeys are disabled.
