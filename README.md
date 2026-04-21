Ross Craik, 2102628

Computer Games Applications Development



2 Button Control Systems in First-Person Shooter Games





To run this project you must have Unreal Engine 5.6.1 Installed on your device and a controller device to play



Steps to run project:

* Open Unreal Engine 5.6.1
* Open The 'HonorsGame.uproject' solution file in unreal engine
* Open the Content Drawer (Bottom Left) and browse to the Content Folder and then the Varient\_Shooter Folder
* Within the Varient\_Shooter Folder, right click the 'Controller Widget' and select 'Run Editor Utility Widget' near the top
* In the Editor Utility Widget, Click either the 'Control Scheme 1' or 'Control Scheme 2' buttons to select which you would like to use
* Then select the green play button at the top of the screen to play the game in the editor viewport





The Game:

* The game is a first-person shooter game with 2 different weapons and enemy ai bots
* There are weapon pick ups at each possible spawn location, and you must walk over them to pick up the weapon
* There is a Weapon Inventory system to be able to hold both weapons





The Controllers:



Control Scheme 1:

* Left stick - aiming and looking
* Bottom Button on controller (A on Xbox, X on PlayStation) - Moves player to point where user is looking
* Right Button on controller (B on Xbox, Circle on PlayStation):

&#x20;  	- While looking at enemy: Switches to secondary weapon

&#x09;	- If no Secondary is available: reload

&#x09;	- If fully reload: throw grenade



&#x09;- While Not Looking at Enemy: Reloads

&#x09;	- If fully reloaded: throw grenade

&#x09;	- if no grenade available: swap weapon





Control Scheme 2:

* Left stick - Moving (Primary) and Aiming (Secondary)
* Bottom Button on controller (A on Xbox, X on PlayStation) - Hold to Switch Left Stick to control Aiming (will continue moving in previous direction)
* Right Button on controller (B on Xbox, Circle on PlayStation):

&#x20;  	- While looking at enemy: Shoots

&#x09;	- If no Ammo Available: switch weapon

&#x09;	- If no secondary weapon: reloads



&#x09;- While Not Looking at Enemy: Reloads

&#x09;	- If fully reloaded: throw grenade

&#x09;	- if no grenade available: swap weapon













