# Translations

If you want to help us translate RetroBat in your own language, this page is for you !



## Concepts

RetroBat uses 2 different components for translations: EmulationStation & RetroBat specific features.



### EmulationStation

The EmulationStation part of the translations concerns the main interface of RetroBat, which includes all screens and menus that you see when configuring a joystick, when configuring the system from the main menu (START button) or when configuring core RetroArch core features.

RetroBat shares the same fork of EmulationStation (f.Caruso fork) with Batocera.

In order not to mess up with translation, both project teams have agreed that the translation of core EmulationStation fonctionnalities will be managed by the Batocera project.

You can find all details on how to help here: [https://wiki.batocera.org/help\_with\_translation](https://wiki.batocera.org/help\_with\_translation)



### RetroBat specific features

Though RetroBat & Batocera projects share the same EmulationStation front-end, features and configuration of emulators are totally different between both projects. Which is why there are a huge number of menu items which are specific to each front-end.

The features are generally the ones that you see when pressing the SELECT button and going into a system / game configuration:

<figure><img src="https://i.imgur.com/AKEpfB2.png" alt=""><figcaption><p>Example of missing italian translation for menu items</p></figcaption></figure>

The same way that you can help with EmulationStation translations, you can help us with these features translation.

### Location of translation files

Current status of RetroBat features translations can be found in the following directory of your RetroBat installation: `\system\templates\emulationstation\es_features.locale`

This folder contains:

* An up-to-date template file `es-features-template.po` which contains the full list of strings to be translated
* A subdirectory per language with the current translation files

{% hint style="info" %}
You might notice that some text to be translated exists in the template file but not in the specific language file, this is normal !
{% endhint %}



### How to help us ?

In order to help us translate RetroBat, you will obviously need to select the language that you want to work with.

Once done, take your favorite text editor and open the `es-features.po` file of the language you are working on:

<figure><img src="https://i.imgur.com/JZOBu99.png" alt=""><figcaption><p>In the example above, we have translated "VIDEO MODE" to "MODE VIDÉO" in french language.</p></figcaption></figure>

The original text that needs translation is the one located after **msgid**, the translated text has to be entered after **msgstr**.

{% hint style="warning" %}
Ensure that you always keep the strings between brackets " ", else it will crash RetroBat.
{% endhint %}



### How to add missing texts in an already partially translated file ?

In order to update an existing language file with the new strings to be translated, you need to proceed like this:

* Copy the **es-features.po** file from your language into the following directory of your RetroBat installation : `\emulationstation\.emulationstation\es_features.locale`
* Rename the file to `es-features-template.po`
* Open a cmd window in the `\emulationstation` folder of your RetroBat installation and type the following command line: `emulatorlauncher -updatepo`

<figure><img src="https://i.imgur.com/6DReUC3.png" alt=""><figcaption></figcaption></figure>

You should receive a message that the template has been updated:

<figure><img src="https://i.imgur.com/kBeXrk1.png" alt=""><figcaption></figcaption></figure>

* You can now copy the es-features-template.po file generated in the `\emulationstation\.emulationstation\es_features.locale` folder to the language folder of your language and rename it to **es-features.po** and finalize the translation.

### How to test your translated file ?

Before sharing the translation with the RetroBat team, ensure that the translation is working properly and is not crashing EmulationStation.

To do this, copy the **es-features.po** file in the language folder to test in the `\emulationstation\.emulationstation\es_features.locale` folder of your RetroBat installation.

You can now run RetroBat, switch to the target language, and check all translations.

### How to submit your translated file ?

Once the translation file has been thoroughly tested, you can submit the file to the RetroBat team through our Discord channel or through our forum.

The links can be found at the top of this wiki or on our [website](https://www.retrobat.org).
