# PrBoom

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/52ff37c9e265587d006945a2ba695b5a962b3a3d/art/logos/prboom.svg" alt=""><figcaption></figcaption></figure>

Game engine to play Doom, Doom II, Doom Ultimate, Final Doom and other Doom IWAD mods.

{% embed url="https://docs.libretro.com/library/prboom/" %}

## Information

| **Emulators**      | <ul><li>Libretro: prboom</li></ul>                      |
| ------------------ | ------------------------------------------------------- |
| **File folder**    | :open\_file\_folder: roms \ :open\_file\_folder: prboom |
| **File extension** | .wad .iwad .pwad                                        |

## Bios Information

No BIOS required.

## Controls

| Retrobat Button                                       | PrBoom key      |
| ----------------------------------------------------- | --------------- |
| START                                                 | Show/Hide Menu  |
| SELECT                                                | Show/Hide Map   |
| D-PAD                                                 | D-PAD           |
| Left analog stick                                     |                 |
| Reft analog stick                                     |                 |
| ![](<../../../.gitbook/assets/image (2) (1) (1).png>) | Run             |
| ![](<../../../.gitbook/assets/image (1) (2) (1).png>) | Use             |
| ![](<../../../.gitbook/assets/image (4) (1).png>)     | Fire            |
| ![](<../../../.gitbook/assets/image (3) (1) (2).png>) | Strafe          |
| L1                                                    | Strafe Left     |
| R1                                                    | Strafe Right    |
| L2                                                    | Previous Weapon |
| R2                                                    | Next Weapon     |

## Specific system information

### File organization

PrBoom can load wad, iwad, and pwad files.&#x20;

WAD and IWAD files are "`Internal Where's All the Data`" files, meaning they are used to run the game.

PWAD files are patches, they need the main game WAD/IWAD file to run.

Hereunder is the recommendation for the organization of your prboom folder:

<pre><code>└── roms\
    └── prboom\
        ├── doom\
<strong>        │   └── doom.wad
</strong>        └── doom 2\
        │   └── doom2.wad
        └── Doom Ultimate\
        │   └── doomu.wad</code></pre>

If you are going to use pwad files, they will have to be placed in a subfolder inside the main wad game folder:

<pre><code>└── roms\
    └── prboom\
        ├── doom\
<strong>        │   └── doom.wad
</strong>        │   └── Episode 5 - Sigil\
        │           └── SIGIL.pwad
        └── Doom 2\
            └── doom2.wad
            └── Goldeneye\
                    └── goldeneye.pwad        </code></pre>
