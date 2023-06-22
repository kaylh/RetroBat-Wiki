# Visual Pinball

<div align="left">

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/52ff37c9e265587d006945a2ba695b5a962b3a3d/art/logos/vpinball.svg" alt=""><figcaption></figcaption></figure>

</div>

Pinball Simulation Software

{% embed url="https://en.wikipedia.org/wiki/Visual_Pinball" %}

{% embed url="https://www.vpforums.org/" %}

## Information

<table data-header-hidden><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><strong>Emulators</strong></td><td><ul><li>vpinball</li></ul></td><td></td></tr><tr><td><strong>Games Location</strong></td><td><span data-gb-custom-inline data-tag="emoji" data-code="1f4c2">📂</span>roms \ <span data-gb-custom-inline data-tag="emoji" data-code="1f4c2">📂</span> vpinball</td><td></td></tr><tr><td><strong>File extensions</strong></td><td>.vpx .7z .zip .rar</td><td></td></tr></tbody></table>

## BIOS

No BIOS required.

## Controls

| Gamepad                                                                                | Keyboard   | Visual Pinball key |
| -------------------------------------------------------------------------------------- | ---------- | ------------------ |
| START                                                                                  | 1          | START game         |
| SELECT                                                                                 | 5          | Insert COIN        |
| D-PAD - UP                                                                             | SPACE      | Forward Nudge      |
| D-PAD - DOWN                                                                           | TAB        |                    |
| D-PAD - LEFT                                                                           | Z          | Left Nudge         |
| D-PAD - RIGHT                                                                          | SLASH (/)  | Right Nudge        |
| Left Analog stick                                                                      |            |                    |
| Right Analog stick                                                                     |            |                    |
| ![A](<../../../.gitbook/assets/image (1) (2) (1).png>)                                 | ENTER      | Plunger            |
| ![B](<../../../.gitbook/assets/image (4) (1).png>)                                     |            |                    |
| <img src="../../../.gitbook/assets/image (3) (1) (2).png" alt="" data-size="original"> | PAUSE      |                    |
| <img src="../../../.gitbook/assets/image (2) (1) (1).png" alt="" data-size="line">     | RIGHTBRACE |                    |
| L1                                                                                     | SHIFT      | Left Flipper       |
| R1                                                                                     | RIGHTSHIFT | Right Flipper      |
| L2                                                                                     |            |                    |
| R2                                                                                     |            |                    |
| L3                                                                                     |            |                    |
| R3                                                                                     |            |                    |

## Specific system information

### Tables

Visual Pinball is a complex system, each table can require different type of files listed here:

* .vpx table file
* .directb2s (backglass)
* .UltraDMD folder (dot matrix display)
* rom files (original pinball machine ROM)
* music files

Some tables require only the .vpx file, but most require at least the directb2s and rom file in addition.

#### VPX files

VPX file needs to be placed in the `\roms\vpinball\` folder.

#### directb2s files

directb2s file needs to be placed in the `\roms\vpinball\` folder, with the exact same name as the vpx file:

<div align="left">

<figure><img src="https://i.imgur.com/muDyjzI.png" alt=""><figcaption></figcaption></figure>

</div>

#### UltraDMD folders

UltraDMD folders need to be placed in the `\roms\vpinball\` folder, do not change the name of the folder from the one you got with your table:

<div align="left">

<figure><img src="https://i.imgur.com/LIDc6B0.png" alt=""><figcaption></figcaption></figure>

</div>

#### ROM files

Tables that are run with the VPinMAME version of the program require an additional .zip file called ROM.

These files need to be placed in the `\emulators\vpinball\VPinMAME\roms` folder :&#x20;

<div align="left">

<figure><img src="https://i.imgur.com/TpXP6dI.png" alt=""><figcaption></figcaption></figure>

</div>

To know what the rom name should be, run the **PinMAME32.exe** file located in the `\emulators\vpinball\VPinMAME` folder and check the rom file associated with your table:

<div align="left">

<figure><img src="https://i.imgur.com/FMuBSQ3.png" alt=""><figcaption></figcaption></figure>

</div>

#### Music files

Additional mp3 or ogg music files are required by some tables, they must be placed in the `\emulators\vpinball\Music` folder:

<div align="left">

<figure><img src="https://i.imgur.com/V3nna49.png" alt=""><figcaption></figcaption></figure>

</div>
