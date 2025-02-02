---
title: Game & Balance Patchnotes 2017
description: 
published: true
date: 2021-09-08T22:23:34.753Z
tags: 
editor: markdown
dateCreated: 2021-09-08T20:45:18.342Z
---

# Complete changelog of all changes in 2016 {.tabset}


## 3695
### Other
- Reverted 3694's changes
- This patch is identical to patch 3693
### Contributors
Ozonex
CookieNoob

## 3694
### Other
- Added christmas-related content, like reclaimable gifts.
- Renamed the Galactic Colossus accordingly
### Contributors
Ozonex
CookieNoob

## 3693
### Lobby
- Fixed the lobby changelog appearing every time
### Contributors
IceDreamer

## 3692
### Shared Armies
- This patch ships with a new, modified exe file that enables the Shared Armies alpha mod. The mod can be found on the vault.
	- To play a game with it, set up your teams such that the topmost slot in the lobby of each team is the army your team will be.
	- On starting the game, control of all team member will be transferred to that army. Coordination between team members is ESSENTIAL
	- This mode will be developed into a fully integrated game mode down the line. It should open up extensive interesting new options for gameplay.

### Gameplay
- Disabled ACU build ability before warp in to stop fast clicks sometimes netting a several-second advantage
- Fixed the Seraphim Sniperbot not working with attack-move in its non-default mode
- Added target bones to Subs to allow them to be attacked by surface units when surfaced
- Added above water target bone to Cybran T1 Torpedo Launcher to allow it to be attacked by surface units, particularly the Seraphim Destroyer
- Fixed the Cybran ACU needing to get into Gun range to attack a specific target with its torpedo upgrade
- Fixed the Cybran ACU not stopping at max range in attack move when firing torpedo

### Bugs
- Fixed units with no faction assignment (From mods usually) breaking the game
- Fixed Percival low detail model not turning its gun properly
- Fixed Seraphim Destroyer not firing its torpedo salvos properly when given orders
- Fixed the Seraphim nuke impact sound calling the wrong sound cue
- Fixed incomplete ships sometimes not being destroyed with their factory
- Fixed Counter-intel turning off intel when power stalling
- Fixed game-breaking bug related to template name cutoff
- Fixed energy consuming weapons draining power before completion
- Added COUNTERINTELLIGENCE to HARMS category list, as it has personal stealth
- Fixed Salem death not animating on land
- Fixed Czar beam not vanishing on death

### UI
- Changed Salvation to be categorized as an experimental instead of a t3 building
- Fixed ACU power consumption not correct after Overcharge
- Fixed and improved the sim dialog window
- Fixed rendering of reload bars
- Fixed bug with the notify overlay in replays
- Fixed a bug where using split-screen mode would break reclaim labels
- Added personal stealth to HARMS ability list
- Adjusted some army colours. A new Order Green, a slightly lighter dark blue, and a golden Seraphim colour from the campaign.
- Fixed Attack-Move icon being greyed out permanently
- Fixed veterancy UI not showing for non-default screen layouts
- Fixed Bulwark dummy shield range ring being the wrong size
- Allowed mod icon support for ACU upgrades
- Refined some UI tips. Engineers now display "Engineering Suite" only, with "Reclaims" and "Repairs" being saved for special case units like the Harbinger

### Lobby
- Changed background faction images to widescreen versions
- Fixed missing dependency bug for non hosts in lobbies
- Overhauled and refined the mod manager

### Other
- Fixed typo in Novax center bones
- Prevented the execution of certain game-breaking console commands
- Allow AI to rebuild upgraded engineering stations in coop missions
- Added game time to the log every 30 seconds
- Added timeout for the overcharge ready notification message to avoid voice spam
- Added rotation animation to the t2 aeon power generator
- Fixed blacklist for coop maps
- Added more naval templates to OpAI
- Updated mod blacklist

### Contributors
basdawimp
CookieNoob
Hussar
IceDreamer
MrNukealizer
PhilipJFry
Speed2
supcomBlackMaster
Uveso

## 3690
### Bugs
- Fixed a word wrap bug that caused missing characters in tooltips and chat, and allowed certain chat messages to crash the game.
### Contributors
MrNukealizer

## 3689
### Bugs
- Veterancy
	- Fixed a bug that caused units to give 100% veterancy points instead of a fraction depending on their remaining HP on death when getting destroyed by self-destruction.
	- Fixed ACUs giving too much veterancy to other ACUs when being killed.
	- Fixed shields recharging many times faster than intended.

### Contributors
Exotic-Retard
MrNukealizer
PhilipJFry





