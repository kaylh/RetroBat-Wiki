# Scraping & Metadata

Scraping is used for downloading metadata and media files (images, videos, maps, pad-to-key settings and manuals) for games in your collection.

Retrobat supports 4 scraping services:

* ScreenScraper (default service) : credentials are required ([screenscraper website](https://www.screenscraper.fr/))
* [TheGamesDB](https://thegamesdb.net/)
* [HFSDB](https://db.hfsplay.fr/)
* ArcadeDB

### **Information that can be scraped**

* Game information (title, year, number of players, description...)
* Ratings
* Thumb (box)
* Marquee / Wheel
* Video
* Fanart
* Image (title screen or in-game screenshot)
* Box backside
* Map
* Manual
* Pad-to-key settings

### Scraping process

There are two approaches to scraping, either for a single game from the [Game Options](../navigation/game-options.md), or for multiple games and systems (global scraping) from the [Main Menu](../navigation/main-menu.md).

#### Global scraping

Refer to the [following part of the wiki](../get-started/adding-a-game.md#global-scraping) for instructions.

#### Per Game scraping

Refer to the[ following section of the wiki](../get-started/adding-a-game.md#per-game-scraping) for instructions.



### Scraping options

Scraping options are available from the [Main Menu](../navigation/main-menu.md).

<figure><img src="https://i.imgur.com/NBYGcPe.png" alt=""><figcaption></figcaption></figure>

Before running the scraper you can:

* Select the scraper to use
* Limit the scraper to only games missing all medias or games missing any media
* Ignore games scraped recently
* Include/exclude systems

Additionaly, each scraper has its own settings.

<figure><img src="https://i.imgur.com/wjGjPxy.png" alt=""><figcaption><p>Example of available settings for ScreenScraper</p></figcaption></figure>

From here you can select which data to scrape, but also define:

* What image to use as "image" file
* What image to use as "thumb" image
* What image to use as logo (marquee or wheel)

{% hint style="info" %}
The Scraper settings is also where you can enter your credentials for ScreenScaper service.
{% endhint %}

### Storage of scraped medias

All scraped medias will be stored in the rom folder.

<figure><img src="https://i.imgur.com/XlUVX8L.png" alt=""><figcaption><p>Example of media folders</p></figcaption></figure>

| Folder  | Media stored                                      |
| ------- | ------------------------------------------------- |
| images  | box (thumb), fanart, boxback, image, marquee, map |
| manuals | pdf manual                                        |
| videos  | mp4 videos                                        |

### Manual modification of Game Metadata

The [Game Option](../navigation/game-options.md) menu offers the possibility to manually edit/complete metadata for a game

<figure><img src="https://i.imgur.com/80l5jWw.png" alt=""><figcaption></figcaption></figure>

**From there you can:**

* Update Game information (name, description, rating, release date, developer, publisher, family, genres, arcade system, number of players, languages and region)
* Attach different media files
* Add game to favorites
* Hide game
* Flag game as KID game to display it in the [Kid Mode](kiosk-and-kid-mode.md#kid-mode)
