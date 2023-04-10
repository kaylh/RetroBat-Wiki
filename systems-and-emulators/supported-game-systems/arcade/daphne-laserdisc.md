# LaserDisc

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/52ff37c9e265587d006945a2ba695b5a962b3a3d/art/logos/daphne.svg" alt=""><figcaption></figcaption></figure>

Arcade - First LaserDisc game release : 1983

{% embed url="http://www.daphne-emu.com/site3/index_hi.php" %}

## Information

<table data-header-hidden><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><strong>Emulators</strong></td><td><ul><li>hypseus</li><li>daphne</li></ul></td><td></td></tr><tr><td><strong>Games Location</strong></td><td><span data-gb-custom-inline data-tag="emoji" data-code="1f4c1">📁</span> roms \ <span data-gb-custom-inline data-tag="emoji" data-code="1f4c2">📂</span> daphne</td><td></td></tr><tr><td><strong>File extensions</strong></td><td>.daphne .actionmax .7z .zip .rar .squashfs</td><td></td></tr></tbody></table>

## BIOS

No BIOS required to play DAPHNE or SINGE games.

## Controls

### Gamepad controls&#x20;

Gamepad controls are enabled through pad2key files provided with Retrobat installation:

| Action               | Gamepad Button             |
| -------------------- | -------------------------- |
| Directional movement | D-PAD or Left analog stick |
| COIN 1               | SELECT                     |
| START 1              | START                      |
| Button 1             | A                          |
| Button 2             | B                          |
| Button 3             | R2                         |
| Skill 1              | Y                          |
| Skill 2              | X                          |
| Skill 3              | L2                         |
| SERVICE              | HOTKEY + B                 |
| TEST                 |                            |
| RESET                | HOTKEY + X                 |
| Screenshot           |                            |
| Quit                 | HOTKEY + START             |
| Pause                | HOTKEY + A                 |
| Console              |                            |
| Title                | HOTKEY + Y                 |

**NOTE:** Right Analog stick simulates mouse



### Keyboard controls:

| Action               | Keyboard Hypseus | Keyboard Daphne       |
| -------------------- | ---------------- | --------------------- |
| Directional movement | ARROW Keys       | ARROW Keys or 8,4,2,6 |
| COIN 1               | 5                | 5 or c                |
| COIN 2               | 6                | 6                     |
| START 1              | 1                | 1                     |
| START 2              | 2                | 2                     |
| Button 1             | LEFT CONTROL     | LEFT CTRL or SPACE    |
| Button 2             | LEFT ALT         | LEFT ALT              |
| Button 3             | SPACE            | LEFT SHIFT            |
| Skill 1              | LEFT SHIFT       | /                     |
| Skill 2              | Z                | \*                    |
| Skill 3              | X                | -                     |
| SERVICE              | 9                | 9                     |
| TEST                 | F2               | F2                    |
| RESET                | 0                | F3                    |
| Screenshot           | F12              | F12                   |
| Quit                 | ESC              | ESC or q              |
| Pause                | P                | P                     |
| Console              | BACKLASH         |                       |
| Title                | T                | t                     |

## Specific system information

### Adding Daphne Games

Daphne games consist of 2 parts

* a folder containing the **videos**, \*.**dat** and \*.**txt** files of the games
* a .zip file in the **roms** folder

To add Daphne games, your games folders must be placed in "**\roms\daphne**" folder by adding **.daphne** at the end.

For example, your game folder "**lair**" (Dragon's Lair) must be renamed to **lair.daphne**

```
roms\
└─ daphne\
   ├─ roms\
   │  └─ lair.zip
   └─ lair.daphne\
      └─ lair.dat
      └─ lair.m2v
      └─ lair.ogg
      └─ lair.txt
```

Once the game added, it is listed twice in Retrobat, as both the zip and the .daphne folder are detected.

<figure><img src="https://i.imgur.com/crqriZ1.png" alt=""><figcaption><p>lair appears twice</p></figcaption></figure>

You can use use the [**VIEW OPTIONS**](../../../navigation/view-options.md) to hide the `.zip` extension for the system by pressing **SELECT**

<figure><img src="https://i.imgur.com/dQngpx5.png" alt=""><figcaption></figcaption></figure>

Navigate to [**VIEW CUSTOMIZATION**](../../../navigation/view-options.md#view-options) and FILE EXTENSIONS

<figure><img src="https://i.imgur.com/JT7AqDc.png" alt=""><figcaption></figcaption></figure>

Untick .zip extension

<figure><img src="https://i.imgur.com/B38zdIa.png" alt=""><figcaption></figcaption></figure>

### Adding SINGE Games

SINGE games include the famous AMERICAN LASR GAMES and a few other titles.

The process is similar as for Daphne games but there is no zip file to place in the roms folder. In addition, 2 files need to be present in your `<game>.daphne` folder:

* `<game>.singe`
* `<game>.txt`

**T**he structure of the game folder should look like this:

<figure><img src="https://i.imgur.com/QPFt4jZ.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
~~Note that Hypseus games will only work if you activate the "Developper Mode" in Windows.~~
{% endhint %}

<figure><img src="https://i.imgur.com/9fAIgE0.png" alt=""><figcaption><p>NOT NECESSARY SINCE RETROBAT VERSION 5.2.0</p></figcaption></figure>

### Add Actionmax games

ActionMax games are compatible with Hypseus emulator but they require a very specific folder structure.

All Actionmax games must be located inside `roms\daphne\actionmax` folder with the following content:

```
+---38ambushalley
|       video_38ambushalley.dat
|       video_38ambushalley.m2v
|       video_38ambushalley.ogg
|       
+---bluethunder
|       video_bluethunder.m2v
|       video_bluethunder.ogg
|       
+---hydrosub2021
|       video_hydrosub2021.m2v
|       video_hydrosub2021.ogg
|       
+---popsghostly
|       video_popsghostly.m2v
|       video_popsghostly.ogg
|       
+---sonicfury
        video_sonicfury.m2v
        video_sonicfury.ogg
|
|   38ambushalley.singe
|   38ambushalley.txt
|   bluethunder.singe
|   bluethunder.txt
|   emulator.singe
|   font_bluestone.ttf
|   font_chemrea.ttf
|   font_led_real.ttf
|   framework.singe
|   hydrosub2021.singe
|   hydrosub2021.txt
|   popsghostly.singe
|   popsghostly.txt
|   sonicfury.singe
|   sonicfury.txt
|   sound_actionmax.wav
|   sound_asteadyaimiscritical.wav
|   sound_badhit.wav
|   sound_gameover.wav
|   sound_getreadyforaction.wav
|   sound_goodhit.wav
|   sound_gunshot.wav
|   sprite_38ambushalley.png
|   sprite_actionmax.png
|   sprite_actionmax_orig.png
|   sprite_bluethunder.png
|   sprite_bullet.png
|   sprite_crosshair.png
|   sprite_hydrosub2021.png
|   sprite_lightoff.png
|   sprite_lighton.png
|   sprite_popsghostly.png
|   sprite_sonicfury.png
|   video_actionmaxintro.dat
|   video_actionmaxintro.m2v
|   video_actionmaxintro.ogg
|   video_menu.dat
|   video_menu.m2v
|   video_menu.ogg
```

Create an empty file and name it with the name of the game and the extension .actionmax in the `roms\daphne` folder (eg. `sonicfury.actionmax`).

<figure><img src="https://i.imgur.com/NQX8l4t.png" alt=""><figcaption></figcaption></figure>

As for Hypseus, the Developper Mode must be enabled in Windows to run Actionmax games.
