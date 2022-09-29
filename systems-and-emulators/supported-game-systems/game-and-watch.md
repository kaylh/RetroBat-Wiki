---
description: G&W
---

# Game & Watch

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/5149a33eed46b2af638b06119397d4023b75131f/art/logos/gameandwatch.svg" alt=""><figcaption></figcaption></figure>

Game Console - Lifespan: 1980 - 1991

{% embed url="https://en.wikipedia.org/wiki/Game_%26_Watch" %}

## Information

| **Emulators**       | <ul><li>libretro: gw</li><li>libretro: mame</li><li>mame64</li></ul> |   |
| ------------------- | -------------------------------------------------------------------- | - |
| **Games Location**  | :open\_file\_folder:roms \ :open\_file\_folder: gameandwatch         |   |
| **File extensions** | .mgw .zip .7z                                                        |   |

## BIOS

No BIOS required for Game & Watch games.

## Controls

| RetroBat key                                                                        | G\&W key         |
| ----------------------------------------------------------------------------------- | ---------------- |
| START                                                                               | Menu             |
| D-PAD                                                                               | D-PAD            |
| ![A](<../../.gitbook/assets/image (1) (2).png>)                                     | Specific to game |
| ![B](<../../.gitbook/assets/image (4) (1).png>)                                     | Specific to game |
| <img src="../../.gitbook/assets/image (3) (1) (2).png" alt="" data-size="original"> | Specific to game |
| <img src="../../.gitbook/assets/image (2) (1) (1).png" alt="" data-size="line">     | Specific to game |

## System Features

### How to run games

The RetroArch "**Handheld Electronic (GW)**" core is used to run a large number of Game & Watch games.

List of games that work with the core "**Handheld Electronic (GW)**":

{% code overflow="wrap" %}
```
"Armor Battle"
"Banana (Time & Fun)"
"Baseball (Explorer Time & Fun)"
"Bomb Fight (Mini Time & Fun)"
"Caccia al Ladro (Mini Time & Fun)"
"Cessate il Fuoco (Mini Time & Fun)"
"Chicky Woggy (Arcade Time & Fun)"
"Chicky Woggy (Electronic Tini-Arcade)"
"Condor (Time & Fun)"
"Crazy Chewy (Electronic Tini-Arcade)"
"Defendo (Explorer Time & Fun)"
"Donkey Angler (LCD Card Game)"
"Donkey Kong"
"Donkey Kong (Multi Screen)"
"Donkey Kong Circus (Panorama Screen)"
"Donkey Kong II (Multi Screen)"
"Donkey Kong Jr."
"Donkey Kong Jr. (Panorama Screen)"
"Donkey Kong Jr. (Table Top)"
"Dungeons & Dragons Computer Fantasy Game (Arcade
"Egg (Wide Screen)"
"Engine Room (Explorer Time & Fun)"
"Escape (Time & Fun)"
"Explorers of Space"
"Fowling"
"Frog Boaster"
"Galaxy II"
"Grab Man (Game & Time)"
"Hippo Teeth (Mini Time & Fun)"
"Hippo Teeth (Sporty Time & Fun)"
"Hot Line (Mini Time & Fun)"
"Hot Line (Sporty Time & Fun)"
"Las Vegas (LCD Game Digital)"
"Lifeboat (Multi Screen)"
"Mario Bros. (Multi Screen)"
"Mario's Bombs Away (Panorama Screen)"
"Mickey Mouse (Panorama Screen)"
"Mickey Mouse (Wide Screen)"
"Monkey (Time & Fun)"
"Monkey Jump (Arcade Time & Fun)"
"Motor Cross"
"Pac Man"
"Pancake (Time & Fun)"
"Parachute (Wide Screen)"
"Penguin Land (LSI Game Double Play)"
"Pirate (Time & Fun)"
"Roller Coaster (Explorer Time & Fun)"
"Safari (Time & Fun)"
"Sleep Walker (Time & Fun)"
"Snoopy (Panorama Screen)"
"Snoopy (Table Top)"
"Snoopy Tennis (Wide Screen)"
"Sub Chase"
"Tennis Menace (Sporty Time & Fun)"
"Tom & Jerry Popper (LCD Card Game)"
"Towering Rescue (LCD Card Game)"
"Tron"
"Turtle Bridge (Wide Screen)"
"Wild Man Jump (Electronic Tini-Arcade)"
```
{% endcode %}

But many liquid crystal electronic games are not supported by this core.\
To make them work you must use the core "**MAME (current)**"\
These games need 2 different files, a file of type "_rom"_ and a file of type "_artwork_ " to work.\
\
You must place the rom file in .zip format in the same folder as other Game & Watch games: `\roms\gameandwatch`

<figure><img src="https://i.imgur.com/ALEygG9.png" alt=""><figcaption></figcaption></figure>

And the artwork files which have exactly the same name as the roms (also .zip format): `\bios\mame\artwork`

<figure><img src="https://i.imgur.com/H39e9W9.png" alt=""><figcaption></figcaption></figure>

Then launch Retrobat and go to the **Game & Watch** system and [change the emulator for the game](../../get-started/running-a-game.md#choosing-the-emulator).
