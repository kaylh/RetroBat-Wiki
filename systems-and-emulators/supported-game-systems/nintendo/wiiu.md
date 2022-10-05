---
description: Nintendo
---

# WiiU

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/5149a33eed46b2af638b06119397d4023b75131f/art/logos/wiiu.svg" alt=""><figcaption></figcaption></figure>

Game Console - Lifespan: 2012 - 2017

{% embed url="https://en.wikipedia.org/wiki/Wii_U" %}

## Information

| **Emulators**       | <ul><li>cemu</li></ul>                          |   |
| ------------------- | ----------------------------------------------- | - |
| **Games Location**  | :file\_folder: roms \ :open\_file\_folder: wiiu |   |
| **File extensions** | .iso .rpx .wud .wux .m3u                        |   |

## BIOS

There is no BIOS files needed to run games, however, when using .wud or .wux game files, it is necessary to have a keys.txt file in the emulator folder with the right game keys.

The Game keys can be dumped from your WiiU console, see [CEMU guide](https://wiki.cemu.info/wiki/Obtaining\_Keys\_for\_Keys.txt) for more information.

## Controls

| RetroBat key                                                                           | WiiU Key    |
| -------------------------------------------------------------------------------------- | ----------- |
| START                                                                                  | +           |
| SELECT / BACK                                                                          | -           |
| D-PAD                                                                                  | D-PAD       |
| Left Analog Stick                                                                      | Left stick  |
| Right Analog Stick                                                                     | Right stick |
| ![A](<../../../.gitbook/assets/image (1) (2) (1).png>)                                 | B           |
| ![B](<../../../.gitbook/assets/image (4) (1).png>)                                     | A           |
| <img src="../../../.gitbook/assets/image (3) (1) (2).png" alt="" data-size="original"> | X           |
| <img src="../../../.gitbook/assets/image (2) (1) (1).png" alt="" data-size="line">     | Y           |
| LB (L1)                                                                                | L           |
| RB (R1)                                                                                | R           |
| L2                                                                                     | ZL          |
| R2                                                                                     | ZR          |
| L3                                                                                     | Left Thumb  |
| R3                                                                                     | Right Thumb |

### Motion controls

Some Games do require motion control to play in some levels (e.g. Zelda Breath of The Wild contains dungeons which can only be beaten using motion).

There are several options to manage motion control, [CEMU wiki](https://wiki.cemu.info/wiki/Motion\_controls) has great documentation to cover motion control.

DualSense and Switch Pro controllers are tested options.

{% hint style="danger" %}
In construction
{% endhint %}

## Specific system information

### Adding Games

The best way to add WiiU games is to use the format known as "Bootloader" format. This is the format of games dumped from your console with Dumpling tool.

This consists of a game folder with 3 subfolders

<figure><img src="https://i.imgur.com/CIYaICX.png" alt=""><figcaption><p>Example of dumped Zelda game</p></figcaption></figure>

There are 2 options to add these games in Retrobat

#### Install the game in Cemu and use m3u file

This method will simulate the installation of the game in the NAND of the WiiU.

From the Retrobat Game View, open the CEMU emulator



<figure><img src="https://i.imgur.com/rdJUos9.png" alt=""><figcaption><p>File > Install</p></figcaption></figure>

Navigate to the \meta folder of your dumped game directory and install the meta.xml file

<figure><img src="https://i.imgur.com/C1KGhKQ.png" alt=""><figcaption></figcaption></figure>

Wait for the installation to finish and you will see the game added to Cemu

<figure><img src="https://i.imgur.com/rG2IJvR.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://i.imgur.com/9ygBgJP.png" alt=""><figcaption></figcaption></figure>

Right-click on the Game and select **Game directory**

<figure><img src="https://i.imgur.com/6ALGNnR.png" alt=""><figcaption></figcaption></figure>

This will show you the path of the game executable .rpx file

<figure><img src="https://i.imgur.com/EN9JEKf.png" alt=""><figcaption></figcaption></figure>

Exit Cemu and open you `\roms\wiiu` folder and create a `zelda breath of the wild.m3u` file with the following content

`\..\..\emulators\cemu\mlc01\usr\title\`<mark style="color:red;">`<path to the game>`</mark>`\`<mark style="color:red;">`*`</mark>`.rpx`

For example for Zelda Breath of the Wild:

<figure><img src="https://i.imgur.com/DjHV0Gt.png" alt=""><figcaption></figcaption></figure>

The game will now be available in Retrobat for scraping and playing.

#### Place the Game folder in the roms directory

This method will simulate the presence of a WiiU cartridge.&#x20;

Place the game folder in the `\roms\wiiu` folder

<figure><img src="https://i.imgur.com/8BsrI9F.png" alt=""><figcaption></figcaption></figure>

The game will now be available in Retrobat for scraping and playing.

Retrobat will detect the **.rpx** file in the `\code` folder

<figure><img src="https://i.imgur.com/iSQdk4o.png" alt=""><figcaption></figcaption></figure>

The Screenscraper service will recognize U-King as Zelda Breath of the Wild

<figure><img src="https://i.imgur.com/9srVWOF.png" alt=""><figcaption></figcaption></figure>

### Game Updates & DLC

Updates & DLC must be installed in the Cemu emulator directory using the install title, update or DLC option, they come in the same structure as the game itself

Open Cemu and choose **install game title, update or DLC**

<figure><img src="https://i.imgur.com/Y53KGT4.png" alt=""><figcaption><p>Select the install option</p></figcaption></figure>

Navigate to the \meta folder of your dumped DLC or Update directory and install the meta.xml file

<figure><img src="https://i.imgur.com/Y6adbtz.png" alt=""><figcaption><p>search for the meta.xml file in the meta folder</p></figcaption></figure>

Wait until the installation finishes

<figure><img src="https://i.imgur.com/8U7YvAk.png" alt=""><figcaption></figcaption></figure>

You should now see the Update or DLC information in the gamelist

<figure><img src="https://i.imgur.com/OY3g3cd.png" alt=""><figcaption></figcaption></figure>
