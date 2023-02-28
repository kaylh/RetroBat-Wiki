# TyrQuake

<figure><img src="https://github.com/fabricecaruso/es-theme-carbon/blob/master/art/logos/tyrquake.png?raw=true" alt=""><figcaption></figcaption></figure>

Game engine to play Quake 1.

{% embed url="https://docs.libretro.com/library/tyrquake/" %}

## Information

| **Emulators**      | <ul><li>Libretro: tyrquake</li></ul>                      |
| ------------------ | --------------------------------------------------------- |
| **File folder**    | :open\_file\_folder: roms \ :open\_file\_folder: tyrquake |
| **File extension** | .pak                                                      |

## Bios Information

No BIOS required.

## Controls

Tyrquakes allows you to choose between 3 controller layouts from RetroBat menu.

| Retrobat Button                                       | Tyrquake Classic                                 | Tyrquake Alt                                     | Tyrquake Modern                                |
| ----------------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ | ---------------------------------------------- |
| START                                                 | Menu                                             | Menu                                             | Menu                                           |
| SELECT                                                | Toggle Run Mode                                  | Toggle Run Mode                                  | Show scores                                    |
| D-PAD                                                 | D-PAD                                            | D-PAD                                            | D-PAD                                          |
| Left analog stick                                     | <p>X-axis : strafe<br>Y-axis: dpad UP/DOWN</p>   | <p>X-axis : strafe<br>Y-axis: dpad UP/DOWN</p>   | <p>X-axis : strafe<br>Y-axis: dpad UP/DOWN</p> |
| Reft analog stick                                     | <p>X-axis : dpad L/R<br>Y-axis: Look UP/DOWN</p> | <p>X-axis : dpad L/R<br>Y-axis: Look UP/DOWN</p> | Look                                           |
| ![](<../../../.gitbook/assets/image (2) (1) (1).png>) | Fire                                             | Look left                                        | Swim Up                                        |
| ![](<../../../.gitbook/assets/image (1) (2) (1).png>) | Jump                                             | Look down                                        | Swim Down                                      |
| ![](<../../../.gitbook/assets/image (4) (1).png>)     | Cycle weapon                                     | Look right                                       | Strafe Right                                   |
| ![](<../../../.gitbook/assets/image (3) (1) (2).png>) | Freelook                                         | Look up                                          | Strafe Left                                    |
| L1                                                    | Strafe Left                                      | Jump                                             | Previous Weapon                                |
| R1                                                    | Strafe Right                                     | Fire                                             | Next Weapon                                    |
| L2                                                    | Look up                                          | Run                                              | Jump                                           |
| R2                                                    | Look down                                        | Next Weapon                                      | Fire                                           |
| L3                                                    | Move down                                        | Swim Down                                        | Move Down                                      |
| R3                                                    | Swim up                                          | Previous Weapon                                  | Swim Up                                        |

## Specific system information

### File organization

Here is the structure organization for your tyrquake rom files:

<pre><code>└── roms\
    └── tyrquake\
        ├── id1\
<strong>        │   └── pak0.pak
</strong><strong>        │   └── pak1.pak
</strong>        │   └── music\
        │       └── track02.ogg
        │       └── ...
        └── hipnotik\
        │   └── pak0.pak
        │   └── music\
        │       └── track02.ogg
        │       └── ...
        └── rogue\
<strong>        │   └── pak0.pak
</strong>        │   └── music\
        │       └── track02.ogg
        │       └── ...
        └── dopa\
            └── pak0.pak
</code></pre>
