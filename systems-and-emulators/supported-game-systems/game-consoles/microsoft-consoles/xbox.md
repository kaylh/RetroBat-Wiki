---
description: Microsoft
---

# Xbox

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/52ff37c9e265587d006945a2ba695b5a962b3a3d/art/logos/xbox.svg" alt=""><figcaption></figcaption></figure>

Game Console - Lifespan: 2001 - 2006

{% embed url="https://en.wikipedia.org/wiki/Xbox_(console)" %}

## Information

<table data-header-hidden><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><strong>Emulators</strong></td><td><ul><li>xemu</li><li>cxbx</li></ul></td><td></td></tr><tr><td><strong>Games Location</strong></td><td><span data-gb-custom-inline data-tag="emoji" data-code="1f4c1">📁</span> roms \ <span data-gb-custom-inline data-tag="emoji" data-code="1f4c2">📂</span> xbox</td><td></td></tr><tr><td><strong>File extensions</strong></td><td>.xbe .iso</td><td></td></tr></tbody></table>

## BIOS

| Bios file         | Folder  | md5                              |
| ----------------- | ------- | -------------------------------- |
| mcpx\_1.0.bin     | `\bios` | d49c52a4102f6df7bcf8d0617ac475ed |
| Complex\_4627.bin | `\bios` | 39cee882148a87f93cb440b99dde3ceb |

## Controls

| RetroBat key                                                                              | Xbox key           |
| ----------------------------------------------------------------------------------------- | ------------------ |
| START                                                                                     | START              |
| SELECT / BACK                                                                             | Back               |
| D-PAD                                                                                     | D-PAD              |
| Left analog stick                                                                         | Left analog stick  |
| Right analog stick                                                                        | Right analog stick |
| ![A](<../../../../.gitbook/assets/image (1) (2) (1).png>)                                 | A                  |
| ![B](<../../../../.gitbook/assets/image (4) (1).png>)                                     | B                  |
| <img src="../../../../.gitbook/assets/image (3) (1) (2).png" alt="" data-size="original"> | Y                  |
| <img src="../../../../.gitbook/assets/image (2) (1) (1).png" alt="" data-size="line">     | X                  |
| L1                                                                                        | L1 (White)         |
| R1                                                                                        | R1 (Black)         |
| L2                                                                                        | LT                 |
| R2                                                                                        | RT                 |
| L3                                                                                        | Left stick button  |
| R3                                                                                        | Right stick button |

## Specific system information

### Game language issue

If your games are all in German or in French, it might be because the eeprom file you are using is not set up in the right language. The emulator will use the language set in the eeprom file.

It is recommended to properly set your language on your original Xbox and extract the BIOS files again.&#x20;

Alternatively, you can edit the eeprom file located in the `/saves/xbox/` directory of your Retrobat folder with a tool available [here (Ernegien's Original Xbox EEPROM editor)](https://github.com/Ernegien/XboxEepromEditor) to change Xbox eeprom settings.
