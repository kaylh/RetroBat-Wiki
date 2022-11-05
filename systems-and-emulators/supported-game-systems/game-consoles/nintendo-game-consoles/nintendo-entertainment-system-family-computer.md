---
description: Nintendo
---

# Nintendo Entertainment System - Family Computer

<table data-header-hidden><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><p></p><p><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/master/art/logos/nes.svg" alt="" data-size="original"></p></td><td><p></p><p><img src="https://upload.wikimedia.org/wikipedia/commons/7/7d/Family_Computer_logo.svg" alt="" data-size="original"></p></td><td></td></tr></tbody></table>

Game Console - Lifespan: 1983 - 2003

{% embed url="https://en.wikipedia.org/wiki/Nintendo_Entertainment_System" %}

## Information

<table data-header-hidden><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><strong>Emulators</strong></td><td><ul><li>libretro: fceumm</li><li>libretro: nestopia</li><li>libretro: mesen</li><li>mednafen</li><li>mesen</li></ul></td><td></td></tr><tr><td><strong>Games Location</strong></td><td><span data-gb-custom-inline data-tag="emoji" data-code="1f4c1">📁</span> roms \ <span data-gb-custom-inline data-tag="emoji" data-code="1f4c2">📂</span> nes</td><td></td></tr><tr><td><strong>File extensions</strong></td><td>.fds .nes .wad .zip .7z</td><td></td></tr></tbody></table>

## Features

| Retroachievements | NetPlay |
| ----------------- | ------- |
| YES               | YES     |

## BIOS

There is no BIOS files needed to run games.

## Controls

| RetroBat key                                                                              | NES key |
| ----------------------------------------------------------------------------------------- | ------- |
| START                                                                                     | START   |
| SELECT / BACK                                                                             | SELECT  |
| D-PAD                                                                                     | D-PAD   |
| Left analog stick                                                                         | D-PAD   |
| Right analog stick                                                                        |         |
| ![A](<../../../../.gitbook/assets/image (1) (2) (1).png>)                                 | B       |
| ![B](<../../../../.gitbook/assets/image (4) (1).png>)                                     | A       |
| <img src="../../../../.gitbook/assets/image (3) (1) (2).png" alt="" data-size="original"> | A       |
| <img src="../../../../.gitbook/assets/image (2) (1) (1).png" alt="" data-size="line">     | B       |

<figure><img src="https://i.imgur.com/ulQC9m2.png" alt=""><figcaption></figcaption></figure>

## Specific System Information

### Custom textures



The libretro:mesen core allows to load custom texture packs.

To do so you need to place the custom texture pack in the `\bios\HdPacks` folder in a dedicated directory that has the same name than the game file, for example if your game name is `Mega Man (USA).nes`, the texture pack folder must be named `Mega Man (USA)`

<figure><img src="https://i.imgur.com/0t1gw0h.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
It is very important that the sha1 hash of your game file matches the sha1 located in the "hires.txt" file from the texture pack folder:
{% endhint %}

<figure><img src="https://i.imgur.com/KAQVQlV.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://i.imgur.com/b04EdoH.png" alt=""><figcaption></figcaption></figure>

Then, select the **Libretro: mesen** emulator for the game or the system:

<figure><img src="https://i.imgur.com/QUAN6n2.png" alt=""><figcaption></figcaption></figure>

Next you need to enable the Custom Textures options in the Advanced Settings > Visual Rendering section of the Game Options or Advanced Systems Options:

<figure><img src="https://i.imgur.com/Un77eUl.png" alt=""><figcaption></figcaption></figure>
