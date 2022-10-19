# Visual Pinball

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/52ff37c9e265587d006945a2ba695b5a962b3a3d/art/logos/vpinball.svg" alt=""><figcaption></figcaption></figure>

Pinball Simulation Software

{% embed url="https://en.wikipedia.org/wiki/Visual_Pinball" %}

{% embed url="https://www.vpforums.org/" %}

## Information

| **Emulators**       | <ul><li>vpinball</li></ul>                               |   |
| ------------------- | -------------------------------------------------------- | - |
| **Games Location**  | :open\_file\_folder:roms \ :open\_file\_folder: vpinball |   |
| **File extensions** | .vpx .7z .zip .rar                                       |   |

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
* .UltraDMD folder
* rom files
* music files

Some tables require only the .vpx file, others might require more information.

#### VPX files

VPX file needs to be placed in the `\roms\vpinball\` folder.

#### directb2s files

directb2s file needs to be placed in the `\roms\vpinball\` folder, with the exact same name as the vpx file:

<figure><img src="https://i.imgur.com/muDyjzI.png" alt=""><figcaption></figcaption></figure>

#### UltraDMD folders

UltraDMD folders need to be placed in the `\roms\vpinball\` folder, do not change the name of the folder from the one you got with your table:

<figure><img src="https://i.imgur.com/LIDc6B0.png" alt=""><figcaption></figcaption></figure>

#### ROM files

Tables that are run with the VPinMAME version of the program require an additional .zip file called ROM.

These files need to be placed in the `\emulators\vpinball\VPinMAME\roms` folder :&#x20;

<figure><img src="https://i.imgur.com/TpXP6dI.png" alt=""><figcaption></figcaption></figure>

To know what the rom name should be, run the **PinMAME32.exe** file located in the `\emulators\vpinball\VPinMAME` folder and check the rom file associated with your table:

<figure><img src="https://i.imgur.com/FMuBSQ3.png" alt=""><figcaption></figcaption></figure>

#### Music files

Additional mp3 or ogg music files are required by some tables, they must be placed in the `\emulators\vpinball\Music` folder:

<figure><img src="https://i.imgur.com/V3nna49.png" alt=""><figcaption></figcaption></figure>