## 3688
### Balance
- Veterancy
	- Until now the veterancy system worked in such a way that the tech level of the units killed determined how many veterancy points a unit was given, and only the unit that got the killing blow would get the veterancy point(s).
	- With this patch we are moving from that tech-based system to a mass based system. That means your units will get veterancy based on the mass of the unit that is killed. Your unit also doesn't need to get the killing blow to get veterancy. Once a unit dies all the units which damaged it will get veterancy points based on how much damage they did to that unit. There are also multipliers to adjust how much veterancy certain classes of units will require to vet up. We will watch closely for cases where veterancy may move to fast or too slow in certain fights and make any adjustments necessary in upcoming patches.
	- he mass value of the ACU has been reduced to 2000 to avoid getting insane veterancy by killing an ACU
	- The amount of veterancy points that the ACU gains from higher tech units is reduced to avoid vetting too fast by overcharging mass heavy land units.
	- Experimental units only need to kill 50% of their own worth in mass to gain one veterancy rank.
	- Regular units need to destroy 200% of their own worth in mass to gain one veterancy rank.
	- Destroying a transport gives veterancy points for the cargo as well as the transport itself.
	- Unified regeneration values.
		>T1 +1 -> 1, 2, 3, 4, 5 regeneration
		T2 +3 -> 3, 6, 9, 12, 15 regeneration
		T3/ACUs +6 -> 6, 12, 18, 24, 30 regeneration
		SACUs +9 -> 9, 18, 27, 36, 45 regeneration
		T4 +25 -> 25, 50, 75, 100, 125 regeneration
    
	- Shields
		- Smoothed out shield recharge from once per second lumps to once per tick.
    
	- Gunships
		- Seraphim T2 Gunship
			>Health: 864 → 1080
			Power Build Cost: 4800 → 6000
			Mass Build Cost: 240 → 300
			Build Time: 1600 → 2000
			Damage: 12 → 16
		- T3 Gunships
			- Cybran T3 Gunships have a personal stealth ability instead of radar jamming.
		- UEF T3 Gunships have radar jamming.
    
	- Novax Satellite
		>Speed: 6 → 9
		Radar Range: 70 → 150
		Omni Range: 0 → 50
		Energy Cost: 80000 → 160000
		Mass Cost: 5000 → 10000
		Build Time: 15000 → 30000
    
	- Flapjack
		- Volley size: 3 → 2
	- Seraphim T1 submarines
		- Torpedo Defense Rate of Fire 0.05 → 0.2
	- Massfabs
		- T2 Massfabs
			>mass cost: 100 → 200
			power drain: 150 → 100
		- T3 Massfabs
			>mass cost: 3000 → 4000
			power cost: 65000 → 120000
			build time: 4988 → 5000
			power drain: 3500 → 1500
			mass gain: 12 → 16
			adjacency bonus on 1x1, 2x2, 3x3 structures buffed to 20%
			adjacency bonus on 5x5 structures buffed to 3.75%
### Contributors
Exotic-Retard
IceDreamer
JaggedAppliance
MrNukealizer
PhilipJFry


## 3686
### Lobby
- Changed "Hide Obsolete" filter in map selection to be enabled by default
- Hide maps if a newer version is available locally
- Fixed the title change option locking if you enter an empty string
- Fixed lobby chat not behaving as expected when multi-line messages are entered
- Allowed lobby chat to correctly handle variable font sizes
- Fixed lobby flags being stretched
- Fixed lobby presets not handling unit restrictions correctly
- Fixed lobby autoteams button not syncing with the selected game options correctly
- Added a warning to the host if they have selected an outdated map, asking them to update it
- Fixed observers being unable to click the observer/player toggle button after being moved to observer while ready
- Added a button to close all unoccupied open slots or open all closed slots
- Fixed a bug where the mod manager UI could break if the host has a mod with an incomplete info file
### Bugs
- Fixed an error caused by empty gunships
- Fixed the spacing when tiling rotated templates being off in some situations
- Fixed a bug which caused only one engineer of a group ordered to rebuild a wreck to actually attempt the task
- Fixed HARMS sinking more than once in some situations
- Fixed deleted orders reappearing if spread command is used
- Added safeguards against a rare exploit which allowed bypassing of the share conditions
- Fixed orders bugging out sometimes if units in the selection died
- Fixed an error caused by a czar dying with units in the hold
- Prevented air units sometimes sinking below the map after bouncing off a shield
- Fixed game exit behaviour sometimes erroring or throwing logspam
- Fixed Czar targeting hover units with depth charges
- Fixed only one Overcharge shot being fired when multiple Overcharge commands are queued
- Fixed Novax Center being unable to build a replacement satellite after a satellite is destroyed blocking a nuke
- Fixed Novax satellite disappearing before hitting the ground after the control center is destroyed
- Fixed subs stopping too close to their targets when given an Attack Move order
- Fixed a bug that caused Hives (and possibly other Cybran units) to instantly capture a unit in some situations
- Increased Cybran SACU projectile lifetime so it can hit targets at the edge of its upgraded range
- Fixed some instances of transported units not dying when their transport dies

