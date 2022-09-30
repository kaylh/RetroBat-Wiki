---
description: Nintendo
---

# Wii

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/5149a33eed46b2af638b06119397d4023b75131f/art/logos/wii.svg" alt=""><figcaption></figcaption></figure>

Game Console - Lifespan: 2006 - 2017

{% embed url="https://en.wikipedia.org/wiki/Wii" %}

## Information

| **Emulators**       | <ul><li>dolphin</li><li>libretro: dolphin</li></ul> |   |
| ------------------- | --------------------------------------------------- | - |
| **Games Location**  | :file\_folder: roms \ :open\_file\_folder: wii      |   |
| **File extensions** | .gcz .iso .ciso .wbfs .wad .rvz .wia                |   |

## BIOS

There is no BIOS files needed to run games.

## Controls

### REAL WIIMOTE

For best experience, you can use real **Wiimotes** with a **Mayflash DolphinBar** (in mode 4) and activate the **REAL WIIMOTES** setting in Retrobat from the [System View Options](../../navigation/view-options.md) or from the [Game Options](../../navigation/game-options.md)

<figure><img src="https://i.imgur.com/0jC9b8z.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://i.imgur.com/FFWtrsV.png" alt=""><figcaption><p>Wiimote type : select REAL</p></figcaption></figure>

### EMULATED WIIMOTE

If you do not own a real wiimote and need to emulate the wiimote, Retrobat offers multiple options to correctly emulate it and use all its features with a gamepad when enabling the option **EMULATED WIIMOTE**

<figure><img src="https://i.imgur.com/mGwoc25.png" alt=""><figcaption></figcaption></figure>

The mapping hereunder is the default mapping for the Wii

| RetroBat key                                                                        | Emulated Wiimote key     |
| ----------------------------------------------------------------------------------- | ------------------------ |
| START                                                                               |                          |
| SELECT / BACK                                                                       | Home                     |
| D-PAD                                                                               | D-PAD                    |
| Left Analog Stick                                                                   | IR control (wii pointer) |
| Right Analog Stick                                                                  | Tilt control             |
| ![A](<../../.gitbook/assets/image (1) (2) (1).png>)                                 | B                        |
| ![B](<../../.gitbook/assets/image (4) (1).png>)                                     | A                        |
| <img src="../../.gitbook/assets/image (3) (1) (2).png" alt="" data-size="original"> | 2                        |
| <img src="../../.gitbook/assets/image (2) (1) (1).png" alt="" data-size="line">     | 1                        |
| LB (L1)                                                                             | -                        |
| RB (R1)                                                                             | +                        |

This mapping is kind of crappy and will not suit all games, this is why there are some built-in features, that are based on ROM naming, that will allow changing the mapping to suit each available game layout.

#### .side.

Adding .side. in your filename is the default layout that should be used for games requiring you to hold the wiimotes sideways, this can be useful for games such as New Super Mario Bros Wii.

If you name you ROM `New Super Mario Bros WII.side.iso` the following mapping changes will occur

| Retrobat Key                                                                        | Wiimote Key |
| ----------------------------------------------------------------------------------- | ----------- |
| ![A](<../../.gitbook/assets/image (1) (2) (1).png>)                                 | 1           |
| ![B](<../../.gitbook/assets/image (4) (1).png>)                                     | 2           |
| <img src="../../.gitbook/assets/image (3) (1) (2).png" alt="" data-size="original"> | B           |
| <img src="../../.gitbook/assets/image (2) (1) (1).png" alt="" data-size="line">     | A           |

#### .cc.

The .cc. flag in the rom name will enable the classic controller mapping. For games supporting the Classic Controller, this might be the best option.

(e.g. `Super Smash Bros WII.cc.iso`)

The is the Classic Controller mapping

| Retrobat key                                                                        | Classic Controller key |
| ----------------------------------------------------------------------------------- | ---------------------- |
| START                                                                               | +                      |
| SELECT                                                                              | -                      |
| D-PAD                                                                               | D-PAD                  |
| Left analog stick                                                                   | Left stick             |
| Right analog stick                                                                  | Right stick            |
| ![A](<../../.gitbook/assets/image (1) (2) (1).png>)                                 | B                      |
| ![B](<../../.gitbook/assets/image (4) (1).png>)                                     | A                      |
| <img src="../../.gitbook/assets/image (3) (1) (2).png" alt="" data-size="original"> | X                      |
| <img src="../../.gitbook/assets/image (2) (1) (1).png" alt="" data-size="line">     | Y                      |
| L1                                                                                  | L                      |
| R1                                                                                  | R                      |
| L2                                                                                  | ZL                     |
| R2                                                                                  | ZR                     |

#### Other .xx. options

Enables the controller to operate with the left stick representing the function represented by first character and the right stick the function represented by the second character.&#x20;

The options are as follows:

| Option | Function | Explanation                                                                                     |
| ------ | -------- | ----------------------------------------------------------------------------------------------- |
| i      | Infrared | The selected stick will operate as the wiimote pointer                                          |
| s      | Swing    | The selected stick will be used for Swing movements                                             |
| t      | Tilt     | The selected stick will be used for Tilt movements                                              |
| n      | Nunchuk  | <p>The selected stick will act as the joystick on the nunchuk </p><p>and L2 = C and :R2 = Z</p> |

For example if your game requires a nunchuk (e.g. Super Mario Galaxy), you can name your ROM

`super mario galaxy.in.iso` if you want to use the left stick to control the pointer and right stick for nunchuk joystick

`super mario galaxy.ni.iso` if you want to use the left stick as the nunchuk joystick and the right stick to control the pointer

## System Features

### Custom Textures

The procedure for custom textures for Wii is similar to the one for Gamecube, refer to the [Gamecube section of the wiki](gamecube.md#custom-textures).&#x20;

