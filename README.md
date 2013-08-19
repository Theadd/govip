GO:VIP
=====

 [CS:GO] VIP Mode - GO:VIP is a simple VIP mode for Counter-Strike: Global Offensive. At the beginning of each round, a random Counter-Terrorist will become the VIP. It is up to the rest of the Counter-Terrorists to escort the VIP safely to one of the rescue zones on the map. It is up to the Terrorists to kill the VIP before he is able to escape. The VIP is equipped with only a pistol with limited ammo and a knife.

 Based on the old source of CS:GO VIP Mod:
 http://forums.alliedmods.net/showthread.php?t=188953
 
 
## REQUIREMENTS
* SDK Hooks (CS:GO Build): http://users.alliedmods.net/~psychon.../sdkhooks/2.2/

## INSTALLATION
0. Install required extension: http://users.alliedmods.net/~psychon.../sdkhooks/2.2/
1. Copy addons and sound folders into your csgo folder.
2. Restart your server.

## INSTRUCTIONS
This plugin will activate only when playing the maps which have its rescue zones configured in **addons/sourcemod/configs/rescue_zones.cfg**

## CHANGELOG
**19-Aug-2013**
* Added translation files for Spanish language.
* Added custom sounds.
* Fixed a bug where the VIP eventually had no weapons.

**Older**
* VIP model appears in GREEN color
* Prevented game restart after killing VIP or reaching to the rescue zone
* Added some colors on GO:VIP chat messages
* GO:VIP Plugin will only work on maps listed in rescue_zones.cfg (No need to use other plugins such as nextmapmode to enable VIP mod only on VIP maps)
* Prevented "Terrorist Win" after VIP have been rescued and then died.
* Added plugin info (Since there was no info provided)

