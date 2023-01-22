---
description: Microsoft
---

# Xbox 360

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/5149a33eed46b2af638b06119397d4023b75131f/art/logos/xbox360.svg" alt=""><figcaption></figcaption></figure>

Game Console - Lifespan: 2005 - 2016

{% embed url="https://en.wikipedia.org/wiki/Xbox_360" %}

## Information

| **Emulators**      | <ul><li>xenia-canary</li><li>xenia</li></ul>             |
| ------------------ | -------------------------------------------------------- |
| **File folder**    | :open\_file\_folder: roms \ :open\_file\_folder: xbox360 |
| **File extension** | .iso .xex .xcp .m3u                                      |

## Bios Information

No specific BIOS requirements to play Xbox 360 games on xenia / xenia-canary emulators.

## Controls

Xenia does not offer any manual configuration of controls.

From Retrobat System Options you can select the type of controller to use, select:

* XBOX CONTROLLER for Xbox Controllers post Xbox 360 models
* KEYBOARD for Keyboard
* OTHER for all other type of controllers (NINTENDO, DualShocks, etc.)

## Specific system information

### Adding XBLA (Xbox Live Arcade) games

Xbox360 **XBLA** games (**XB**ox **L**ive **A**rcade) are presented in the form of a succession of several folders, which end in a file that has no extension.

For example for _Banjo Tooie_ game, the filepath is the following:

**\Banjo Tooie\58410955\000D0000\ABB9CAB336175357D09F2D922735D23C62F90DDD**

For Retrobat to be able to launch the game, you must create a **\*.m3u** file to be placed at the root of the `\roms\xbox360` folder.

<figure><img src="https://i.imgur.com/tfzS8Rt.png" alt=""><figcaption><p>Example for Banjo Tooie</p></figcaption></figure>

The content of the .m3u file is the following:

```
\Banjo Tooie\58410955\000D0000\ABB9CAB336175357D09F2D922735D23C62F90DDD
```

{% hint style="info" %}
BATGUI tool offers an automatic m3u creation tool. Refer to the [BATGUI ](../../../../advanced-features/batgui.md)section of the wiki.
{% endhint %}
