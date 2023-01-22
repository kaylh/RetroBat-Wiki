---
description: Sony
---

# PlayStation 2

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/52ff37c9e265587d006945a2ba695b5a962b3a3d/art/logos/ps2.svg" alt=""><figcaption></figcaption></figure>

Game Console - Lifespan: 2000 - 2013

{% embed url="https://en.wikipedia.org/wiki/PlayStation_2" %}

## Information

<table data-header-hidden><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><strong>Emulators</strong></td><td><ul><li>pcsx2-sse4</li><li>pcsx2-avx2</li><li>pcsx2-16</li></ul></td><td></td></tr><tr><td><strong>Games Location</strong></td><td><span data-gb-custom-inline data-tag="emoji" data-code="1f4c1">📁</span> roms \ <span data-gb-custom-inline data-tag="emoji" data-code="1f4c2">📂</span> ps2</td><td></td></tr><tr><td><strong>File extensions</strong></td><td>.iso .cso .bin .mdf .gz .chd</td><td></td></tr></tbody></table>

## Features

| Retroachievements         | NetPlay |
| ------------------------- | ------- |
| YES (with PCSX2 1.7 only) | NO      |

## BIOS

| Bios file      | Folder  | md5                              |
| -------------- | ------- | -------------------------------- |
| SCPH30004R.bin | `\bios` | 28922c703cc7d2cf856f177f2985b3a9 |
| SCPH30004R.MEC | `\bios` | 3faf7c064a4984f53e2ef5e80ed543bc |
| scph39001.bin  | `\bios` | d5ce2c7d119f563ce04bc04dbc3a323e |
| scph39001.MEC  | `\bios` | 3faf7c064a4984f53e2ef5e80ed543bc |
| EROM.BIN       | `\bios` | 9a9e8ed7668e6adfc8f7766c08ab9cd0 |
| rom1.bin       | `\bios` | 44552702b05697a14ccbe2ca22ee7139 |
| ROM2.BIN       | `\bios` | b406d05922dac2eaf3c2e68157b1b468 |

### Other possible non-mandatory BIOS files

| Bios file                           | Folder  |
| ----------------------------------- | ------- |
| SCPH-39004\_BIOS\_V7\_EUR\_160.BIN  | `\bios` |
| SCPH-39001\_BIOS\_V7\_USA\_160.BIN  | `\bios` |
| SCPH-70000\_BIOS\_V12\_JAP\_200.BIN | `\bios` |

### Logic for BIOS search

RetroBat will search BIOS to use with the following logic:

1. Search for existing BIOS in folder `\bios\pcsx2\bios`, use first BIOS found in this folder
2. If no BIOS found, search for BIOS in `\bios` folder, use the first BIOS found in this folder
3. If no BIOS found: force _SCPH30004R.bin_ in emulator configuration file

This means that if you want to use a dedicated BIOS file instead of standard _SCPH30004R.bin_, the best solution is to place the BIOS you want to use in the `\bios\pcsx2\bios` directory.

## Controls

{% hint style="info" %}
The following controllers can be autoconfigured from Retrobat to PCSX2:

* XInput controllers
* Dualshock & DualSense controllers
* Nintendo Switch Pro controller
{% endhint %}

| RetroBat key                                                                              | Playstation 2 key  |
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

<figure><img src="https://i.imgur.com/9sz2VFM.png" alt=""><figcaption></figcaption></figure>

## System Features

### Custom textures

PCSX2 allows to load custom texture packs.

To do so you need to place the custom texture pack in the `\bios\pcsx2\textures` folder in a dedicated directory that has the same code as the game.

<figure><img src="https://i.imgur.com/nOBWsbc.png" alt=""><figcaption></figcaption></figure>

The texture files must be placed in a sub-directory called "replacements":

<figure><img src="https://i.imgur.com/H7dUscl.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
To get the code of the game, you can launch the game a first time directly from the emulator executable located in the `\emulators\pcsx2` folder with the "dump textures" option on, PCSX2 will automatically create the game texture folder in the `\bios\pcsx2\textures` folder.
{% endhint %}

<figure><img src="https://i.imgur.com/ejTZWqt.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://i.imgur.com/WtewREp.png" alt=""><figcaption></figcaption></figure>

Once the texure pack in the right folder, set Retrobat to load custom textures, this is achieved from the **VISUAL RENDERING** menu in the [Advanced System Options](../../../../navigation/view-options.md#advanced-system-options) or in the [Advanced Game Options](../../../../navigation/game-options.md#advanced-game-options) menu :

<figure><img src="https://i.imgur.com/kMCqWFr.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://i.imgur.com/zLj3F55.png" alt=""><figcaption></figcaption></figure>