### Gameplay
- New Feature: Integrated a vastly improved version of the popular Notify mod
	- Notify Features
		- Notify started as a way to allow ACU upgrade progress to be communicated nicely to the team. FAF has taken it to the next level.
		- Support for sending notifications about ACU upgrades, Factory Tech upgrades (HQs), Experimental construction, and Nuke and T3 Artillery construction
		- By default, you will see notifications about ACU upgrades only, as well as an ETA overlay at the location of the upgrading ACUs
		- Toggles available to define which types of messages you want to see come in from allies
		- Notify messages limited to only show the first of each HQ type, Experimental (Non game-ender), Nuke, or T3 Artillery to avoid spamming the chat with notifications late-game
	- Notify UI
		- Selecting your ACU will show any upgrades it has completed for each slot above the UI in the bottom left corner
		- There is an in-game customisation menu UI. It can be accessed via the main menu, or with a key bind. Default binding is CTRL-ALT-F1
		- Full customisation of all Notify messages is enabled, including resetting to default
		- All message types are broadcast at all times. The menu allows you to customise which messages you see, using toggle buttons at the top of the customiser.
		- Colour of Notify messages can be changed inside the chat window
	- Upgrade Queuing
		- ACU Upgrades can now be queued up the same as any other construction project
		- Unfortunately, due to an engine limitation, upgrades cannot be UN-queued (You can only stop the ACU, cancelling the in-progress work orders)
		- ACUs can queue buildings from an uncompleted tech level if the upgrade is queued
		- Hotbuild has the ability to correctly access the uncompleted tech level buildings tooltip
	- Blacklisted all previous Notify mod versions
- Significantly improved unit formations
	- Changed land and naval formations to give large units extra space instead of forcing the whole group to spread out
	- Moved submarines so they sit between surface vessels instead of directly under them
	- Changed air formation shape to spread units out more evenly and make large formations wider instead of a long line
	- Made guard formation denser so more units can stay close to the target
	- Changed shield distribution in guard formation to more efficiently cover the target and other guarding units
	- Fixed several unit filter issues that caused units to get the wrong positions or even be excluded from a formation altogether
	- Rearranged land and naval formations to give some units better positions
- Improved spread attack. It now handles most order types.
- Changed the timeout on player attention pings to be per-player instead of on a global cooldown
- Fixed and optimised TML leading for AIs
- Increased the depth at which Megalith and Ythotha appear to be submerged in water instead of walking on land
- Reverted the Energy hotbuild cycling through to Storage, in response to popular demand.
- T3 Sonar can now be given assist commands. Primarily useful so they can guard a unit and stay with it.

### UI
- Added full support for UTF character set in the lobby, game chat, and other typing interfaces. This enables Russian, Chinese, Japanese, and all manner of other characters.
- Fixed ShowNetworkStats not closing in some situations
- Fixed the construction menu pause button not changing colour with factional skins
- Added an option to have fonts change colour according to faction
- Fixed observers not seeing the correct unit regen number for units with veterancy, upgrades, or other regen changes
- Detail view no longer shows a cost/tick breakdown for some units incorrectly
- Made loading screen hints more readable by adding a drop shadow effect
- Fixed a bug causing build mode to exit when a template is ordered
- Added a hotbuild key for T3 Mobile AA
- Fixed a hotbuild bug causing errors when certain units were upgraded
- Fixed hotbuild key label for support factory upgrades being on the wrong icon
- Fixed zoom pop key action not functioning
- Fixed reclaim overlay sometimes showing reclaim out of the playable areas
- Put silo count/capactity label at the top of the button to avoid it being obscured by the hotkey label
- Added an option to disable hotkey labels
- Fixed factory templates not displaying icons for mod units
- Fixed missing UI elements in replays or when the Use Factional UI Skin option is disabled
- Removed "Quick Tip" prefix from the tips which show on the loading screen
- Added T3 MAA to the hotkey description

