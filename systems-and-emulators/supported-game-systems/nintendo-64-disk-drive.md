---
description: Nintendo
---

# Nintendo 64 Disk Drive



<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/master/art/logos/n64dd.svg" alt=""><figcaption></figcaption></figure>

Game Console - Lifespan: 1999- 2001

{% embed url="https://en.wikipedia.org/wiki/64DD" %}

## Information

| **Emulators**       | <ul><li>libretro: mupen64plus next</li><li>project64</li></ul> |   |
| ------------------- | -------------------------------------------------------------- | - |
| **Games Location**  | :file\_folder: roms \ :open\_file\_folder: n64dd               |   |
| **File extensions** | .v64 .z64 .n64 .ndd                                            |   |

## BIOS

| <p>IPL_JAP.n64<br>Japan</p>           | <p><strong>location:</strong> \bios\Mupen64plus<br><strong>md5:</strong> <code>8d3d9f294b6e174bc7b1d2fd1c727530</code></p> |   |
| ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | - |
| <p>IPL_USA.n64<br>USA</p>             | <p><strong>location:</strong> \bios\Mupen64plus<br><strong>md5:</strong> <code>37c36e4286d36892a9fc70eafe4104be</code></p> |   |
| <p>IPL_DEV.n64<br>Development Kit</p> | <p><strong>location:</strong> \bios\Mupen64plus<br><strong>md5:</strong> </p>                                              |   |

## Controls

| RetroBat key                                                                        | Nintendo 64 key |
| ----------------------------------------------------------------------------------- | --------------- |
| START                                                                               | START           |
| SELECT / BACK                                                                       |                 |
| D-PAD                                                                               | D-PAD           |
| Analog Stick - Left                                                                 | Analog Stick    |
| Analog Stick - Right                                                                | C-Buttons       |
| ![A](<../../.gitbook/assets/image (1) (2).png>)                                     | A               |
| ![B](<../../.gitbook/assets/image (4) (1).png>)                                     |                 |
| <img src="../../.gitbook/assets/image (3) (1) (2).png" alt="" data-size="original"> |                 |
| <img src="../../.gitbook/assets/image (2) (1) (1).png" alt="" data-size="line">     | B               |
| LB (L1)                                                                             | L               |
| RB (R1)                                                                             | R               |
| LT (L2)                                                                             | Z               |
| RT (R2)                                                                             |                 |
| L-Click (L3)                                                                        |                 |
| R-Click (R3)                                                                        |                 |

## System Features

### Running Games

There are two types of games on the Nintendo 64DD, full games and game expansions. In order to get n64dd games running successfully, it's required to have two roms files per game. One of the files is a n64 rom file and the other is a n64dd rom file. Both roms need to have exact same file name and in the case of the n64dd rom file, it must have a double extension with the same extension than the n64 rom file, added before its own extension.\


In the case of game expansion like the one in the example below, the n64 game is the actual rom file for which the n64dd rom file is the expansion. For the full games, you also always need two files, so the n64dd rom file of the full game and another n64 rom of any title that you just need to rename.\


Example file names with the expansion "F-Zero X Expansion Kit":

* Rename n64dd rom file\
  `F-Zero X - Expansion Kit (Japan).ndd`\
  ``to\
  `F-Zero X - Expansion Kit (Japan).n64.ndd`
* Rename n64 rom file\
  `F-Zero X (Japan).n64`\
  `` to \
  `F-Zero X - Expansion Kit (Japan).n64`
* Run expansion with\
  `F-Zero X - Expansion Kit (Japan).n64`

Example with the full game "SimCity 64":

* Rename `SimCity 64 (Japan).ndd` to `SimCity 64 (Japan).n64.ndd`
* Pick any n64 roms file and rename it `SimCity 64 (Japan).n64`
* Then run `SimCity 64 (Japan).n64` in RetroBat.

### BIOS selection

Althrough only commercialized in Japan, US games are available for the n64dd system, as well as prototypes using a specific "dev" BIOS.

The right BIOS can be selected directly in Retrobat Games Options menu, per game:

<figure><img src="https://i.imgur.com/htqkK3Q.png" alt=""><figcaption><p>Advanced System Options / Emulation / BIOS</p></figcaption></figure>
