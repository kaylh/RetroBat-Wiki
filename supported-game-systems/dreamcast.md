---
description: SEGA
---

# Dreamcast

![](<../.gitbook/assets/image (11).png>)

Type: Game Console

Lifespan: 1998 - 2001

Wikipedia page : [https://en.wikipedia.org/wiki/Dreamcast](https://en.wikipedia.org/wiki/Dreamcast)

## Information

**Emulators / Libretro Cores:**

* Libretro: flycast
* Libretro: redream
* redream
* demul

**ROMs folder:**

* `\roms\dreamcast`

**ROMs formats:**

.mds .mdf .cue .cdi .gdi .chd .m3u

## Bios Information

| bios file     | Folder     | md5                              |
| ------------- | ---------- | -------------------------------- |
| dc\_boot.bin  | `\bios\dc` | e10c53c2f8b90bab96ead2d368858623 |
| dc\_flash.bin | `\bios\dc` | 0a93f7940c455905bea6e392dfde92a4 |

## Controls

| Retrobat Button                             | Dreamcast key |
| ------------------------------------------- | ------------- |
| START                                       | START         |
| Left analog stick                           | Analog stick  |
| D-PAD                                       | D-PAD         |
| ![](<../.gitbook/assets/image (2).png>)     | X             |
| ![](<../.gitbook/assets/image (1) (2).png>) | A             |
| ![](<../.gitbook/assets/image (4).png>)     | B             |
| ![](<../.gitbook/assets/image (3) (1).png>) | Y             |
| L1                                          | L1            |
| R1                                          | R1            |

## Specific system information

### Multi-disc

You can use a m3u file to automatically load the next disc of multi-disc games.

For example for ShenMue, if the ROM contains the following files:

<figure><img src="https://i.imgur.com/dtC65cI.png" alt=""><figcaption></figcaption></figure>

Create a "shenmue.m3u" text file with the following content and save it to the /roms/dreamcast folder:

<figure><img src="https://i.imgur.com/HxcDWc4.png" alt=""><figcaption></figcaption></figure>

Retrobat will automatically detect the m3u file and hide the individual .gdi files from the Game List.

### HD textures

Custom HD textures can be used with the flycast core.

The texture pack must be placed in the "/bios/dc/textures/" folder:

<figure><img src="https://i.imgur.com/65bX2kT.png" alt=""><figcaption></figcaption></figure>

Then custom textures have to be enabled in Retrobat Dreamcast system configuration or in the game specific configuration:

<figure><img src="https://i.imgur.com/ppkZ9bw.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://i.imgur.com/qVMX2Ly.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://i.imgur.com/SbsPMz1.png" alt=""><figcaption></figcaption></figure>
