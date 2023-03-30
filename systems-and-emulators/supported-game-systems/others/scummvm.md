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

| BIOS file         | Folder                | md5                              |
| ----------------- | --------------------- | -------------------------------- |
| MT32\_CONTROL.ROM | `\bios\scummvm\extra` | 5626206284b22c2734f3e9efefcd2675 |
| MT32\_PCM.ROM     | `\bios\scummvm\extra` | 89e42e386e82e0cacb4a2704a03706ca |

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

### Running a specific version of a game with dedicated per-game options

Some games have been issued on multiple platforms, SCUMMVM is able to run most of these versions.

If you own multiple versions of the same game and want to be able to select the version to run, you will first need to add the games to SCUMMVM directly within the emulator.

To do so, proceed as follows.

* Open SCUMMVM and select "add games":

<figure><img src="https://i.imgur.com/iJoG99n.png" alt=""><figcaption></figcaption></figure>

Locate your game folder.

* Pick the version of the game to be added (if multiple versions exist in your game file):

<figure><img src="https://i.imgur.com/AOzAJp2.png" alt=""><figcaption></figcaption></figure>

* Define the game short ID and the options to enable when running this game

<figure><img src="https://i.imgur.com/SSQCrt7.png" alt=""><figcaption></figcaption></figure>

Click OK once finished

The game is now added to SCUMMVM:

<figure><img src="https://i.imgur.com/Ok0JkMy.png" alt=""><figcaption></figcaption></figure>

* Create a dedicated .scummvm file to run this specific version of the game:

<figure><img src="https://i.imgur.com/nCNTake.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://i.imgur.com/5DiPExS.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
The name inside the .scummvm file must match the short ID specified when adding the game in the emulator.
{% endhint %}

* In RetroBat, both versions will now be available

<figure><img src="https://i.imgur.com/OTcJf0h.png" alt=""><figcaption></figcaption></figure>

Note that you can check all installed games and their short-ID in the scummvm.ini file, this file is located in:

* \emulators\scummvm folder (for SCUMMVM standalone)
* \bios folder for libretro:scummvm

<figure><img src="https://i.imgur.com/YUsciw5.png" alt=""><figcaption></figcaption></figure>
