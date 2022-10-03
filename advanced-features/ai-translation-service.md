# AI Translation Service

## Translation Service settings

This function can be used to translate screens from games that are written in a language you do not read in to your native language (e.g. Japanese to English).

Configuration can be done in the [Main Menu ](../navigation/main-menu.md)under **GAME SETTINGS** and **AI GAME TRANSLATION**.

<figure><img src="https://i.imgur.com/9PkHi7R.png" alt=""><figcaption><p>GAME SETTINGS</p></figcaption></figure>

<figure><img src="https://i.imgur.com/wQswVu7.png" alt=""><figcaption><p>AI GAME TRANSLATION</p></figcaption></figure>

<figure><img src="https://i.imgur.com/GD7f7Ay.png" alt=""><figcaption><p>AI GAME TRANSLATION options</p></figcaption></figure>

| Configuration Item                | Description                                                                                          |
| --------------------------------- | ---------------------------------------------------------------------------------------------------- |
| **Enable AI Translation Service** | Turn the translation feature ON or OFF                                                               |
| **Target Language**               | Select the language you want to get the screens translated into                                      |
| **AI Translation service URL**    | Enter the translation service URL                                                                    |
| **Pause on translated screen**    | Select whether you want to keep the game going while the translation overlay is on or pause the game |

### Translation Service URL

The service from [ztranslate.net](https://ztranslate.net/) can be used to translate games.

You will need to register on the website.

<figure><img src="https://i.imgur.com/rLddOm8.png" alt=""><figcaption><p>Register</p></figcaption></figure>

Once the Sign up finalized, go to Settings and retrieve you API key.

<figure><img src="https://i.imgur.com/7Oe139R.png" alt=""><figcaption><p>Retrieve API key at the bottom</p></figcaption></figure>

Now, enter the URL + API key in Retrobat AI GAME TRANSLATION settings and confirm.

Use the following format:

```
http://ztranslate.net/service?api_key=XXXYYYZZZ
```

(replace XXXYYYZZZ with your own API key)

<figure><img src="https://i.imgur.com/OiGEpQD.png" alt=""><figcaption></figcaption></figure>

## Calling the translation while in game

You can now call the AI translation service in-game by using the `HOTKEY` + `R1` combination.
