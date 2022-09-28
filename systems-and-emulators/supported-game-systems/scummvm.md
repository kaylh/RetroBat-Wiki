---
description: ScummVM Team
---

# ScummVM

![](<../../.gitbook/assets/image (1).png>)

Emulator - Creation year: 2001

{% embed url="https://en.wikipedia.org/wiki/ScummVM" %}

## Information

| **Emulators**      | <ul><li>Libretro: scummvm</li><li>scummvm</li></ul>      |
| ------------------ | -------------------------------------------------------- |
| **File folder**    | :open\_file\_folder: roms \ :open\_file\_folder: scummvm |
| **File extension** | .scummvm .7z .zip .rar .squashfs                         |

## Bios Information

No specific BIOS is required to play ScummVM games.

## Controls

Most of the games are point-and-click games designed to be played with a mouse. If you don't have a mouse, the left analog stick can be used too.

Manual controls can be configured by adding a [pad2key ](../../advanced-features/pad2key.md)profile for the game.

## Specific system information

### Adding games

Scummvm games must be in separate folders, in the `\roms\scummvm` folder.

<figure><img src="https://i.imgur.com/qfDZ5Np.png" alt=""><figcaption></figcaption></figure>

In each games folder, create a .txt file with the name of the game, for example **Full Throttle.txt** for Full Throttle.

<figure><img src="https://i.imgur.com/zNotr1I.png" alt=""><figcaption></figcaption></figure>

In the .txt file, enter the ScummVM **game shortname**, refer to [https://www.scummvm.org/compatibility/](https://www.scummvm.org/compatibility/) to get the correct shortname.

Finally, rename the \*._txt_ files into \*._scummvm_ file, for example:\
\
Full Throttle.**txt**  **==>** Full Throttle.**scummvm**