### Other
- Updated mods blacklist
- Updated maps blacklist
- Random spawn locations are no longer accurate in the UI to prevent UI mods from cheating
- New random spawn modes have been added which mark opponents' spawn locations so all players can see where everyone is
- Fixed an issue with offline COOP not working as intended
- Significant improvements and bugfixes for COOP AI capabilities
- Properly hide failed bonus objectives in COOP
- Optimised Sorian-AI-related code a little
- Optimised AIX-related code a little
- Fixed kill objectives not working as intended in COOP
- Fixed Torpedo Boat ID being incorrect from an AI perspective, causing them not to work properly
- Added additional AI Naval platoon templates
- Removed the hyphen from "Air Superiority Fighter" unit type to make it the same across all factions

### Contributors
CookieNoob
Crispweed
Crotalus
dk0x
IceDreamer
JaggedAppliance
MrNukealizer
PhilipJFry
speed2
TheKeyBlue
Uveso

## 3684
### Other
- Fixed a typo that is probably responcible for the rare sim freeze bug that has been happening since 3680
- Fixed a typo which broke some FX on the Ythotha
### Gameplay(Balance)
**Janus**
>- Corrected miscalculation in total damage. Fire pulse count decreased 15 → 10

**Reclaim**
>- Time taken to reclaim unit wrecks doubled. Props and living units unaffected
>- Increased value of split trees by 25% to compensate for it taking longer to reclaim them

**T1 Land/Air Factory + T2 Land/Air Support**
> Aeon Health increased 3100 → 3200
> Cybran
	>- Health increased 2500 → 2750
	>- Regen increased 6 → 9

**T1 Naval Factory**
>Aeon Health increased 3100 → 3700
>UEF Health increased 4000 → 4500
>Seraphim Health increased 3500 → 4000
>Cybran
>- Health increased 2500 → 3200
Regen increased 6 → 10
T2 Land/Air HQ + T3 Land/Air Support
Aeon Health increased 6200 → 6400
Cybran Health increased 5000 → 5500
T2 Naval Support
Aeon Health increased 5000 → 6400
UEF Health increased 6500 → 8000
Seraphim Health increased 5500 → 7000
Cybran
Health increased 4000 → 5500
Regen increased 12 → 20
T2 Naval HQ
Aeon Health increased 10000 → 12800
UEF Health increased 13000 → 16000
Seraphim Health increased 11000 → 14000
Cybran
Health increased 8000 → 11000
Regen increased 30 → 40
T3 Land/Air HQ
Aeon Health increased 12400 → 12800
Cybran Health increased 10000 → 11000
T3 Naval Support
Aeon Health decreased 13000 → 12800
UEF Health decreased 17000 → 16000
Cybran Regen increased 30 → 40
Seraphim Health decreased 15000 → 14000
T3 Naval HQ
Aeon Health increased 20000 → 21000
Cybran Health increased 16000 → 17000
Seraphim Health increased 22000 → 23000
Hydrocarbon
Cybran Regen decreased 6 → 5
Mass Storage
Cybran Regen decreased 4 → 3
Seraphim ACU Second Gun Upgrade
Mass cost increased 3500 → 4800
Energy cost decreased 300000 → 270000
Damage bonus increased 400 → 750
Damage radius increased 2 → 2.
Veterancy
Increased veterancy regen values for Experimentals across the board
Fixed longstanding bug causing Veterancy to heal far too much health
Introduced new veterancy mechanics to allow fine control over instant heal effect
Old system: 1st Vet = Heal for max HP * 0.1. 2nd Vet = Heal for max HP * 0.2 ... etc
New system: Unchanged for ACUs. Other units heal max HP * 0.1 each time
MMLs
Aeon
Missile HP increased 1 → 2
Missile motion parameters changed to be slower
UEF
Now fires 3 missiles in a salvo, 1.8 seconds apart, every 10 seconds
Effective DPS increased 60 → 90
Seraphim
Missile motion parameters changed to be faster
MuzzleVelocity increased 3 → 4
RateOfFire increased 0.15 → 0.1666. Firing cycle from 1 shot every 6.7s to one shot every 6 seconds
Effective DPS increased 60.4 → 67.5
Sparky
Reintroduced Energy drain of 15 for running Jammer
Novax Satellite
Crash damage decreased 3000 → 1000
UEF T1 Bomber
Bomb DoT Duration increased 1.5 → 4.2. Damage remains the same, just more spread out in time T2 Static Flak
Aeon MuzzleVelocity increased 30 → 35
UEF MuzzleVelocity increased 25 → 35
Cybran MuzzleVelocity increased 20 → 30
Seraphim
MuzzleVelocity increased 25 → 35
AOE increased 3 → 4
FiringRandomness decreased 2.5 → 2
Crab Eggs
Corrected T3 Engineer Egg to match new values for the main unit from previous patches
BuildTime of all eggs reduced by 50%
Megalith
BuildRate decreased 180 → 45
Combined with egg changes, effectively doubles egg build time, and reduces Megalith reclaim rate to 25% of before
Aurora
FiringRandomnessWhileMoving increased 0.1 → 0.3
Harbinger
BuildRate increased 3 → 5
Aeon ACU
First Shield upgrade recharge time increased 65 → 90
Contributors
Crotalus
IceDreamer
JaggedAppliance
MrNukealizer
PerticPwnz

