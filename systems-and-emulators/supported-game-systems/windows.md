---
description: Microsoft
---

# Windows

<figure><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/5149a33eed46b2af638b06119397d4023b75131f/art/logos/windows.svg" alt=""><figcaption></figcaption></figure>

Computer Operating System - Lifespan: 1992 - now

{% embed url="https://en.wikipedia.org/wiki/Microsoft_Windows" %}

## Information

Windows games do not use any emulator to function, RetroBat enables to launch Windows games from its interface.



| **File folder**    | :open\_file\_folder: roms \ :open\_file\_folder: windows                  |
| ------------------ | ------------------------------------------------------------------------- |
| **File extension** | .exe .bat .cmd .lnk .url .pc .win .windows .wine .7z .zip .rar .wsquashfs |

## Controls

No automatic controller configuration is performed for Windows games.

## Specific system information

### Adding games

Right click and select "_copy_" on the executable (\*.exe) of your PC games, and make "_paste shortcuts_" in folder `\roms\windows`

<figure><img src="https://i.imgur.com/47WNq9D.png" alt=""><figcaption><p>Project CARS shortcut</p></figcaption></figure>



### Adding Steam games

{% hint style="info" %}
The BATGUI tool offers a simplified procedure for adding Steam games, refer to the [BATGUI ](../../advanced-features/batgui.md)section of the wiki.
{% endhint %}

Create a .bat file with a scrapable name for your game.

You have 2 possibilities, quit Steam at the end of each game or not, both work since it seems that emulationstation is waiting on the end of the execution of the script to reactivate.

The solution without switching off Steam launches the games faster since the connection step is no longer to be done once launched for the first time or if Steam is launched when Windows starts.

This is code of your .bat file **with Steam kill**:

<pre class="language-batch"><code class="lang-batch"><strong>@echo OFF
</strong>
REM HERE MODIFY YOUR STEAM APPID:
START steam://rungameid/000000

TIMEOUT /t 30
:RUNNING

REM HERE YOU MUST ENTER THE RIGHT NAME OF THE EXECUTABLE, FOR EXAMPLE: "MyGame.exe"
tasklist|findstr "Mygame.exe" > nul

if %errorlevel%==1 timeout /t 5 &#x26; taskkill /F /IM Steam.exe /T &#x26; GOTO ENDLOOP</code></pre>

This is code of your .bat file **without Steam kill**:

```batch
@echo OFF

REM HERE MODIFY YOUR STEAM APPID:
START steam://rungameid/000000

TIMEOUT /t 30
:RUNNING

REM HERE YOU MUST ENTER THE RIGHT NAME OF THE EXECUTABLE, FOR EXAMPLE: "MyGame.exe"
tasklist|findstr "Mygame.exe" > nul

if %errorlevel%==1 timeout /t 5 & GOTO ENDLOOP
```

**All you need is to inquire Steam game ID and executable name, proceed as follows:**

Open steam then check "Activate Steam address bar when available", also make sure that Steam does not start in big picture mode.

<figure><img src="https://i.imgur.com/oQssKE7.png" alt=""><figcaption></figcaption></figure>

You will then find your game id at the top left in the address bar, from the store page.

<figure><img src="https://i.imgur.com/Po6FSrn.png" alt=""><figcaption></figcaption></figure>

Alternatively, you can find the full "start" command in the properties of a Steam game shortcut:

<figure><img src="https://i.imgur.com/90ZcRdF.png" alt=""><figcaption></figcaption></figure>

Then find the game executable as follows:

<figure><img src="https://i.imgur.com/CCVHbSs.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://i.imgur.com/CBLOJwn.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Alternatively you could run the game and open the task manager to find the executable name.
{% endhint %}

Finally, report these two pieces of information in your.bat file as follows:

<figure><img src="https://i.imgur.com/CHGYrxn.png" alt=""><figcaption></figcaption></figure>
