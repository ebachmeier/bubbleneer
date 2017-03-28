-=Bubbleneer Readme=-

-=Builds=-
-Our game comes with 2 builds one for mac, and one for windows.
-It is also playable on our website:
http://www.ericbachmeier.com/bubbleneer/

-=Instructions=-
-Instructions on how to play can be viewed on our website under the "Gameplay" tab.

-=Obtaining Map Files=-
-If you can open the Unity project file, you can download additional maps from our website
and place them in the  "Assets/Resources/MapFiles" folder. Next, you will need to add
the name of the map to LevelOrder.txt. Please note that we've already included all of
the available maps we have created in your version of the game.

-=Map Building=-
-You can build your own maps using:
https://thorbjorn.itch.io/tiled

-Use the "bubbleneer exportable tileset" found in "Assets/"bubbleneer Tiled Map Editor data/tilesets".

-Exporting the finished map as a .csv will provide a finished tier of the map, but not the formatting necessary
for our mapbuilder script to understand it and initialize the level. For reference here is a labelled header from
Level_1.txt:

17,17,3 -dimensions of map: x,y,z
2000 - money
300 -points for 3 stars
30,15 -build time,simulation time
-- object codes at y = 0 --
INC -increase the tier being constructed by 1
-- object codes at y = 1 --

-This feature was developed to help design maps faster, and is extremely buggy. Ideally we would completely
replaced by an in-game map builder.

-=Contributions=-
Brandon Allen: Scene Loading, Map Management, Round Management, Money System, and Point System
Eric Bachmeier: Main Menu, and Website
Kirkland Landry: Crab logic, External Tile Editor Set-up, and In-game Music, Level Design
Kartsen Babin: In-game construction tools, In-game UI, Macro Manager, Pause Menu, Main Menu, and Round Over Menu 
Mathias Babin: AI logic (crab/squid/bubbles), Pipe/Ground Management, Map Construction, 3D models, Menu Music, Level Design