## 3682
### Bugs
- Fixed a typo that is probably responsible for the rare sim freeze bug that has been happening since 3680
### Gameplay
- Fixed several unit restriction settings restricting units that did not make sense
- Hotbuild power generators key now also cycles through to power storage
- Fixed hotbuild select nearest scout not selecting the nearest one, and not selecting spy planes
### UI
- Added a new button to the F10/Main Options dropdown ingame to access the key bindings popup directly in case you remapped F1
- Updated the wording of several loading tips
### Contributors
CookieNoob
Fast-Thick-Pants
Hussar
IceDreamer
PhilipJFry
Speed2

Special Thanks
MrNukealizer
## 3681
### Bugs
- Fixed always loading the default or last map, which broke COOP
- Fixed a typo which broke All Faction Templates
### Other
- Reverted the changes to lobby text showing faction colours due to community feedback. This feature will reappear as an option in the future.
### Contributors
Icedreamer
MrNukealizer
## 3680
### Gameplay
- New feature: Dead air unit wrecks now bounce off shields. The amount of bounce depends on the unit's momentum and angle of approach. Some of the crash damage is transferred to the shield. Unit wrecks can only bounce once. Doesn't affect Experimentals.
- Allow units in a transport which is shot down to leave wrecks at the crash site
- Allow the Novax to build a new Satellite if the old one dies. This can only happen if it is impacted by a Nuke or ctrl-k'ed
- Introduced code to slightly improve the way Tempest and Atlantis behave, particularly in being able to fire, in shallow waters
- Enabled fire states on TML and SML structures and units. This allows you to command multiple launchers to fire simultaneously at multiple targets
- Increased reconnect timeout from 45 to 90 seconds to better allow router reboots
- HARMS now sinks to a greater depth on completion
- Assist-Mex-To-Cap is now on by default

### Bugs Fixes
- Fixed ACU reclaiming while shooting
- Fixed ACU building while shooting
- Fixed Auto-Overcharge stopping working randomly until toggled
- Fixed Auto-Overcharge firing while building
- Fixed SML hitboxes so some are no longer immune to T2 PGen explosions
- Increased Beetle hitbox size and declared new targetbones to stop everything missing it if it strafes
- Fixed two move-while-building exploits
- Gave Force damage to several AOE weapons so they now kill trees properly
- Fixed ambient movement sounds continuing to play for sinking units
- Fixed air units occasionally granting infinite intel at the crash site
- Fixed unit restrictions not updating correctly when HQs are transferred between players
- Fixed ancient bug which didn't deselect factory units properly, leading to accidental pausing of those units
- Fixed the 'Select Onscreen Land/Air/Navy' hotkey also selecting the factories of that type
- Fixed the Mex Cap feature somehow allowing storage to be built inside units built via upgrade
- Fixed bug where the Aeon shields didn't visually rotate properly
- Fixed adjacency visual effect being placed on the water surface when dealing with underwater mexes or hydros
- Fixed ships sometimes sinking through land
- Attempted a safety check to try and fix Aeon T2 shields getting the shield up despite having been destroyed in construction
- Fixed cluster bombers (Janus etc) gaining a new target halfway through a bombing run

### Lobby
- Fixed 'Random' faction using 'Random - Unbalanced' tooltip
- Allow filtering of 13-16 player maps in map selection
- Fixed 'Autoteams: Manual' resulting in all players being allied
- Fixed autobalance functions crashing when used with uneven team numbers
- Improved the ping/cpu display column, splitting it into two. The ping column only shows when it matters.
- Observers are now kicked before checking connection issues when Allow Observers is false. This means they will no longer stall game launch if one or more have a connection issue.
- Improved performance of Unit Manager, as well as layout, tooltips, and some icons
- Fixed faction selector panel not updating properly
- Removed ability for people to spam the lobby chat with the observer button
- Fixed several cases of CPU rating not being broadcast properly
- Added a 'New Message' button to the lobby which jumps to bottom of chat, and disabled the chat auto-hopping to bottom with every new message, if you have scrolled up
- Fixed the number of active mods not updating for non-hosts when they enable/disable a UI mod
- Fixed double clicking various elements in the lobby bypassing various restrictions
- Added a tooltip to the map preview top right

