<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="readme/bd_logo.jpg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">BetterDiscord Pack</h3>
</div>

<!-- ABOUT THE PROJECT -->
## About

[![Product Name Screen Shot][product-screenshot]](https://i.imgur.com/d7qDvEQ.png)

BetterDiscord pack with custom css, plugins & themes. Everything is editable and customisable to your liking.

<!-- GETTING STARTED -->
### Prerequisites

First you should download and install the official BetterDiscord client. [Download](https://betterdiscord.app/)

### Installation

1. [Download](https://github.com/Lund1337/betterdiscord/archive/refs/heads/main.zip) the repo.
2. Open the .zip file and open the next folder.
3. Extract only the 'betterdiscord' folder from there.
4. Drag and Drop the 'betterdiscord' folder into 'C:\Users\USER*\AppData\Roaming' or where your default betterdiscord client is installed.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Everything is drag and drop, after that just reload Discord 'CTRL+R'.

_If you wish to edit something, check the betterdiscord settings from discord client settings._

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- things -->
## Custom CSS Plugins and Themes

### Custom CSS

1. Custom Home Button:
```sh
.homeIcon-r0w4ny {
    display: none;
}

.tutorialContainer-1pL9QS .wrapper-3kah-n .childWrapper-1j_1ub {
    background-color: transparent;
}

.tutorialContainer-1pL9QS .wrapper-3kah-n .childWrapper-1j_1ub:before {
    position: absolute;
    content: " ";
    width: 45px; /* Change size if needed */
    height: 45px; /* Change size if needed */
    background-image: url('https://i.imgur.com/eP9MkwW.png'); /* Replace the link, with your image link */
    background-size: contain;
}
  ```

2. Custom Discord Font:
```sh
html, body {
  font-family: 'Roboto Condensed', monospace; /* --== Use a Google Font (https://fonts.google.com/) ==-- */
}
  ```
3. Mini Search Bar:
```sh
:root {
    --transitionspeed: 0.25s;
}

.search-2Mwzzq:not(.open-1F8u2c) .searchBar-jGtisZ {width: 27px; transition: var(--transitionspeed); background-color: transparent;}
.search-2Mwzzq:not(.open-1F8u2c):hover .searchBar-jGtisZ {width: 170px; background-color: var(--background-tertiary);}
.search-2Mwzzq:not(.open-1F8u2c) .iconContainer-1RqWJj {transform: scale(1.3); transition: var(--transitionspeed);}
.search-2Mwzzq:not(.open-1F8u2c):hover .iconContainer-1RqWJj {transform: scale(1);}
.search-2Mwzzq:not(.open-1F8u2c) .icon-18rqoe {color: var(--text-normal);}
.search-2Mwzzq:not(.open-1F8u2c):hover .icon-18rqoe {color: var(--text-muted);}
  ```
4. Custom Background Image: 
```sh
:root {
    --background-image: url('https://i.imgur.com/WC0aEqH.jpg'); /*Change the link to your custom image*/
    --opacity: .95;
}

:root {background:var(--background-image) center/cover no-repeat;opacity:var(--opacity)}
 ```
5. AboutMe Scroll Bar:
```sh
.clamped-2ZePhX{
    -webkit-line-clamp: 190; /*Maximum amount of characters as new lines, unset just breaks links*/
    max-height:112px;
    overflow-x: hidden;
    overflow-y:scroll;
}
.clamped-2ZePhX::-webkit-scrollbar {
  width: 10px;
  height: 15px;
}
.clamped-2ZePhX::-webkit-scrollbar-track {
  border-radius: 10px; /*How round you want the scrollbar to be. 0 is square, 10px is round.*/
  background-color: rgb(255 255 255 / 10%); /*Edit this to what color you want the track to be.*/
}
.clamped-2ZePhX::-webkit-scrollbar-thumb {
  background: linear-gradient(45deg, #d3d3d3, #808080); /* Edit this to whatever color/colors you'd like*/
  border-radius: 10px; /*How round you want the scrollbar thumb to be. 0 is square, 10px is round.*/
}
 ```
6. Rounded Menus:
```sh
.menu-1QACrS, .colorDefault-CDqZdO { 
    border-radius: 15px; 
}
 ```
7. Compact Channels:
```sh
:root {
    --category-spacing: 0px;
    --channel-spacing: 4px;
}

.containerDefault-3TQ5YN, .containerDragAfter-1J_-1V, .containerDragBefore-ei4h1m, .containerUserOver-3woq86 {
    padding-top: var(--category-spacing);
}

.mainContent-20q_Hp {
    padding: var(--channel-spacing);
}
 ```

### Plugins

### Themes

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[product-screenshot]: readme/screenshot.png
