---
description: Nintendo
---

# Nintendo 64 Disk Drive

<figure><img src="https://i.imgur.com/Oo6wj1I.png" alt=""><figcaption></figcaption></figure>

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

Same as N64

## Specific System Information

### Running Games

There are two types of games on the Nintendo 64DD, full games and game expansions.&#x20;

In order to get n64dd games running successfully, it is required to have two files per game.&#x20;

One of the files is a n64 ROM file and the other is a n64dd .ndd file.&#x20;

Both files need to have the exact same filename and in the case of the n64dd .ndd file, it must have a double extension with the same extension than the n64 rom file, added before its own extension.\


In the case of game expansion like the one in the example below, the n64 game is the actual ROM file for which the n64dd .ndd file is the expansion.&#x20;

For the full games, you also always need two files, so the n64dd .ndd file of the full game and another n64 rom of any title that you just need to rename.\


Example filenames with the expansion "F-Zero X Expansion Kit":

* Rename n64dd .ndd file\
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

The right BIOS can be selected directly in Retrobat Games Options menu, per game.

<figure><img src="https://i.imgur.com/htqkK3Q.png" alt=""><figcaption><p>Advanced System Options / Emulation / BIOS</p></figcaption></figure>
