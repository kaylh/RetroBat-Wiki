---
description: MAME Team
---

# MAME

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/52ff37c9e265587d006945a2ba695b5a962b3a3d/art/logos/mame.svg" alt=""><figcaption></figcaption></figure>

Multi-Arcade Emulator - Release year: 1997

{% embed url="https://en.wikipedia.org/wiki/MAME" %}

## Information

| **Emulators**      | <ul><li>Libretro: mame</li><li>Libretro: mame2016</li><li>Libretro: mame2010</li><li>Libretro: mame2003_plus</li><li>Libretro: mame2003</li><li>Libretro: mame2003_midway</li><li>Libretro: mame2000</li><li>mame64</li></ul> |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **File folder**    | :open\_file\_folder: roms \ :open\_file\_folder: mame                                                                                                                                                                         |
| **File extension** | .zip .7z                                                                                                                                                                                                                      |

## Bios Information

Depending on the [romset type](../../arcade-guide.md#romsets), a BIOS can be required or not to play some games:

* **Full non-merged**: the BIOS is included in the ROM file, so no BIOS file will be needed
* **Non-merged**: same as "Full non-merged" but BIOS that are shared by multiple games are placed outside of the individual ROMs
* **Split**: BIOS files are required
* **Merged**: BIOS files (as well as multiple versions of the game) are placed inside the ROM, no separate BIOS is required

{% hint style="info" %}
Refer to the [Arcade page for more information about ROM set types](../../arcade-guide.md#rom-set-types).
{% endhint %}

**Here is a non-exhaustive list of MAME bios & device files (based on rom set 0.247):**

{% file src="../../../.gitbook/assets/MAME_BIOS_247.dat" %}

{% file src="../../../.gitbook/assets/MAME_Devices_247.dat" %}

BIOS/device files must be placed at the root of the `\bios` folder of your RetroBat installation.

## Controls

### Arcade stick mapping

Mapping can be found in the [notice](http://retrobat.ovh/notice/notice.pdf).

<figure><img src="https://i.imgur.com/kXBcdsB.png" alt=""><figcaption></figcaption></figure>

### Controller mapping

| Retrobat Button                                       | Arcade Key |
| ----------------------------------------------------- | ---------- |
| START                                                 | START      |
| SELECT                                                | COIN       |
| Left analog stick                                     | Stick      |
| Right analog stick                                    |            |
| D-PAD                                                 | Stick      |
| ![](<../../../.gitbook/assets/image (2) (1) (1).png>) | 3          |
| ![](<../../../.gitbook/assets/image (1) (2) (1).png>) | 1          |
| ![](<../../../.gitbook/assets/image (4) (1).png>)     | 2          |
| ![](<../../../.gitbook/assets/image (3) (1) (2).png>) | 4          |
| L1                                                    | 5          |
| R1                                                    | 6          |
| L2                                                    |            |
| R2                                                    |            |
| L3                                                    |            |
| R3                                                    |            |

{% hint style="info" %}
MAME64 Emulator natively accepts Xinput controllers, other controllers will require dedicated mapping ([refer to this guide](../../../controllers/specific\_mapping/mame64-controller-mapping.md)).
{% endhint %}

## Specific system information

### ROM set versions&#x20;

Refer to the [Arcade Guide rom set section](../../arcade-guide.md#available-arcade-emulators-in-retrobat).

### CHD or IMG files

Refer to the [Arcade Guide section](../../arcade-guide.md#chd-or-img-files) about CHD.

### **Sample files**

Refer to the [Arcade Guide "sample file" section](../../arcade-guide.md#samples).
