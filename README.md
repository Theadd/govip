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
**20-Aug-2013**
* Added vip_vertigo map as additional map.
* Completed translation files for english and spanish languages.

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
* Added additional cash to VIP player when reaching rescue zone.

## ADDITIONAL MAPS
GO:VIP Specific maps:
### <a href="http://csgo.gamebanana.com/maps/175986">as_vertigo</a>
[![](http://csgo.gamebanana.com/maps/embeddables/175986?type=small)](http://csgo.gamebanana.com/maps/175986)

Rescue zone is in a chopper at terrorists spawn.
##### Add in rescue_zones.cfg:

    "as_vertigo"
    {
    	"Rescue Zone"
    	{
    		"coords" "-1189.88 1495.94 11602.58"
    		"radius" "100"
    	}
    }

=====
The following maps are well suited for playing in VIP Mod mode even not being developed for it.

### <a href="http://csgo.gamebanana.com/maps/169201">ar_nomercy</a>
Rescue zone is a chopper platform near terrorists spawn which can be accessed from several paths
##### Add in rescue_zones.cfg:

    "ar_nomercy"
    {
        "Rescue Zone"
        {
            "coords" "413.607971 -603.788757 380.093811"
            "radius" "150"
        }
    }

### <a href="http://csgo.gamebanana.com/maps/171236">cs_creek</a>
Rescue zone is a chapel near terrorists spawn, this is a big and resource intensive map.
##### Add in rescue_zones.cfg:

    "cs_creek"
    {
    	"Rescue Zone"
    	{
    		"coords" "742.230591 1096.808472 1427.890625"
    		"radius" "100"
    	}
    }

