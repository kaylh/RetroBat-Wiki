---
description: Nintendo
---

# Nintendo 64 Disk Drive

<figure><img src="https://hyperspin-fe.com/siteuploads/downloads/screenshots/monthly_2018_03/5ab59a08f060d_Nintendo64dd.png.37360958cf54c2250cba823a58c0fad2.png" alt=""><figcaption></figcaption></figure>

Game Console - Lifespan: 1999- 2001

{% embed url="https://en.wikipedia.org/wiki/64DD" %}

## Information

<table data-header-hidden><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><strong>Emulators</strong></td><td><ul><li>libretro: mupen64plus next</li><li>project64</li></ul></td><td></td></tr><tr><td><strong>Games Location</strong></td><td><span data-gb-custom-inline data-tag="emoji" data-code="1f4c1">📁</span> roms \ <span data-gb-custom-inline data-tag="emoji" data-code="1f4c2">📂</span> n64dd</td><td></td></tr><tr><td><strong>File extensions</strong></td><td>.v64 .z64 .n64 .ndd</td><td></td></tr></tbody></table>

## BIOS

<table data-header-hidden><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td>IPL_JAP.n64<br>Japan</td><td><strong>location:</strong> \bios\Mupen64plus<br><strong>md5:</strong> <code>8d3d9f294b6e174bc7b1d2fd1c727530</code></td><td></td></tr><tr><td>IPL_USA.n64<br>USA</td><td><strong>location:</strong> \bios\Mupen64plus<br><strong>md5:</strong> <code>37c36e4286d36892a9fc70eafe4104be</code></td><td></td></tr><tr><td>IPL_DEV.n64<br>Development Kit</td><td><strong>location:</strong> \bios\Mupen64plus<br><strong>md5:</strong> </td><td></td></tr></tbody></table>

## Controls

Same as [N64](nintendo-64.md#controls)

## Specific System Information

### Running Games

There are two types of games on the Nintendo 64DD, full games and game expansions.&#x20;

In order to get n64dd games running successfully, it is required to have two files per game.&#x20;

One of the files is a n64 ROM file and the other is a n64dd .ndd file.&#x20;

Both files need to have the exact same filename and in the case of the n64dd .ndd file, it must have a double extension with the same extension than the n64 rom file, added before its own extension.\


In the case of game expansion like the one in the example below, the n64 game is the actual ROM file for which the n64dd .ndd file is the expansion.&#x20;

For the full games, you also always need two files, so the n64dd .ndd file of the full game and another n64 rom of any title that you just need to rename.\


Example filenames with the expansion "F-Zero X Expansion Kit":

* Rename n64dd .ndd file\
  `F-Zero X - Expansion Kit (Japan).ndd`\
  ``to\
  `F-Zero X - Expansion Kit (Japan).n64.ndd`
* Rename n64 rom file\
  `F-Zero X (Japan).n64`\
  `` to \
  `F-Zero X - Expansion Kit (Japan).n64`
* Run expansion with\
  `F-Zero X - Expansion Kit (Japan).n64`

Example with the full game "SimCity 64":

* Rename `SimCity 64 (Japan).ndd` to `SimCity 64 (Japan).n64.ndd`
* Pick any n64 roms file and rename it `SimCity 64 (Japan).n64`
* Then run `SimCity 64 (Japan).n64` in RetroBat.

{% hint style="info" %}
Always run the .n64 or .z64 file from RetroBat, as running the .ndd will lead to an error message.

To avoid confusion, you can hide the .ndd extensions for the system.
{% endhint %}

### BIOS selection

Althrough only commercialized in Japan, US games are available for the n64dd system, as well as prototypes using a specific "dev" BIOS.

The right BIOS can be selected directly in Retrobat Games Options menu, per game.

<figure><img src="https://i.imgur.com/htqkK3Q.png" alt=""><figcaption><p>Advanced System Options / Emulation / BIOS</p></figcaption></figure>
