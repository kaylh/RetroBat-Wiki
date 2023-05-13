# Know issues & fixes

This section is constantly updated with official fixes provided by the Team for specific issues raised by users in our official support channels.

## Clean es\_input file

If your controller settings become messed-up and you need a clean start, here is a `es_input.cfg` file that you can copy in your `retrobat\emulationstation\.emulationstation` folder.

It contains only standard keyboard settings, you will have to perform again your controller configuration.

{% file src="../.gitbook/assets/es_input.cfg" %}

## Ryujinx automatic controller configuration breaking config file

Since version 1.695 of Ryujinx, the way RetroBat generates controller configuration breaks the configuration file of Ryujinx.

In order to prevent this from happening, you can either disable controller autoconfiguration if you do not need it, or you can unzip the following file in your `retrobat\emulationstation` folder:

{% file src="../.gitbook/assets/EmulationStation.zip" %}

## BigPEmu chain error message

If you get a message like that when running BigPEmu from RetroBat:

<div align="left">

<figure><img src="https://i.imgur.com/YBpU8yk.png" alt=""><figcaption></figcaption></figure>

</div>

Just delete the _**BigPEmuConfig.bigpcfg**_ file located in the `\emulators\bigpemu\userdata` folder of your RetroBat installation.

## Mame artwork not select in saves\mame\artwork path

You can either place your artworks in `retrobat\emulators\mame\artwork` folder, or you can unzip the following file in your `retrobat\emulationstation` folder:

{% file src="../.gitbook/assets/EmulationStation.zip" %}

## Cannonball in a second "Ports" system

Open the file **es\_systems.cfg** located in `retrobat\emulationstation\.emulationstation` folder and find the Cannonball session, than change the `<theme>ports</theme>` value to `<theme>cannonball</theme>`:

<div align="left">

<figure><img src="https://i.imgur.com/EiKMiME.png" alt=""><figcaption></figcaption></figure>

</div>

## Wii bezels not working when in 4/3

Unzip the following file in your `retrobat\emulationstation` folder:

{% file src="../.gitbook/assets/EmulationStation.zip" %}

## FBNEO: patched rom setting preventing the use of Retroachievements Hardcore mode

Unzip the following file in your `retrobat\emulationstation` folder:

{% file src="../.gitbook/assets/EmulationStation.zip" %}
