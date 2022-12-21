# Know issues & fixes

This section is constantly updated with official fixes provided by the Team for specific issues raised by users in our official support channels.



### SDL fix

Some users have reported strange behaviour of RetroBat with few controllers (Xbox 360 controllers appearing twice, game not launching with specific USB material connected...).

A known fix for these issues is to replace the RetroBat sdl2.dll file (version 2.24) with the more recent 2.26.1 version available here : [https://github.com/libsdl-org/SDL/releases](https://github.com/libsdl-org/SDL/releases)



Download the [SDL2-2.26.1-win32-x86.zip](https://github.com/libsdl-org/SDL/releases/download/release-2.26.1/SDL2-2.26.1-win32-x86.zip) version (or more recent x86 version) and extract the SDL2.dll file into the \emulationstation\ folder of your RetroBat installation.

This will replace the current 2.24 version and might fix some issues.



### Xenia feature licence mask overwritten by RetroBat

The licence mask value gets systematically overwritten by RetroBat, making it impossible to set the value correctly and to play Xbox Live Arcade titles.

This is due to a missing feature that will be corrected in next RetroBat version, in the meantime, you can download the following "es\_features.cfg" file and copy it to the `\emulationstation\.emulationstation\` of your RetroBat installation.

{% file src="../.gitbook/assets/es_features.cfg" %}

This will overwrite the existing es\_features file and bring you the licence mask as a feature in RetroBat:

<figure><img src="https://i.imgur.com/G7TVdhI.png" alt=""><figcaption></figcaption></figure>

