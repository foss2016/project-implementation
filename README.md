# About 
This is the implementation of our project as part of the FOSS Course


#### A free HTML5 remake of Nintendo's original Super Mario Bros, expanded for the modern web. It includes the original 32 levels, a random map generator, a level editor, and over a dozen custom mods.


## How to Play

It is easy to play your own copy.

Download  this project, extract that onto your computer, and open **index.html** in a browser (preferably Google Chrome). That's it!

#### In your own site

Upload the latest release of FullScreenMario (or your built version) to your FTP server.


## Developing

##### Build Process

FullScreenMario uses [Grunt](http://gruntjs.com/) to automate building, which requires [Node.js](http://node.js.org). The process is straightforward; see [Grunt's help page](http://gruntjs.com/getting-started).

#### Coding

FullScreenMario is built on a modular framework called GameStartr. The [FullScreenShenanigans](https://github.com/FullScreenShenanigans/) organization contains GameStartr, its parent class EightBittr, and the modules used by the GameStartr framework. These all (theoretically) have their own README files, which you should skim before developing for FullScreenMario itself.

All source code is in the [Source](Source/) directory. See [Getting Started.md](Getting Started.md) for an in-depth guide on getting started programming with FullScreenMario.

The FullScreenMario.ts class declaration contains class functions and some constants, while static settings to be added to the FullScreenMario prototype, such as map layouts and object attributes, are stored in files under [Source/settings](Source/settings), such as audio.js and collisions.js.