### UI
- Added new option to change the minimum reclaim label size shown in the overlay
- Enabled the STOP button for shields which can be upgraded
- Removed the tech level tick from Mass Storage strategic icon to match energy storage
- Fixed hotkey labels not moving properly when scrolling the build menu
- Pause button is now visible and active in the Enhancements and Selection tabs
- Allowed multiple nuke pings to display simultaneously
- Corrected several incorrect tooltips on SCUs
- You can now search for bindings or actions in the F1 key binding menu
- The buttons for adding and removing key bindings have been moved to be on the same line as the binding
- Added Hotbuild Preset button. This will automatically set your bindings to the Hotbuild Preset. There is also a button to set back to Default Preset.
- Fixed Hotbuild conflicting with other binds
- Fixed keys being able to be bound to two actions at once
- Keybinding UI will now auto-assign shift-bindings to match a newly bound action, if the shift-bind is not in use
- Fixed hotbuild labels in the construction UI not updating when they are re-assigned
- Lots of text around the UI will now change colour to reflect your faction skin again
- New Feature: Helpful tips and tricks will now show briefly on the loading screen
- Fixed language changes not always taking effect on game restart properly
- Removed nonfunctional language change hotloader
- Fixed buttons with a countdown not counting down

### Balance
- Increased Auto-Overcharge rate of fire from 3.3s to 5s

### Other
- Added some mods to blacklist
- Allowed hooking of schook files to help future patch mechanism
- Allow hot-reloading of UI files with EnableDiskWatch
- Uncapped max framerate for people with monitor refresh rates >100
- Fixed desync in COOP
- Allow Salem death sound on land in COOP
- Allowed restricted units to be captured in COOP
- Added a new objective type to COOP
- Added a new icon for the Kill or Capture objective in COOP
- Objective tooltip in COOP now coloured according to faction skin
- Various other extensive COOP-only changes
- Added CZ translation file
- Added PL translation file
- Improved RU translations
- Improved SP translations

### Contributors
CookieNoob
Crotalus
Duk3Luk3
Exotic-Retard
Hussar
IceDreamer
IDragonfire
PhilipJFry
Speed2
TheKeyBlue
ThomasHiatt
Uveso

Special Thanks
Jackherer (French translations)
UnicornNoob (Russian translations)

## 3677
### Bugs
- Added code to log and potentially fix an issue with army index assignment which may be causing rating irregularities
### Contributors
duk3luk3

## 3676
### Welcome to the patchnotes for the 3676 patch.
The focus of this patch is working on improving the implementation of the previous patch. Cybran regen is improved, Seraphim get a buff to their hps, as well as some smaller changes and fixes.

We wish you good luck and much fun playing with the new patch!

-- The Balance Team

### Air
**Janus:**
Janus gets a slight buff again to improve it slightly vs units.
>- Initial Damage: 15 → 20
>- Total Impact Damage: 300 → 400
>- Total Overall Damage: 1500 → 1600
### Structures
**T3 Naval Support Factories:**
T3 naval support facs were found to be too vulnerable considering the cost of the units being constructed within them so we have reduced their hp nerf.
>- UEF HP: 13000 → 17000
>- Seraphim HP: 10000 → 15000
>- Aeon HP: 10000 → 13000
>- Cybran HP: 8000 → 11000
>- Cybran HP Regeneration: 15 → 30

**T2 UEF Naval Support Factory:**
This is a correction of the UEF T2 naval support factory which was missed in testing before the previous balance patch.
>- HP: 6000 → 6500

**Mass Storages:**
Mass storage hp has been given some hp back, so that it is more in line with their cost.
>- UEF HP: 760 → 1200
>- Seraphim HP: 600 → 1100
>- Aeon HP: 600 → 1000
>- Cybran HP: 500 → 800
>- Cybran HP Regeneration: 1 → 4

### Seraphim Structures
In the HP nerf patch Seraphim were given the same HP as Aeon. However we now decided to buff their HP so that they have more than Aeon, but still less than UEF. Seraphim have less unit choices and are not one of the stongest factions so some buffs are warranted and this also increases faction diversity.

**Seraphim T1 Buildings:**
>- Air/Land/Naval Factory HP: 3100 → 3500
>- Power Generator HP: 600 → 650
>- Hydrocarbon Power Plant HP: 1600 → 1700
>- Mass Extractor HP: 600 → 650
>- Wall Segment HP: 2000 → 2500

