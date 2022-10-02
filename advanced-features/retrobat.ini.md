# retrobat.ini

The `retrobat.ini` file located in the root Retrobat folder can be modified to enable or disable some Retrobat features.

{% hint style="info" %}
These features can also be modified in the BATGUI tool, refer to the [BATGUI ](batgui.md)section of the wiki.
{% endhint %}

This is the list of options that can be modified in the "retrobat.ini" file:

| Setting                                                                    | Values                                                                                  | Description                                                                                     |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| LanguageDetection                                                          | 0 (disabled) / 1 (enabled)                                                              | Automatically detect Operating System language                                                  |
| ResetConfigMode                                                            | 0 (disabled) / 1 (enabled)                                                              | Reset the default config files options of the emulators at startup.                             |
| Autostart                                                                  | 0 (disabled) / 1 (enabled)                                                              | Autostart Retrobat at Windows startup                                                           |
| [WiimoteGun](../controllers/supported-controllers/lightguns/wiimotegun.md) | 0 (disabled) / 1 (enabled)                                                              | Run WiimoteGun at RetroBat's startup.                                                           |
| EnableIntro                                                                | 0 (disabled) / 1 (enabled)                                                              | Enable intro video.                                                                             |
| FileName                                                                   | name of the video file between " "                                                      | Define the video file to play at startup.                                                       |
| FilePath                                                                   | <p>Path between " " <br>Default = "default"</p>                                         | Sse a custom directory for video files.                                                         |
| RandomVideo                                                                | 0 (disabled) / 1 (enabled)                                                              | Play a random video from the path selected.                                                     |
| VideoDuration                                                              | <p>duration in miliseconds.<br>Default = 6500</p>                                       | Duration of the intro video                                                                     |
| Fullscreen                                                                 | 0 (disabled) / 1 (enabled)                                                              | Start Retrobat in fullscreen or windowed mode                                                   |
| ForceFullscreenRes                                                         | 0 (disabled) / 1 (enabled)                                                              | Force the fullscreen resolution with the parameters set at WindowXSize and WindowYSize.         |
| GameListOnly                                                               | 0 (disabled) / 1 (enabled)                                                              | Retrobat will parse only the gamelist.xml files in roms directories to display available games. |
| InterfaceMode                                                              | <p>0 = normal<br><a href="kiosk-and-kid-mode.md">1 = kiosk mode<br>2 = kid mode</a></p> |                                                                                                 |
| MonitorIndex                                                               | Default = 0                                                                             | Set to which monitor index the frontend will be displayed.                                      |
| NoExitMenu                                                                 | 0 (disabled) / 1 (enabled)                                                              | Set if the option to quit the frontend is displayed or not when the full menu is enabled.       |
| <p>WindowXSize<br>WindowYSize</p>                                          |                                                                                         | Set the windows width and height of the frontend.                                               |
