[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# WebPrBoom

WebPrBoom is a fork of the excellent [WebDOOM](https://github.com/UstymUkhman/webDOOM) WebAssembly port of [PrBoom](http://prboom.sourceforge.net/) that was originally developed by [UstymUkhman](https://github.com/UstymUkhman).

The original goal of WebPrBoom was to provide a version of PrBoom that is compatible with the Xbox One (series X/S) browser. Currently, WebPrBoom works well for most devices (including Xbox One) that support WebAssembly and have a physical input mechanism (gamepad, mouse/keyboard, etc.).

## Play

To play WebPrBoom, use one of the following URLs (GitHub is more reliable)

[http://webprboom.com](http://webprboom.com) 
or
[https://raz0red.github.io/webprboom](https://raz0red.github.io/webprboom) 


#### Gameplay Video (Xbox Series X Web Browser)

<a href='http://www.youtube.com/watch?feature=player_embedded&v=FrfQZ2PJ33M' target='_blank'><img src='https://github.com/raz0red/webprboom/raw/master/webprboom.png' width='455' height='343' /></a>

Click the image above to view the gameplay video.

## Features

* Menu to select game to play
* Includes Doom 1 (Shareware), [Freedoom 1](https://freedoom.github.io/), and [Freedoom 2](https://freedoom.github.io/)
* Other PrBoom compatible games can be added via custom builds (Doom 2, etc.)
* Gamepad support for menu and games
* Keyboard/mouse support for menu and games
* Save/load game support (persisted in browser storage)
* Configuration persistence (in browser storage)
* Pointer lock support (for mouse input)

## Gamepad Controls

The following controls are described using the Xbox One controller. 

Equivalent controls for other controller types (PS4, Switch, etc.) should also be compatible.

|Name|Controls|Description|
|-|-|-|
|Move|`D-Pad` or<br> `Left-Analog-Stick` &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | Player moves |
|Run|`X Button`| Player runs | 
|Fire|`A Button`| Fire weapon | 
|Strafe|`B Button`| Strafe when moving left and right | 
|Use|`Y Button`| Opens doors, etc. | 
|Previous Weapon|`Left Shoulder`| Select the previous weapon |
|Next Weapon|`Right Shoulder`| Select the next weapon |
|Show Menu|`Left Trigger` +<br>`Right Trigger` +<br>`Click Left Analog Stick`|**3 button combo**<br><br>This three button combo is required due to the Xbox One reserving the `Screen` and `Menu` buttons for browser-specific controls.<br><br>To enter the menu, hold down the left and right trigger buttons and click (press down) on the left analog stick.|
|Full screen Toggle|`View Button`<br>(Previously back button)|**Xbox One Only**<br><br>This button toggles between full screen and browser (containing the address bar, etc.) modes.|
|Controls Menu|`Menu Button`<br>(Previously start button)|**Xbox One Only**<br><br>Displays a menu that allows for choosing between "browsing" and "game" controls.|

When presented with a Yes/No prompt, the `A button` corresponds to *Yes* and the `B button` to *No*.

