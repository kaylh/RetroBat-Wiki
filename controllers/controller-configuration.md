# Controllers Configuration

## General Controller Configuration

Connect a controller and press a button, **CONFIGURE INPUT** screen appears.

<figure><img src="https://i.imgur.com/C8T3fn5.png" alt=""><figcaption><p>Press and hold any button</p></figcaption></figure>

Press and hold any button to go to the **CONFIGURING** screen

<div align="left">

<figure><img src="https://i.imgur.com/NhgVTbZ.png" alt=""><figcaption></figcaption></figure>

</div>

Press each button accordingly to finalize your controller mapping.

{% hint style="info" %}
If your controller does not have that many buttons, hold a button (long-press) to ignore the current line and skip to the next one.

Note that at least you need to map A, B, D-PAD, START, SELECT and Hotkey.
{% endhint %}

The table hereunder gives you the standard mapping for the following controllers:

* Microsoft XBOX
* Playstation
* Nintendo controller

<table><thead><tr><th width="184">Retrobat Key</th><th>Microsoft</th><th>PlayStation</th><th>Nintendo</th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (1) (2) (1).png" alt="A"></td><td>A</td><td><img src="../.gitbook/assets/image (11).png" alt=""></td><td>B</td></tr><tr><td><img src="../.gitbook/assets/image (4) (1).png" alt=""></td><td>B</td><td><img src="../.gitbook/assets/image (8) (1).png" alt=""></td><td>A</td></tr><tr><td><img src="../.gitbook/assets/image (3) (1) (2).png" alt=""></td><td>Y</td><td><img src="../.gitbook/assets/image (7).png" alt=""></td><td>X</td></tr><tr><td><img src="../.gitbook/assets/image (2) (1) (1).png" alt="" data-size="line"></td><td>X</td><td><img src="../.gitbook/assets/image (10).png" alt=""></td><td>Y</td></tr><tr><td>START</td><td><img src="../.gitbook/assets/image (5) (1).png" alt=""></td><td>START / OPTIONS</td><td>+</td></tr><tr><td>SELECT</td><td><img src="../.gitbook/assets/image (6) (1).png" alt=""></td><td>SELECT / SHARE</td><td>-</td></tr><tr><td>D-PAD UP</td><td>D-PAD UP</td><td>D-PAD UP</td><td>D-PAD UP</td></tr><tr><td>D-PAD DOWN</td><td>D-PAD DOWN</td><td>D-PAD DOWN</td><td>D-PAD DOWN</td></tr><tr><td>D-PAD LEFT</td><td>D-PAD LEFT</td><td>D-PAD LEFT</td><td>D-PAD LEFT</td></tr><tr><td>D-PAD RIGHT</td><td>D-PAD RIGHT</td><td>D-PAD RIGHT</td><td>D-PAD RIGHT</td></tr><tr><td>L1</td><td>Left Bottom</td><td>L1</td><td>L</td></tr><tr><td>R1</td><td>Right Bottom</td><td>R1</td><td>R</td></tr><tr><td>Left Analog UP</td><td>Left Analog UP</td><td>Left Analog UP</td><td>Left Analog UP</td></tr><tr><td>Left Analog Left</td><td>Left Analog Left</td><td>Left Analog Left</td><td>Left Analog Left</td></tr><tr><td>Right Analog UP</td><td>Right Analog UP</td><td>Right Analog UP</td><td>Right Analog UP</td></tr><tr><td>Right Analog Left</td><td>Right Analog Left</td><td>Right Analog Left</td><td>Right Analog Left</td></tr><tr><td>L2</td><td>Left Top</td><td>L2</td><td>ZL</td></tr><tr><td>R2</td><td>Right Top</td><td>R2</td><td>ZR</td></tr><tr><td>L3</td><td>Left Thumb</td><td>Left Thumb</td><td>Left Thumb</td></tr><tr><td>R3</td><td>Right Thumb</td><td>Right Thumb</td><td>Right Thumb</td></tr></tbody></table>

## Per-Game Controller Configuration

If, for any reason, the default controller configuration does not work for you or if you want to tweak your system, there is a possibility to deactivate controller autoconfiguration and to manage controller configuration directly in the emulator/core itself.

Autoconfiguration can be disabled globally, per system or per game.

### **Global deactivation**

Open the [Main Menu](../navigation/main-menu.md) and go to **GAME SETTINGS.**

<div align="left">

<figure><img src="https://i.imgur.com/LL6eTfL.png" alt=""><figcaption></figcaption></figure>

</div>

Disable **AUTOCONFIGURE CONTROLLERS.**

<div align="left">

<figure><img src="https://i.imgur.com/USc60bs.png" alt=""><figcaption></figcaption></figure>

</div>

### **Per system d**eactivation

Open the [System View Options](../navigation/view-options.md) and go to **ADVANCED SYSTEM OPTIONS.**

<div align="left">

<figure><img src="https://i.imgur.com/OwqDv4H.png" alt=""><figcaption></figcaption></figure>

</div>

Then set **AUTOCONFIGURE CONTROLLERS** to **OFF.**

<div align="left">

<figure><img src="https://i.imgur.com/DnYtGMf.png" alt=""><figcaption></figcaption></figure>

</div>

### **Per Game d**eactivation

Open the [Game Options](../navigation/game-options.md) menu and go to **ADVANCED GAME OPTIONS.**

<div align="left">

<figure><img src="https://i.imgur.com/tUJldiK.png" alt=""><figcaption></figcaption></figure>

</div>

Set **AUTOCONFIGURE CONTROLLERS** to **OFF**

<div align="left">

<figure><img src="https://i.imgur.com/b6Z10Rc.png" alt=""><figcaption></figcaption></figure>

</div>

{% hint style="warning" %}
With AUTOCONFIGURE CONTROLLERS set to OFF, you need to configure your controllers directly in the Emulator.

To access the Emulator, you can go in the Retrobat System in the System View.

For RetroArch cores, you can create your own Game Controller mapping for the game by pressing F1 (hotkey + ![B](<../.gitbook/assets/image (4) (1).png>)) during game emulation and changing the controller configuration.
{% endhint %}

## Fixing controller configuration issues

In case of issue with controls, follow the steps below:&#x20;

1. Try to reconfigure your controller mapping
2. Use the [Batgui ](../advanced-features/batgui.md#change-sdl-library-version-and-reset-controller-configuration)tool to reset the controller configuration
3. Use the [batgui ](../advanced-features/batgui.md#change-sdl-library-version-and-reset-controller-configuration)tool to try different SDL version
4. Contact the RetroBat team
