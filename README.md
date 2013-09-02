GO:VIP
=====

 **[CS:GO] VIP Mode - GO:VIP** is a simple VIP mode for Counter-Strike: Global Offensive. At the beginning of each round, a random Counter-Terrorist will become the VIP. It is up to the rest of the Counter-Terrorists to escort the VIP safely to one of the rescue zones on the map. It is up to the Terrorists to kill the VIP before he is able to escape. The VIP is equipped with only a pistol with limited ammo and a knife.

#### DISCLAIMER
Originally created by <a href="https://github.com/KyleSanderson">KyleS</a> for CSS and ported by <a href="https://github.com/AnthonyIacono">pimpinjuice</a> to CS:GO, published in <a href="http://alliedmods.net">alliedmods.net</a> in February 2012, last update was eight months later, old post <a href="http://forums.alliedmods.net/showthread.php?t=188953">here</a>, old github project <a href="https://github.com/AnthonyIacono/GOVIP">here</a>.
Since there is no activity from them and I had <a href="https://github.com/AnthonyIacono/GOVIP/issues/1">no reply</a> in order to keep their project alive, I've decided to publish current development branch as a new project, giving them proper credits.

## INSTALLATION
0. Install required extension: http://users.alliedmods.net/~psychon.../sdkhooks/2.2/
1. Copy **addons**, **maps**, **materials** and **sound** folders into your csgo folder.
2. Restart your server.
3. Change map to **as_vertigo**.

## INSTRUCTIONS
This plugin will **only** activate when playing maps which have its rescue zones configured in **addons/sourcemod/configs/rescue_zones.cfg**

## FEATURES
* English and Spanish translation files (Post an <a href="https://github.com/Theadd/govip/issues">issue</a> to contribute with translations).
* Includes custom <a href="https://github.com/Theadd/govip/tree/master/sound/govip">sounds</a>.
* VIP player is painted green.
* VIP player gets additional cash when rescued.
* Included **VIP maps** by default: <a href="http://csgo.gamebanana.com/maps/175986">as_vertigo</a>.

## ADDITIONAL MAPS
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

## CHANGELOG
**02-Sep-2013**
* Fixed vip\_vertigo, renamed to as_vertigo and added custom "VIP RESCUE ZONE" decals.
* Added as_vertigo as the included default map in plugin downloads.

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

## CREDITS
* pimpinjuice

**Original credits from <a href="http://forums.alliedmods.net/showthread.php?t=188953">pimpinjuice post</a>:**
* KyleS - His CS:S VIP plugin.
* psychonic - Awesome SDK Hooks support!
* SM Devs - Quick CS:GO support!
* Dr!fter - Helpful as always.

## KNOWN GO:VIP SERVERS
* <a href="http://www.gametracker.com/server_info/37.187.9.5:27015/">[ESP] Tick128 + MODS: VIP+ZOMBIE+GG [FreeADMIN+FastDL]</a>
    
    Server used to test/develop this plugin. Server default language is spanish so it will use the spanish translation files for the plugin chat messages. Use "!nominate" > as_vertigo and "!rtv" to play VIP mod or email me your SteamID to get admin rights.

## LINKS
* <a href="https://github.com/Theadd/govip">GITHUB Project</a>
* Alliedmods forum post (WIP)
* <a href="https://github.com/Theadd/govip/issues">Submit bugs and suggestions</a>
* <a href="https://github.com/Theadd/govip/archive/master.zip">Download</a>

