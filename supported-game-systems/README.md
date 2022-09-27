# Supported Game Systems

The following table is the official list of all supported game systems as per the es\_systems configuration file.

The **system name** column corresponds to the directory where the game roms must be placed in the "roms" folder of the root Retrobat folder.

The **Full Name** column is the actual gaming system name.

The **Default Emulator** column lists the primary emulator configured in Retrobat for the system. All emulators are retroarch cores unless marked as **(s)** for standalone emulators.

The **Alternative Emulators** column lists the additional emulators that can be configured by system or per game. As in the Standard Emulator column, the mark (standalone) is used for non retroarch cores emulators.

Additional information related to BIOS and rom file formats can be found in the detailed section related to the system / emulator.

| System Name   | Full Name                            | Default Emulator  | Alternative Emulators                                                                                |
| ------------- | ------------------------------------ | ----------------- | ---------------------------------------------------------------------------------------------------- |
| 3do           | 3DO                                  | 4do               | opera                                                                                                |
| 3ds           | Nintendo 3DS                         | citra             | citra(s)                                                                                             |
| advision      | Adventure Vision                     | mame              | mame64(s)                                                                                            |
| amiga500      | Amiga OCS/ECS                        | puae              | <p>amigaforever(s)<br>winuae(s)</p>                                                                  |
| amiga1200     | Amiga AGA                            | puae              | <p>amigaforever(s)<br>winuae(s)</p>                                                                  |
| amigacd32     | Amiga CD32                           | puae              | <p>amigaforever(s)<br>winuae(s)</p>                                                                  |
| amigacdtv     | Amiga CDTV                           | puae              | amigaforever(s)                                                                                      |
| amstradcpc    | Amstrad CPC                          | cap32             | crocods                                                                                              |
| apfm1000      | APF M-1000                           | mame              | mame64(s)                                                                                            |
| apple2        | Apple II                             | applewin(s)       |                                                                                                      |
| apple2gs      | Apple IIGS                           | gsplus(s)         |                                                                                                      |
| arcadia       | Arcadia 2001                         | mame              | mame64(s)                                                                                            |
| astrocade     | Astrocade                            | mame              | mame64(s)                                                                                            |
| atari800      | Atari 800                            | atari800          |                                                                                                      |
| atari2600     | Atari 2600                           | stella            | stella2014                                                                                           |
| atari5200     | Atari 5200                           | a5200             | <p>atari800<br>stella2014</p>                                                                        |
| atari7800     | Atari 7800                           | prosystem         |                                                                                                      |
| atarist       | Atari ST                             | hatari            |                                                                                                      |
| atomiswave    | Atomiswave                           | flycast           | demul(s)                                                                                             |
| bbcmicro      | BBC Micro                            | mame              | mame64(s)                                                                                            |
| c20           | VIC-20                               | vice\_xvic        |                                                                                                      |
| c64           | Commodore 64                         | vice\_x64         | <p>vice_x64sc<br>vice_x128<br>vice_xplus4<br>vice_xvic<br>vice_xpet<br>frodo</p>                     |
| c128          | Commodore 128                        | vice\_x128        |                                                                                                      |
| camplynx      | Camputers Lynx                       | mame              | mame64(s)                                                                                            |
| cave          | CAVE                                 | fbneo             | <p>fbalpha<br>fbalpha2012<br>mame2003_plus<br>mame2016<br>mame<br>mame64(s)</p>                      |
| cavestory     | Cavestory                            | nxengine          |                                                                                                      |
| cdi           | Philips CD-i                         | mame              | mame64(s)                                                                                            |
| channelf      | Fairchild Channel F                  | freechaf          |                                                                                                      |
| chihiro       | Chihiro                              | chihiro(s)        | xemu(s)                                                                                              |
| coco          | TRS-80 Color Computer                | mame              | mame64(s)                                                                                            |
| colecovision  | ColecoVision                         | gearcoleco        | <p>bluemsx<br>fbneo</p>                                                                              |
| cps1          | CPS-I                                | fbalpha2012\_cps1 | <p>fbneo<br>fbalpha<br>fbalpha2012</p>                                                               |
| cps2          | CPS-II                               | fbalpha2012\_cps2 | <p>fbneo<br>fbalpha<br>fbalpha2012</p>                                                               |
| cps3          | CPS-III                              | fbalpha2012\_cps3 | <p>fbneo<br>fbalpha<br>fbalpha2012</p>                                                               |
| crvision      | CreatiVision                         | mame              | mame64(s)                                                                                            |
| daphne        | Laserdisc                            | hypseus(s)        | daphne(s)                                                                                            |
| dos           | DOS                                  | dosbox\_pure      | dosbox(s)                                                                                            |
| dreamcast     | Dreamcast                            | flycast           | <p>redream<br>redream(s)<br>demul(s)</p>                                                             |
| easyrpg       | EasyRPG - RPG Maker 2000/2003 player | easyrpg           |                                                                                                      |
| fbneo         | Final Burn                           | fbneo             | <p>fbalpha<br>fbalpha2012<br>fbalpha2012_neogeo</p>                                                  |
| fds           | Nintendo Family Computer Disk System | fceumm            | <p>nestopia<br>mesen<br>mesen(s)</p>                                                                 |
| flash         | flash                                | arcadeflashweb(s) |                                                                                                      |
| fm7           | FM-7                                 | mame              | mame64(s)                                                                                            |
| fmtowns       | FM Towns                             | mame              | <p>tsugaru(s)<br>mame64(s)</p>                                                                       |
| fpinball      | Future Pinball                       | fpinball          |                                                                                                      |
| gaelco        | Gaelco PowerVR                       | demul-old(s)      |                                                                                                      |
| gamate        | Gamate                               | mame              | mame64(s)                                                                                            |
| gameandwatch  | Game and Watch                       | gw                | mame64(s)                                                                                            |
| gamecom       | Game.com                             | mame              | mame64(s)                                                                                            |
| gamecube      | GameCube                             | dolphin(s)        | dolphin                                                                                              |
| gamegear      | Game Gear                            | genesis\_plus\_gx | <p>picodrive<br>fbneo</p>                                                                            |
| gamepock      | Game Pocket Computer                 | mame              | mame64(s)                                                                                            |
| gb            | Game Boy                             | gambatte          | <p>mesen-s<br>bsnes<br>tgbdual</p>                                                                   |
| gb2players    | Game Boy 2 Players                   | tgbdual           |                                                                                                      |
| gba           | Game Boy Advance                     | mgba              | <p>mednafen_gba<br>mgba(s)<br>nosgba(s)</p>                                                          |
| gba2players   | Game Boy Advance 2 Players           | nosgba(s)         |                                                                                                      |
| gbc           | Game Boy Color                       | gambatte          | tgbdual                                                                                              |
| gbc2players   | Game Boy Color 2 Players             | tgbdual           |                                                                                                      |
| gmaster       | Game Master                          | mame              | mame64(s)                                                                                            |
| gx4000        | Amstrad GX4000                       | cap32             |                                                                                                      |
| hbmame        | MAME Homebrew                        | mame              | <p>mame2003_plus<br>mame2003<br>mame2003_midway<br>mame2016<br>mame64(s)</p>                         |
| hikaru        | Hikaru                               | demul(s)          |                                                                                                      |
| intellivision | Mattel Intellivision                 | freeintv          |                                                                                                      |
| jaguar        | Jaguar                               | virtualjaguar     |                                                                                                      |
| lcdgames      | LCD Games                            | mame              | <p>gw<br>mame64(s)</p>                                                                               |
| love          | LÖVE                                 | love(s)           |                                                                                                      |
| lutro         | Lutro Lua Framework                  | lutro             |                                                                                                      |
| lynx          | Lynx                                 | mednafen\_lynx    | handy                                                                                                |
| mame          | MAME                                 | mame              | <p>mame2016<br>mame2010<br>mame2003_plus<br>mame2003<br>mame2003_midway<br>mame2000<br>mame64(s)</p> |
| mastersystem  | Master System - Mark III             | genesis\_plus\_gx | <p>picodrive<br>fbneo<br>kega-fusion(s)</p>                                                          |
| megadrive     | Megadrive - Genesis                  | genesis\_plus\_gx | <p>genesis_plus_gx_wide<br>picodrive<br>fbneo<br>mednafen(s)<br>kega-fusion(s)</p>                   |
| megadrive-msu |                                      |                   |                                                                                                      |
| megaduck      |                                      |                   |                                                                                                      |

