---
description: Nintendo
---

# Nintendo 64

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/master/art/logos/n64.svg" alt=""><figcaption></figcaption></figure>

Game Console - Lifespan: 1996 - 2002

{% embed url="https://en.wikipedia.org/wiki/Nintendo_64" %}

## Information

| **Emulators**       | <ul><li>libretro: mupen64plus next</li><li>libretro: parallel</li><li>project64</li></ul> |   |
| ------------------- | ----------------------------------------------------------------------------------------- | - |
| **Games Location**  | :file\_folder: roms \ :open\_file\_folder: n64                                            |   |
| **File extensions** | .v64 .z64 .n64 .wad .zip .7z                                                              |   |

## BIOS

There is no BIOS files needed to run games.

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

### Custom textures

mupen64plus next core allows the use of custom textures.

the texture pack must be placed in the retrobat`bios\Mupen64Plus\cache\` folder if the pack comes as a .hts or .htc file:

<figure><img src="https://i.imgur.com/H878WjR.png" alt=""><figcaption></figcaption></figure>

If it comes as a uncompressed pack (folder with .png files), it must be placed in the `bios\Mupen64Plus\hires_texture\` folder:

<figure><img src="https://i.imgur.com/1sqG9H4.png" alt=""><figcaption></figcaption></figure>

For htc or hts files, the file name must be "GAMEID"\_\_HIRESTEXTURES.hts or .htc (for example : MARIOKART64\_HIRESTEXTURES.htc)&#x20;

For uncompressed folder, the folder name must be similar to the gameID (for example  MARIOKART64).

Once the texture pack in the right folder, enable Custom Textures option in Retrobat:

<figure><img src="https://i.imgur.com/jBt3sjA.png" alt=""><figcaption><p>Advanced System Options (can also be done per game)</p></figcaption></figure>

<figure><img src="https://i.imgur.com/hzikBUa.png" alt=""><figcaption><p>Visual Rendering</p></figcaption></figure>

<figure><img src="https://i.imgur.com/TXJ3fti.png" alt=""><figcaption></figcaption></figure>

RICE if the texture pack is compressed (htc or hts).&#x20;

CACHE if the texture pack is uncompressed (folder).

{% hint style="info" %}
At first launch of a game with an uncompressed texture pack, Mupen64Plus-next will generate a .hts file in `CACHE` folder, upon next launch of the game, it is possible to use RICE instead of CACHE.
{% endhint %}
