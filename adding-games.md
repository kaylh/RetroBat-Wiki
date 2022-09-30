---
description: Building your library
---

# Adding games

Adding games in Retrobat is a straight-forward process.

Game ROMs need to be placed in the `\roms\<system>\` folder, they will be directly detected by Retrobat and added to the library when starting Retrobat or when updating the Game List.

## Adding a ROM

<figure><img src="https://i.imgur.com/ayxotgu.png" alt=""><figcaption><p>Adding a snes rom</p></figcaption></figure>

{% hint style="info" %}
For more information about the ROM format per system, refer to the [Supported Games Systems](supported-game-systems/) of the wiki.
{% endhint %}

The System will be visible upon restart of Retrobat

<figure><img src="https://i.imgur.com/8yZ6Dll.png" alt=""><figcaption><p>System View - Super Nintendo system appeared</p></figcaption></figure>

and the game will be visible in the Game View

<figure><img src="https://i.imgur.com/pvbhxaB.png" alt=""><figcaption><p>Game View</p></figcaption></figure>

## Scraping Game Information

The next step is to scrape game information, your game library will look better with game media and information.

Scraping can be done individually per game, per system or globally.

### Global Scraping

Press **START** on the controller (**ENTER** on keyboard) to display the **Main Menu** and choose **SCRAPER**

<figure><img src="https://i.imgur.com/sentTnp.png" alt=""><figcaption><p>SCRAPER</p></figcaption></figure>

Define **SCRAPER SETTINGS** and select **SCRAPE NOW**:

<figure><img src="https://i.imgur.com/7k0IPHA.png" alt=""><figcaption><p>Choose settings and scrape</p></figcaption></figure>

{% hint style="info" %}
To use ScreenScraper, you will need to create an account on the [Screenscraper ](https://www.screenscraper.fr/)website.&#x20;

Then you will have to enter your credentials (User/Password) in the **SCRAPER SETTINGS** menu.

More details in the dedicated [Scaping & Metadata](advanced-features/scraping-and-metadata.md) section of the wiki.
{% endhint %}

The following message will appear on the top right of the screen, this means that the scraping is in progress

<figure><img src="https://i.imgur.com/7WXE0GL.png" alt=""><figcaption><p>Scraping in progress</p></figcaption></figure>

Once the scraping finalized, refresh the gamelist.

Press **START** on the controller (**ENTER** on keyboard) to display the [Main menu](navigation/main-menu.md) and select **GAME SETTINGS**

<figure><img src="https://i.imgur.com/X1sumBQ.png" alt=""><figcaption></figcaption></figure>

Choose **UPDATE GAMELIST**

<figure><img src="https://i.imgur.com/B9beKo6.png" alt=""><figcaption></figcaption></figure>

Game information will now be available in the [Game View](navigation/system-view-and-game-view.md#game-view)

<figure><img src="https://i.imgur.com/hJOODzs.png" alt=""><figcaption><p>Game information has been added to the database</p></figcaption></figure>

### Per game scraping

In order to scrape only a single game, select the game and long-press ![](<.gitbook/assets/image (1) (2) (1).png>) to open the [game options](navigation/game-options.md).&#x20;

Select **SCRAPE**

<figure><img src="https://i.imgur.com/gjGEejQ.png" alt=""><figcaption><p>From the game view, highlight a game and long-press SOUTH button</p></figcaption></figure>

A list of possible match will be displayed, select the appropriate game and confirm with ![](<.gitbook/assets/image (1) (2) (1).png>)

{% hint style="info" %}
The default search string will be based on the ROM filename, to change the search string use the **INPUT** button at the bottom of the screen.
{% endhint %}

<figure><img src="https://i.imgur.com/iwdzJqF.png" alt=""><figcaption><p>Select the right game or press INPUT to enter the game name manually</p></figcaption></figure>

CONGRATULATIONS : you have added your first games to the library !
