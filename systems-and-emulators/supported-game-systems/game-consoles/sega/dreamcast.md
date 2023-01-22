---
description: Sega
---

# Dreamcast

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/5149a33eed46b2af638b06119397d4023b75131f/art/logos/dreamcast.svg" alt=""><figcaption></figcaption></figure>

Game Console - Lifespan: 1998 - 2001

{% embed url="https://en.wikipedia.org/wiki/Dreamcast" %}

## Information

| **Emulators**      | <ul><li>Libretro: flycast</li><li>Libretro: redream</li><li>redream</li><li>demul</li></ul> |
| ------------------ | ------------------------------------------------------------------------------------------- |
| **File folder**    | :open\_file\_folder: roms \ :open\_file\_folder: dreamcast                                  |
| **File extension** | .mds .mdf .cue .cdi .gdi .chd .m3u                                                          |

## Features

| Retroachievements | NetPlay                      |
| ----------------- | ---------------------------- |
| YES               | YES (libretro: redream only) |

## Bios Information

| bios file     | Folder     | md5                                 |
| ------------- | ---------- | ----------------------------------- |
| dc\_boot.bin  | `\bios\dc` | e10c53c2f8b90bab96ead2d368858623    |
| dc\_flash.bin | `\bios\dc` | 0a93f7940c455905bea6e392dfde92a4    |
| dc.zip        | `\bios\dc` | See below (required for demul only) |

#### Content of BIOS file

```
dc.zip
- 1_01d_01.bin "E10C53C2F8B90BAB96EAD2D368858623"
- 1_01d_02.bin "A5C6A00818F97C5E3E91569EE22416DC"
- 1_004_01.bin "37C921EB47532CAE8FB70E5D987CE91C"
- 1_011_01.bin "EAFCA1EED2D7F76C487E940597C2A786"
```

## Controls

| Retrobat Button                                          | Dreamcast key |
| -------------------------------------------------------- | ------------- |
| START                                                    | START         |
| D-PAD                                                    | D-PAD         |
| Left analog stick                                        | Analog stick  |
| Right analog stick                                       |               |
| ![](<../../../../.gitbook/assets/image (2) (1) (1).png>) | X             |
| ![](<../../../../.gitbook/assets/image (1) (2) (1).png>) | A             |
| ![](<../../../../.gitbook/assets/image (4) (1).png>)     | B             |
| ![](<../../../../.gitbook/assets/image (3) (1) (2).png>) | Y             |
| L1                                                       |               |
| R1                                                       |               |
| L2                                                       | L1            |
| R2                                                       | R1            |
| L3                                                       |               |
| R3                                                       |               |

<figure><img src="https://i.imgur.com/g71xmgZ.png" alt=""><figcaption></figcaption></figure>

## Specific system information

### Multi-disc

You can use a m3u file to manage multi-disc games.

For example for _Alone In The Dark_, if the ROM contains the following files:

<figure><img src="https://i.imgur.com/LUmmLpf.png" alt=""><figcaption></figcaption></figure>

create a `Alone in the dark The new nightmare.m3u` text file with the following content and save it to the /roms/dreamcast folder:

<figure><img src="https://i.imgur.com/9dQJhD9.png" alt=""><figcaption></figcaption></figure>

Retrobat will automatically detect the m3u file and hide the individual .gdi files from the Game List.

### Custom textures

Custom textures can be used with the flycast core.

The texture pack must be placed in the `\bios\dc\textures\` folder:

<figure><img src="https://i.imgur.com/65bX2kT.png" alt=""><figcaption></figcaption></figure>

Then, enable **CUSTOM TEXTURES** in **ADVANCED SYSTEM OPTIONS** or in **ADVANCED GAME OPTIONS**.

<figure><img src="https://i.imgur.com/ppkZ9bw.png" alt=""><figcaption><p>Enter the Dreamcast System View Options</p></figcaption></figure>

<figure><img src="https://i.imgur.com/qVMX2Ly.png" alt=""><figcaption><p>Select Visual Rendering</p></figcaption></figure>

<figure><img src="https://i.imgur.com/SbsPMz1.png" alt=""><figcaption><p>Set Custom Textures to YES</p></figcaption></figure>
