# 🎮 Gamepads

Any Gamepad that can be detected by Windows should work in Retrobat.

Wired Gamepads are plug'n'play, once the Gamepad connected you should be able to configure it in Retrobat.

Bluetooth Gamepads will first require to be paired with your system so that they are detected by Windows.

{% hint style="info" %}
You can test you Gamepad [HERE](https://gamepad-tester.com/) to check if it is detected in Windows
{% endhint %}

### 8bitdo controllers <a href="#bitdo_controllers" id="bitdo_controllers"></a>

![](<../../.gitbook/assets/image (5) (2).png>)

8bitdo Bluetooth controllers have been reported to work perfectly with Retrobat.

8bitdo Controllers can be set-up in 2 modes : XINPUT or sdl, we recommend using the XINPUT mode for better compability with Windows.

To turn on the XINPUT mode, the controller must be started with `START` + `X` before being paired to the computer. (`START`+ `Y` will enable sdl mode)

{% hint style="info" %}
XINPUT does not support motion control. If you need to use your controller in games requiring motion, it is better to use sdl mode.
{% endhint %}

When using a wired 8bitdo controller, the switch between XInput and sdl is done by maintaining `X` or `Y` button while plugging the USB cable (instead of pressing `START`)

### XBox controllers (or any XInput controller)

![](<../../.gitbook/assets/image (4) (3).png>)![](<../../.gitbook/assets/image (4).png>)

For wired Xbox controllers, the connection to windows and setup in Retrobat will be plug'n'play.

Wireless controllers will also work seamlessly in Retrobat when properly connected to Windows.

All controllers introduced before the Xbox One S (Xbox 360, Xbox One controllers) will require a specific RF dongle to be paired to your computer, as they are not natively Bluetooth compatible.

### Nintendo Switch Pro controller

![](<../../.gitbook/assets/image (2) (2).png>)

The Switch Pro controller will be ideal for use in CEMU (WiiU emulator) or Yuzu (Switch emulator) as it is natively compatible with these emulators and it will support motion control for games that require motion.

However, it has been reported that this controller does not work well with Retrobat interface due to issues with sdl drivers.

{% hint style="info" %}
In order to use best of both worlds, it is possible to use a 3rd party program such as DS4Windows (by Ryochan) to set this controller as XINPUT in Windows and Retrobat and make it visible in CEMU or Yuzu as sdl controller with motion.
{% endhint %}

### Playstation 5 controller (DualSense)

![](<../../.gitbook/assets/image (1) (3).png>)

DualSense controllers supports motion and is reported to work natively with Retrobat, however it will cause issues with some standalone emulators (e.g. Dolphin).

The same tip as explained for the Switch Pro Controller can be used to unlock the full potential of this controller.
