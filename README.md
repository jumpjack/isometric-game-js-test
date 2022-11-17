Isometric game "urban survivor" written for MelonJS engine

Other isometric engines for javascript:
 - http://craftyjs.com/  (https://github.com/craftyjs/Crafty)
 - http://www.isogenicengine.com/ 8https://github.com/Irrelon/ige)
 - https://github.com/bugnano/frigame
 - https://github.com/j03m/trafficcone
 - https://github.com/angrycoding/jgen/tree/master/src
 - https://www.prelude-prod.fr/demo/pp3diso/
 - https://cocos2d-x.org/js-tests/TileMaps/iso-test.tmx
 

![image](https://user-images.githubusercontent.com/1620953/201612641-2b39645b-0e36-45a1-aca3-ff3b6bef131a.png)

Forked from [jkalkhof/urban-survivor-rpg](https://github.com/jkalkhof/urban-survivor-rpg)

[Live demo](https://jumpjack.github.io/isometric-game-js-test/Jerry-isometric-rpg/index.html)

Game is made with **MelonJS**:

- [Main page](https://melonjs.org/)
- [Documentation](https://github.com/melonjs/melonJS)
- [Source code](https://github.com/melonjs/melonJS)
- [Games made with MelonJs](https://itch.io/games/made-with-melonjs)

Game map is made with **Tiled**:
- [Documentation](https://doc.mapeditor.org/en/stable/manual/introduction/)
- [Source code](https://github.com/bjorn/tiled)
- [Download](https://thorbjorn.itch.io/tiled?download)

Tool "Tiled" supports various formats for maps:
- [JSON](https://doc.mapeditor.org/en/stable/reference/json-map-format/)
- XML
- [TMX/TSX](https://doc.mapeditor.org/en/stable/reference/tmx-map-format/) (proprietary format) ([3rd party libraries](https://doc.mapeditor.org/en/stable/reference/support-for-tmx-maps/) in various languages)

------------------

_Original text of readme.txt:_

Urban Survival RPG

copyright 2018 Jerry Kalkhof

This project is based off the html5 game engine melonjs.

## Major features
- isometric map movement
- inventory system
- achievement system

## version 1.0
This version is very basic and only has basic movement of the main character.

Gather items from around the city to reach the 3 achievement goals.

This project was built using the following tools:
- atom - text editor
- tiled - tilemap editor
- TexturePacker - sprite packing tool

CREDITS


This project also used art assets from [OpenGameArt.org](https://opengameart.org):
- [Simerion tiles by Yoann Sculo](https://opengameart.org/content/simerion-tiles-and-images)
- [Jerry City Pack by Jerry Kalkhof](https://opengameart.org/content/jerrycitypack)	
- [SciFi background image by Eris](https://opengameart.org/content/sci-fi-platform-tiles)	
- [UI from Buch](https://opengameart.org/content/golden-ui-bigger-than-ever-edition)	
- [UI pack from Kenny.nl](https://opengameart.org/content/ui-pack)	
- [Player sprite sheet by Knight Yamato](https://www.deviantart.com/knightyamato/art/Blank-Sprite-Sheet-4-2-129192797)	
- [Sound FX by Lokif](https://opengameart.org/content/gui-sound-effects)
	
	
Run Instructions for Windows
1. [install ubuntu - microsoft windows subsystem](https://www.microsoft.com/en-us/p/ubuntu/9nblggh4msv6#activetab=pivot:overviewtab)	
2. use nodejs to install http server
	mkdir node_modules
	sudo npm install http-server -g
3. run http server		
	export PATH=./node_modules/.bin:$PATH
	echo $PATH
	http-server -a localhost -p 8000 -c-1	
4. run app from localhost: [http://localhost:8000/Jerry-isometric-rpg/](http://localhost:8000/Jerry-isometric-rpg/)
	
	
This game can also be [tested live](https://jerryartist.itch.io/urban-survivor) from my itch.io page.

