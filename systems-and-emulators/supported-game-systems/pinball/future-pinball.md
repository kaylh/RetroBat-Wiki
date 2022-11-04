# Future Pinball

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/52ff37c9e265587d006945a2ba695b5a962b3a3d/art/logos/fpinball.svg" alt=""><figcaption></figcaption></figure>

Pinball Simulation Software

{% embed url="https://en.wikipedia.org/wiki/Future_Pinball" %}

{% embed url="https://futurepinball.com/" %}

## Information

<table data-header-hidden><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><strong>Emulators</strong></td><td><ul><li>fpinball</li></ul></td><td></td></tr><tr><td><strong>Games Location</strong></td><td><span data-gb-custom-inline data-tag="emoji" data-code="1f4c2">📂</span>roms \ <span data-gb-custom-inline data-tag="emoji" data-code="1f4c2">📂</span> fpinball</td><td></td></tr><tr><td><strong>File extensions</strong></td><td>.fpt .7z .zip .rar</td><td></td></tr></tbody></table>

## BIOS

No BIOS required.

## Controls

| RetroBat key                                                                           | Future Pinball key       |
| -------------------------------------------------------------------------------------- | ------------------------ |
| START                                                                                  | START game               |
| SELECT                                                                                 | Insert COIN              |
| D-PAD                                                                                  | Shake the Pinball        |
| Left Analog stick                                                                      |                          |
| Right Analog stick                                                                     |                          |
| ![A](<../../../.gitbook/assets/image (1) (2) (1).png>)                                 | Ball Launcher            |
| ![B](<../../../.gitbook/assets/image (4) (1).png>)                                     | Look up to the backglass |
| <img src="../../../.gitbook/assets/image (3) (1) (2).png" alt="" data-size="original"> | Pause / Highscores       |
| <img src="../../../.gitbook/assets/image (2) (1) (1).png" alt="" data-size="line">     | Change Camera view       |
| L1                                                                                     | Left Flipper             |
| R1                                                                                     | Right Flipper            |
| L2                                                                                     |                          |
| R2                                                                                     |                          |
| L3                                                                                     |                          |
| R3                                                                                     |                          |

## Specific system information

### Tables

Future Pinball tables are distributed as `.fpt` files.&#x20;

Some tables are fully contained in the `.fpt` file, these kind of tables can simply be placed in `\roms\fpinball` folder.

Some tables require additional files to work (fonts, music, textures...), these kind of tables need to be placed in a subfolder of their own in the `\roms\fpinball` folder:

```
roms\
└─ fpinball\
   └─ 24 (Stern) (2009) (Collectors Edition) (1.01)\
      ├─ 24 (Stern) (2009) (Collectors Edition) (1.01).fpt
      ├─ 24fonts.fpl
      └─ 24textures.fpl
```

### **Why there is an error message ?**

If you receive an error message like the following one:

<figure><img src="https://i.imgur.com/UjD7GIy.png" alt=""><figcaption></figcaption></figure>

You need to launch Future Pinball as administrator once only.\
\
So, go to the "**fpinball**" folder in the "**emulators**" folder at the root of your Retrobat installation folder.\
\
Then right-click on the Future Pinball executable "**Future Pinball.exe**" and, as showed on the picture, select "**Run as administrator**"

<figure><img src="https://i.imgur.com/2XXANBV.png" alt=""><figcaption></figcaption></figure>

Once Future Pinball has started, you can close it and start it again from Retrobat.
