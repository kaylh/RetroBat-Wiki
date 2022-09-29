---
description: SEGA
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

## Bios Information

| bios file     | Folder     | md5                              |
| ------------- | ---------- | -------------------------------- |
| dc\_boot.bin  | `\bios\dc` | e10c53c2f8b90bab96ead2d368858623 |
| dc\_flash.bin | `\bios\dc` | 0a93f7940c455905bea6e392dfde92a4 |

## Controls

| Retrobat Button                                 | Dreamcast key |
| ----------------------------------------------- | ------------- |
| START                                           | START         |
| D-PAD                                           | D-PAD         |
| Left analog stick                               | Analog stick  |
| Right analog stick                              |               |
| ![](<../.gitbook/assets/image (2) (1) (1).png>) | X             |
| ![](<../.gitbook/assets/image (1) (2).png>)     | A             |
| ![](<../.gitbook/assets/image (4) (1).png>)     | B             |
| ![](<../.gitbook/assets/image (3) (1).png>)     | Y             |
| L1                                              |               |
| R1                                              |               |
| L2                                              | L1            |
| R2                                              | R1            |
| L3                                              |               |
| R3                                              |               |

## Specific system information

### Multi-disc

You can use a m3u file to automatically load the next disc of multi-disc games.

For example for _Alone In The Dark_, if the ROM contains the following files:

<figure><img src="https://i.imgur.com/LUmmLpf.png" alt=""><figcaption></figcaption></figure>

Create a _Alone in the dark The new nightmare.m3u_ text file with the following content and save it to the /roms/dreamcast folder:

<figure><img src="https://i.imgur.com/9dQJhD9.png" alt=""><figcaption></figcaption></figure>

Retrobat will automatically detect the m3u file and hide the individual .gdi files from the Game List.

### Custom textures

Custom textures can be used with the flycast core.

The texture pack must be placed in the `\bios\dc\textures\` folder:

<figure><img src="https://i.imgur.com/65bX2kT.png" alt=""><figcaption></figcaption></figure>

Then custom textures have to be enabled in Retrobat Dreamcast system configuration or in the game specific configuration:

<figure><img src="https://i.imgur.com/ppkZ9bw.png" alt=""><figcaption><p>Enter the Dreamcast System View Options</p></figcaption></figure>

<figure><img src="https://i.imgur.com/qVMX2Ly.png" alt=""><figcaption><p>Select Visual Rendering</p></figcaption></figure>

<figure><img src="https://i.imgur.com/SbsPMz1.png" alt=""><figcaption><p>Set Custom Textures to YES</p></figcaption></figure>