**Seraphim T2 Buildings:**
>- Air/Land Factory HQ HP: 6200 → 7000
>- Naval Factory HQ HP: 10000 → 11000
>- Air/Land Support Factory HP: 3100 → 3500
>- Naval Support Factory HP: 5000 → 5500
>- Power Generator/Mass Extractor HP: 1900 → 2000

**Seraphim T3 Buildings:**
>- Air/Land Factory HQ HP: 12400 → 14000
>- Naval Factory HQ HP: 20000 → 22000
>- Air/Land Support Factory HP: 6200 → 7000
>- Naval Support Factory HP: 10000 → 15000
>- Power Generator/Mass Extractor HP: 6200 → 7000

### Cybran Structure Regeneration
The initial Cybran regen values were found to be too low to be a relevant feature, so we have increased Cybran regen across the board.

**Cybran T1 Buildings:**
>- Air/Land/Naval Factory: 3 → 6
>- Power Generator/Mass Extractor: 1 → 2
>- Hydrocarbon Power Plant: 1 → 6
>- Wall Segment: 3 → 6

**Cybran T2 Buildings:**
>- Air/Land Factory HQ Regen: 10 → 20
>- Naval Factory HQ Regen: 15 → 30
>- Air/Land Support Factory Regen: 3 → 6
>- Naval Factory Regen: 6 → 12
>- Power Generator/Mass Extractor Regen: 3 → 6

**Cybran T3 Buildings:**
>- Land Factory HQ Regen: 20 → 40
>- Air Factory HQ Regen: 20 → 40
>- Naval Factory HQ Regen: 30 → 60
>- Air/Land Support Factory Regen: 10 → 20
>- Naval Factory Regen: 15 → 30
>- Power Generator/Mass Extractor Regen: 10 → 20

### Miscellaneous
**Wall segments:**
Destroying Wall Segments now grants 0.1 veterancy instead of 1. Killing walls for vet was an abuse which became more prevalent since the wall hp nerf.

**T2 Radar:**
We have reduced the maintenance cost of T2 radars to encourage this intel option in the midgame.

>- T2 Radar energy Mainentance cost: 250 → 200
## 3675
### Bugs
- Fixed a small bug that led to the game not ending properly when a player died with Share Unit Cap turned on

## 3674
### Welcome to the patchnotes for the 3674.
This patch contains the HP changes that have been in testing and discussion for a long time, and some Ythotha buffs on top. As always, you can post your feedback and opinion on the forums.

We wish you good luck and much fun playing with the new patch!

-- The balance team


### Land
**Ythotha:**
A buff to the Ythotha has been long planned and wished, but buffing it in a way that makes the unit more dynamic and interesting turned out to be difficult. We have decided to improve it by making it more nimble and also allowing it to shoot 45 degrees backwards so that it can be microed to a much greater degree. It also gets a slight range increase to help with this goal. We will closely observe if this new microability in certain situations gives the Ythotha the power it should have, or if further adjustments are needed.
>- TurnRate: 40 → 60
>- EyeWeapon Range: 45 → 47
>- LeftArm Range: 45 → 47
>- RightArm Range: 45 → 47
>- AA Range: 45 → 47
>- AA AOE: 1.5 → 4
>- RightArm, LeftArm and EyeWeapon can now shoot 45 degrees behind them.
>- AA can shoot at a slightly greater angle to eliminate blindspots.
>- Added UseFiringSolutionInsteadOfAimBone = true for better AA performance. Credit to EQ for this AA change.

**Stun:**
- Stun effects will no longer affect air units.

### Air
**Janus:**
The Janus change in the last patch worked well but was found to be too strong. The napalm's burn time is increased to allow players to react and move out of the damage radius before all damage has been dealt. The initial damage of the bombs is also decreased.
>- DoTTime: 4.2 → 6
>- InitialDamage per bomb: 30 → 15

### Structures
**HP Reductions (Part 1)**
The goal with all the HP reductions in general is to allow more options for aggressive play, especially in the lategame and to bring the game closer to how it is working with the current low t2 pg HP and its impact on the game.

The goal with increasing the HP differences between the factions is to make them a relevant and interesting part of the game, rather than a visual difference without much impact. The changes are aimed to increase faction diversity and attempt to even out the current differences in power between the factions by giving them more unique strengths and weaknesses, rather than making them more equal. This are rather big changes, but we believe they will make the game more diverse and interesting.

