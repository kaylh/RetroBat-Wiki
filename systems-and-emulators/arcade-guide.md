# Arcade Guide

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/52ff37c9e265587d006945a2ba695b5a962b3a3d/art/logos/arcade.svg" alt=""><figcaption></figcaption></figure>

## Introduction

Arcade emulators can be split in 2 categories:

* Multi-Arcade-Machine Emulators
* Single-Arcade-Board Emulators

There are a huge variety of Arcade Machines, this is why Arcade Emulation is complex.



In this guide, we will focus on 2 families of emulators, and give you the main keys to understand Arcade Emulation, we will group the Emulators in the 2 families described above.

## Multi Machine Emulators

There are two families of multi-system arcade emulators available: FinalBurn and MAME.&#x20;

These emulators are available in multiple versions to allow users to best match a core/emulator with their games.&#x20;

### Available Multi-Machine Arcade emulators in Retrobat

| Emulator/core            | ROMs folder   | ROM set version |
| ------------------------ | ------------- | --------------- |
| libretro: mame (current) | `\roms\mame`  | 0.251           |
| libretro: mame2016       | `\roms\mame`  | 0.174           |
| libretro: mame2014       | `\roms\mame`  | 0.159           |
| libretro: mame2010       | `\roms\mame`  | 0.139           |
| Libretro: mame2003\_plus | `\roms\mame`  | 0.78plus        |
| Libretro: mame2003       | `\roms\mame`  | 0.78            |
| Libretro: mame2000       | `\roms\mame`  | 0.37b5          |
| mame (standalone)        | `\roms\mame`  | 0.253           |
| Libretro: fbneo          | `\roms\fbneo` | 1.0.0.3         |
| Libretro: fbalpha        | `\roms\fbneo` | 0.2.97.44       |
| Libretro: fbalpha2012    | `\roms\fbneo` | 0.2.97.29       |

MAME is the usual emulator used for common Arcade games (the likes of Pac-Man, Asteroids, etc.)

FBNeo is specialized in Fighting Games and Beat-them-up.



## Single Board Emulators

| Arcade Machine(s)          | ROMs folder         | Emulator         |
| -------------------------- | ------------------- | ---------------- |
| FMV LaserDisc Arcade Games | `\roms\daphne`      | DAPHNE / Hypseus |
| ATOMISWAVE                 | `\roms\atomiswave`  | FLYCAST / Demul  |
| GAELCO                     | `\roms\gaelco`      | Demul            |
| SEGA MODEL 2               | `\roms\model2`      | m2emulator       |
| SEGA MODEL 3               | `\roms\model3`      | Supermodel       |
| SEGA NAOMI                 | `\roms\naomi`       | FLYCAST / Demul  |
| SEGA NAOMI 2               | `\roms\naomi2`      | FLYCAST / Demul  |
| HIKARU                     | `\roms\hikaru`      | Demul            |
| TRIFORCE                   | `\roms\triforce`    | DOLPHIN          |
| CHIHIRO                    | `\roms\chihiro`     | CXBX-RELOADED    |
| PC-BASED ARCADE            | `\roms\teknoparrot` | TEKNOPARROT      |



## ROMs

### Terminology

* **ROM, ROM set, and romset**: Arcade games are packaged as zip files, most of which are composed of more than one individual 'ROM' file. \
  That is why some resources refer to an individual arcade game as a ROM while other resources refer to an individual game as a ROM set or romset.\

* **ROM version or romset version**: Each version of an arcade emulator must be used with ROMs that have the same exact version number. \
  For example, MAME 0.37b5 ROMs are required by the MAME 2000 emulator, but will not work correctly with the MAME 2010 emulator, which requires MAME 0.139 ROMs.\


### ROM set types

Arcade ROMs can be formatted four ways:

* **Full Non-merged**: All romsets can be used standalone because each zip contains all the files needed to run that game, including any ROMs from 'parent' ROM sets and BIOS sets.\

* **Non-merged ROM**: All romsets can be used standalone because each zip contains all the files needed to run that game, including any files from 'parent romsets'. \
  The only exceptions are games which use BIOS ROMs, which are formatted as 'Split' and must be kept in the same folder as the game romset which uses it.\

* **Split**: Some romsets that are considered clones, translations, or bootlegs also require a "parent" romset to run. In some cases the parent is not the most popular or best working version of the game, however. \
  For example, in a Split set `pacman.zip` (a clone), will not work without `puckman.zip` (its parent).\

* **Merged**: Clones are merged into the parent romset zip, meaning that more than one game is stored per file. \


{% hint style="warning" %}
Merged rom sets are not supported, as only the main game will be seen in RetroBat and launched by Mame core.&#x20;

We recommend the use of Non-merged rom sets.
{% endhint %}

{% hint style="info" %}
Do not rename the zipped ROM files. Scrapers will recognize the games with the .zip filename and match them with the right game.
{% endhint %}

## Additional files

### Samples

Some games need extra samples files to work, they should be placed in the following folders:

* For fbneo: `\bios\fbneo\samples`
* For mame2003: `\bios\mame2003\samples`
* For mame2003plus: `\bios\mame2003-plus\samples`
* For mame2010: `\bios\mame2010\samples`
* For the current mame and standalone mame: `\bios\mame\samples`

### CHD or IMG files

Some arcade games can use extra files (originally these were physically stored on a disc) called CHD (sometimes IMG).&#x20;

The CHD folder must be placed in the rom folder and must have the same name as the game's ZIP file.&#x20;

For example, for `kinst.zip` the game will be looking for `kinst\kinst.chd`.

<figure><img src="https://i.imgur.com/xl9iImN.png" alt=""><figcaption></figcaption></figure>

## Links and references

{% hint style="info" %}
**Credits**

A big chunk of information from this page has been sourced from libretro documentation:

[https://docs.libretro.com/guides/arcade-getting-started/](https://docs.libretro.com/guides/arcade-getting-started/)
{% endhint %}
