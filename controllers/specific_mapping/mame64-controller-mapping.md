# MAME64 controller mapping

MAME64 emulator is compatible natively with XInput controllers.

When using another type of controllers (or to simply use a specific mapping for a game), it is possible to perform a dedicated mapping within the emulator.

## STEP 1 : Create controller mapping file in MAME

Run _mame.exe_, the executable is located in the `emulators\mame` folder of your RetroBat installation.

Click on "General Settings":

<figure><img src="https://i.imgur.com/7FfrAyr.png" alt=""><figcaption></figcaption></figure>

Select "Input Assignments"

<figure><img src="https://i.imgur.com/P23EUU1.png" alt=""><figcaption></figcaption></figure>

Select the controls you want to assign:

* User Interface section lets you map buttons to actions in the MAME Menu
* Player X Controls allows you to map in-game controls

<figure><img src="https://i.imgur.com/pgXcIQM.png" alt=""><figcaption></figcaption></figure>

Map controls as you would like them:

<figure><img src="https://i.imgur.com/kxVLMtw.png" alt=""><figcaption></figcaption></figure>

When using left and right buttons (or keys), you can select whether to add a key to the same button or whether to reset the mapping for the control.

<figure><img src="https://i.imgur.com/ubjsXry.png" alt=""><figcaption><p>You can APPEND</p></figcaption></figure>

<figure><img src="https://i.imgur.com/6pGoFrF.png" alt=""><figcaption><p>Are clear and reset</p></figcaption></figure>

Once the mapping done, go back and click on "Save Settings":

<figure><img src="https://i.imgur.com/pDLsvFJ.png" alt=""><figcaption></figcaption></figure>

A file name "default.cfg" has been saved in the `\emulators\mame\cfg` folder.

<figure><img src="https://i.imgur.com/PmZJO4I.png" alt=""><figcaption></figcaption></figure>



## STEP 2 : Manage the cfg file

Open the default.cfg file and check the content:

<figure><img src="https://i.imgur.com/tYgSbfM.png" alt=""><figcaption></figcaption></figure>

The file has an xml format, the mapping that you have performed is located in the \<input> section of the file.

_In the example, the keyboard key "Q" has been assigned to the action "UI\_MENU" that opens the MAME menu._

Rename the file to one of the following values:

* custom1.cfg
* custom2.cfg
* custom3.cfg
* custom4.cfg

Move the file in the `\saves\mame\ctrlr` folder of your RetroBat installation:

<figure><img src="https://i.imgur.com/15wt2XH.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
You can also perform the mapping directly in the cfg file if you feel comfortable with xml document processing.

Additional information on the file structure can be found here:

[http://mirrors.arcadecontrols.com/easyemu/mameguidenew/mameguide-controlini.htm](http://mirrors.arcadecontrols.com/easyemu/mameguidenew/mameguide-controlini.htm)

[https://docs.mamedev.org/advanced/ctrlr\_config.html](https://docs.mamedev.org/advanced/ctrlr\_config.html)
{% endhint %}

## STEP 3 : Select the controller profile in RetroBat

From the MAME [Game view](../../navigation/system-view-and-game-view.md#game-view), press SELECT to open the [View Options](../../navigation/view-options.md) menu and select "ADVANCED SYSTEM OPTIONS"

<figure><img src="https://i.imgur.com/Y3mGW33.png" alt=""><figcaption></figcaption></figure>

Ensure the MAME64 emulator is set as EMULATOR and navigate to the CONTROLS submenu:

<figure><img src="https://i.imgur.com/3xCkZOg.png" alt=""><figcaption></figcaption></figure>

Select the "CONTROLLER PROFILE" option and choose the profile used for the file that you have created:

{% hint style="info" %}
RetroBat provides 4 custom profiles as well as the ability to use a per\_game cfg file.

When using "per\_game", the name of the file must match the name of the game file (without extension), for example name the file "wjammers.cfg" for the game file "wjammers.zip" (WindJammers).
{% endhint %}

<figure><img src="https://i.imgur.com/ltkfOQt.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Do not hesitate to share the files you have created with the RetroBat team if you have a general profile that can be shared with other users.
{% endhint %}
