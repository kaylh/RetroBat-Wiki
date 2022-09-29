---
description: Bang bang
---

# 🔫 Lightguns

Lightgun compatibility is still in early phase in Retrobat, it might be possible that for many Emulators, specific configuration is required to make it work correctly.

There are several lightguns on the market, the list of compatible will grow, however only a few have been tested so far.



When a lightgun is connected to the system, you will notice that a small gun icon appears on the top left corner near the Gamepad icon : ![](<../../../.gitbook/assets/image (3).png>)

Also, a crosshair will appear on the screen as well as a collection called **LIGHT GUN** in the System View.

<figure><img src="https://i.imgur.com/YDBWOrd.png" alt=""><figcaption></figcaption></figure>

LightGun compatible games will have a specific icon next to their name in the Game View

<figure><img src="https://i.imgur.com/rbFVyjA.png" alt=""><figcaption><p>Duck Hunt is compatible</p></figcaption></figure>

The list of LightGun games is stored in an .xml file inside your Retrobat folder, if you find that some games appear in the list but are not LightGun games, you can remove them from the list.

<figure><img src="https://i.imgur.com/WrtdDbz.png" alt=""><figcaption><p>gungames.xml folder</p></figcaption></figure>

{% hint style="info" %}
Some games appear in the list but the LightGun functionality is only in some levels or as a mini-game.
{% endhint %}

## Lightgun Configuration

### Lightgun Activation

Lightguns can be activated for a system or for a game.

To activate Lightguns for a system, from the Game View, open the [View Options](../../../navigation/view-options.md) and select **ADVANCED SYSTEM OPTIONS**

<figure><img src="https://i.imgur.com/rfmZxeu.png" alt=""><figcaption></figcaption></figure>

Navigate to **CONTROLS**

<figure><img src="https://i.imgur.com/lbqvjVS.png" alt=""><figcaption></figcaption></figure>

Switch **LIGHTUN** to **ON**

<figure><img src="https://i.imgur.com/rpt8cBZ.png" alt=""><figcaption></figcaption></figure>

The same can be done per game from the [Game Options](../../../navigation/game-options.md) menu and **ADVANCED GAME OPTIONS**

{% hint style="info" %}
**Fo**r some systems the option will be directly in the **ADVANCED OPTIONS** list (e.g. 3DO), for some other systems the option will be named **LIGHTGUN MODE** (e.g. MAME).
{% endhint %}

### Calibration

{% hint style="danger" %}
In construction
{% endhint %}

## Lightgun Devices

### WiiMote & Mayflash DolphinBar

![](<../../../.gitbook/assets/image (1).png>)![](<../../../.gitbook/assets/image (1) (2).png>)

The Wiimote and DolphinBar is actually a great way to enjoy your Lightgun game library.

There are 2 ways of using the Wiimote as a Lightgun:

* By using the mode 2 of the Mayflash Dolphinbar
* By using the mode 4 of the Mayflash Dolphinbar and activating the [WiimoteGun software](wiimotegun.md).

{% hint style="info" %}
This guide assumes that you already know how to connect your Mayflash Dolphinbar and your Wiimotes. If not you can find all instructions on the [Mayflash Website](https://www.mayflash.com/product/6.html).
{% endhint %}

Both of these options will serve the same purpose : it will convert your Wiimotes movements and buttons into Mouse & Keyboard keys. This means that emulators that can use a mouse as a gun will be able to work with the Wiimote.

When using the Dolphinbar in mode 4 with WiimoteGun, you will be able to calibrate your Wiimote with a long-press on the "Home" button of the Wiimote.

{% hint style="info" %}
For better accuracy, it is recommended to place your Dolphinbar UNDER your screen, as close as possible to the display (do not forget to set your Dolphinbar switch at the back to the BOTTOM position).
{% endhint %}

{% hint style="info" %}
For Dolphin standalone emulator, you need to set the Dolphinbar in mode 4 as this is the native Wiimote mode supported by Dolphin and allowing you to use your wiimotes as **REAL WIIMOTES** for best possible experience. See the Wii section of the wiki for more information.
{% endhint %}

### AE Lightgun

TBD

### Sinden Lightgun

TBD

### Gun4IR

TBD

## Compatible LightGun Systems

{% hint style="danger" %}
Under testing and construction
{% endhint %}