To compensate cybran a bit for the rather large nerfs, and to accompany their new weakness with a strength that fits to them, all their nerfed buildings do (very slowly) regenerate health now in return. They are more vulnuable, but if you don't kill them they will be back at full HP after about 10 minutes for each building.


**UEF T1 Land Factory.pngT1 Land/Air/Navy and T2 Land/Air Support Factories**

>- UEF HP: 4100 / 4100 / 4800 and 4500 / 4500 → 4000
>- Aeon HP: 3700 / 3700 / 4400 and 4100 / 4100 → 3100
>- Seraphim HP: 3700 / 3700 / 4600 and 4300 / 4300 → 3100
>- Cybran HP: 3500 / 3500 / 4200 and 3900 / 3900 → 2500
>- Cybran HP regeneration: 3 hp/s

**UEF T2 Land Factory HQ.pngT2 Land/Air HQ and T3 Land/Air Support Factories**

>- UEF HP: 9000 and 4500 / 4500 → 8000
>- Aeon HP: 8200 and 10000 → 6200
>- Seraphim HP: 8200 and 10500 → 6200
>- Cybran HP: 7800 and 9500 → 5000
>- Cybran HP regeneration: 10 hp/s

**UEF T3 Land Factory HQ.pngT3 Land/Air HQs**

>- UEF HP: 22000 → 16000
>- Aeon HP: 20000 → 12400
>- Seraphim HP: 21000 → 12400
>- Cybran HP: 19000 → 10000
>- Cybran HP regeneration: 20 hp/s

**UEF T2 Naval Factory.png T2 Navy Support Factories**

>- UEF HP: 9000 → 6000
>- Aeon HP: 8000 → 5000
>- Seraphim HP: 8500 → 5000
>- Cybran HP: 7500 → 4000
>- Cybran HP regeneration: 6 hp/s

**UEF T2 Naval Factory HQ.png T2 Navy HQs / t3 Navy Support Factories**

>- UEF HP: 18000 / 20000 → 13000
>- Aeon HP: 16000 / 18750 → 10000
>- Seraphim HP: 17000 / 19000 → 10000
>- Cybran HP: 15000 / 17000 → 8000
>- Cybran HP regeneration: 15 hp/s

**HP Reductions (Part 2)**

**T1 Mass Extractors and T1 Power Generators:**

>- UEF HP: 600 → 760
>- Aeon HP: 600
>- Seraphim HP: 600
>- Cybran HP: 600 → 500
>- Cybran HP regeneration: 1 hp/s

**T1 Mass Storage:**

>- UEF HP: 1600 → 760
>- Aeon HP: 1600 → 600
>- Seraphim HP: 1600 → 600
>- Cybran HP: 1600 → 500
>- Cybran HP regeneration: 1 hp/s

**T2 Mass Extractors and T2 Power Generators:**

>- UEF HP: 3000 / 2160 → 2500
>- Aeon HP: 3000 / 2160 → 1900
>- Seraphim HP: 3000 / 2160 → 1900
>- Cybran HP: 3000 / 2160 → 1800
>- Cybran HP regeneration: 3 hp/s

**T3 Mass Extractors and T3 Power Generators:**

>- UEF HP: 8400 / 9720 → 9000
>- Aeon HP: 8400 / 9720 → 6200
>- Seraphim HP: 8400 / 9720 → 6200
>- Cybran HP: 8400 / 9720 → 6000
>- Cybran HP regeneration: 10 hp/s
>- Explosion Damage (only t3 Power Generator): 8000 → 5500

**Hydrocarbonplants:**

>- UEF HP: 1600 → 1800
>- Aeon HP: 1600
>- Seraphim HP: 1600
>- Cybran HP: 1600 → 1400
>- Cybran HP regeneration: 1 hp/s

**Walls:**

>- BuildTime: 10 → 20
>- UEF HP: 4000 → 3000
>- Aeon HP: 4000 → 2000
>- Seraphim HP: 4000 → 2000
>- Cybran HP: 4000 → 1500
>- Cybran HP regeneration: 3 hp/s
## 3672
### Bugs
- Fixed non-default team balance option breaking the anti-rating-bug code
## 3671
### Bugs
- Fixed an unintentional bug with hosting games with an AI introduced with the rating bug fixes below
## 3670
### Bugs
- Fixed the game reporting incorrect army indexes to the server on game start, leading to incorrect rating calculations on game end
## 3669
### Bugs
- Reverted that last one for a bit to fix an idiot bug
## 3668
### Bugs
- Fixed the game reporting incorrect army indexes to the server on game start, leading to incorrect rating calculations on game end