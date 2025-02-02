---
title: Game & Balance Patchnotes 2018
description: 
published: true
date: 2021-09-09T09:11:53.184Z
tags: 
editor: markdown
dateCreated: 2021-09-08T22:36:42.319Z
---

# Complete changelog of all changes in 2018 {.tabset}

## 3702
### Lobby
- Added a feedback button for the ladder map pool in the score screen
- Improved changelog popup
### UI
- Disable notify during cinematics
### Gameplay
- Allow walls to be handed over in fullshare games
- Allow switching to different target priorities for units
- Improved AI
### Bugs
- Improved the aiming of the sera pd
- Fixed AI not rebuilding satellite
- Fixed a bug causing capture to keep the upgrade progress
- Fixed several rare bugs that were causing a crash
- Removed CZAR from AA fighter hotkey
### Other
- Improved parser to allow complex default target priorities for weapons
- Updated mod blacklist
- Optimized unit range rings
### Contributors
Faether
Strogo
Uveso
speed2
Exotic_Retard
PhilipJFry
keyser

## 3701
### Bugs
- Fixed bug that caused the Kennel structure to stay after being upgraded which resulted into having two buildings stacked upon each other
### Gameplay
- Changed Novax Sat fix in order to not potentially break mods
- Updated mod blacklist
- Removed smoke effect on the water surface caused by wrecks on the bottom of the ocean
### Lobby
- Moved current patch number in the lobby to a more visible location
- Allow Users to open the Changelog by clicking on the patch number in the game lobby
- Allow Users to open the changelog on github by adding a button to the changelog popup in the lobby
### Contributors
speed2
Strogo
Exotic-Retard
PhilipJFry

## 3700
### Bug
- Fixed bug that caused users to get stuck when trying to host/join a game
### Contributors
speed2

## 3699
### Lobby
- Added an option for coloured name in the chat
- Fixed units restriction menu
- Removed a player color that is too similar to civilian colour
### Gameplay
- Removed friendly collisions
- Allowed the selection of upgradable/offensive building and all experimentals while they are being built
- Improved AI
- Saved upgrade progress of building and exp/T3 arty build progression after transfer for game with full share condition
### Bugs
- Fixed units losing veterancy after transfer
- Fixed nuke being deflected by aeon TMD
- Fixed HARMS not being seen by surface units while being built
- Fixed satellite weapon firing when retargeting
- Fixed OC not impacting on mobile shield
- Fixed the way wreckages spawn from map script
- Fixed ythotha lightning being triggered by alt-delete and by the wreck spawn from map script
- Fixed mobile shield stopping when assisting friendly units and enemy units are nearby
- Fixed strats killing each other when bomb connect with opponent asf, by making them immune to allies strat
- Fixed kennel's drones not being paused after transfer
- Fixed kennel spawning drone after transfer
### Contributors
Hussar
keyser
Strogo
Uveso
Rackover
JeroenDeDauw
Zkov96
c0_okieZ
Crotalus
Exotic_Retard
PhilipJFry

## 3698
### Bug
- Remove AI Takeover from ladder as it is intended to be an option for custom games

### Contributors
TheAdDad

## 3697
### Lobby
- Introduced ability to have mods that affect AI options
- Fixed official maps being hidden at the wrong time by the filter
- Added chat name colors
- Lobby refactor
- Allow more "No Rush" timer
### UI
- Fixed shielded air units having their shield and fuel UI bars collide
- Added a shield bar under the ACU icon
- Added the mass killed meter for full veted units.
- Updated the tips to the actual balance
### Gameplay
- Allow Novax Command Center to have rally points
- Allow torpedo to target subs first
- Allow the missile from SMD to not collide with air
- Allow nuke to be invulnerable to satellite laser
### Bugs
- Fixed Aeon Hydrocarbon not being targetable during construction
- Fixed some underwater props being rendered as though they were above the water
- Fixed objective units not being properly highlighted in COOP
- Fixed T2 fighter/bomber slowing down on move order when there is land/naval target nearby
- Fixed wrong civilian blueprints
- Fixed sera T3 static arty shots landing too short
- Fixed UEF Battlecruiser leaving no mass behind
- Fixed being able to shield transport and having a personal shield of 0 hp
- Fixed a crash with "Game object have been destroyed"
- Fixed OC draining more e than available
- Fixed omen and exodus not retargeting as soon as possible
- Fixed T3 static arty having issue shooting at targets on higher ground
- Fixed the deflected missiles by loyalist missing the target
- Fixed walls not being selectable on double-click
### Other
- Improved engine documentation
- Improved performance
- Updated mod blacklist
- Updated map blacklist
- Added blueprints for unit database
- Cleaned up some blueprint entries and unit IDs for unit database
- Further game translation into French
- Added a chinese translation
- Optimized the AI sim speed
- Make game load props folder
- Make game send message when the simulation ends
- Added an option allowing AI to take over a player when disconnection occurs
- Added russian, german and french translation to adaptative map options

### Contributors
strogo
rackover
speed2
CookieNoob
PhilipJFry
IceDreamer
keyser
Uveso
FAETHER
TheAdDad
ChrisKitching
crotalus
dk0x

## 3696
### Balance
**Aeon**
- Personal Shield Generator
	>- BuildCostMass: 1000 → 1300
	>- BuildTime: 1000 → 1300
- Heavy Personal Shield Generator
	>- BuildCostEnergy: 93750 → 123750
	>- BuildCostMass: 1500 → 2300
	>- BuildTime: 1750 → 2450
	>- ShieldMaxHealth: 29000 → 25000
	>- ShieldRegenRate: 37 → 32

**UEF**
- Nano-Repair System
	>- NewHealth: 2000 → 1500
- Personal Shield Generator
	>- BuildCostMass: 1500 → 2300
	>- ShieldMaxHealth: 24000 → 19000
	>- ShieldRegenRate: 35 → 30
- Shield Generator Field
	>- BuildCostMass: 3000 → 3600
	>- BuildTime: 2800 → 3400

**Seraphim**
- Refracting Chronotron Amplifier
	>- AdditionalDamage: 750 → 620
	>- BuildCostMass: 4800 → 5400
	>- BuildTime: 4200 → 4600
- Nano-Repair System
	>- BuildCostEnergy: 42000 → 56000
	>- BuildCostMass: 1200 → 1800
	>- BuildTime: 1200 → 1800
	>- NewHealth: 3000 → 2000
- Enhanced Nano-Repair System
	>- BuildCostMass: 4500 → 5800
	>- BuildTime: 4200 → 4600

**T3 Land Combat**
- Harbinger
	>- Health: 4600 → 3050
	>- Shield Health: 1300 → 1000
	>- Shield Regen Rate: 9 → 30
	>- Shield Recharge Time: 63 → 40
	>- ShieldRegenStartTime: 3 → 2
	>- Power Drain: 25 → 30
	>- BuildTime: 4500 → 3600
	>- Speed: 3 → 2.85
	>- Acceleration: 3 → 3.2
	>- Turn Rate: 120 → 130
	>- Damage: 300 → 320
	>- Rate of Fire: 1.25 → 1
	>- Range: 28 → 26
	>- Muzzle Velocity: 30 → 40
	>- DPS: 375 → 320
- Othuum
	>- Health: 6700 → 5000
	>- Acceleration: 2.6 → 3.5
	>- SizeY: 0.45 → 0.65
  >- SizeZ: 2.0 → 2.3
  >- First 2 Guns:
		- Damage: 75 → 39
		- Muzzle Velocity: 35 → 40
		-	Turret Yaw Speed: 90 → 120
		- Combined DPS: 300 → 156
	>- 3rd Gun:
		- Damage: 400 → 525
		- Range: 32 → 28
		- Muzzle Velocity: 30 → 40
		- DPS: 100 → 131
	>- Torpedo Weapon:
		- Range: 32 → 28
	>- Target Priorities: Othuum now prioritises T3 over T2 over T1 instead of the reverse.
- Percival
	>- Health: 9300 → 7200
	>- BuildTime: 6000 → 4800
	>- Speed: 2 → 2.1
	>- Acceleration: → 2.1
	>- TurnRate: 60 → 70
	>- Damage: 1600 → 1670
	>- Rate of Fire: 0.25 → 0.2
	>- Range: 35 → 34
	>- Muzzle Velocity: 35 → 38
	>- Turret Yaw Speed: 60 → 90
	>- DPS: 400 → 334
- Titan
	>- Health: 2200 → 2550
	>- Shield: 1200 → 600
	>- Recharge Time: 60 → 15
	>- Regen Rate: 9 → 20
	>- Speed: 4 → 3.8
	>- Acceleration: 4 → 4.2
	>- Range: 20 → 22
	>- Muzzle Velocity: 30 → 35
	>- Turn rate: 150 → 120
	>- Target Priorities: Titan now prioritises T3 over T2 over T1 instead of the reverse.
- Brick
	>- Health: 9000 → 7500
	>- BuildTime: 6000 → 4800
	>- Speed: 2 → 2.3
	>- Acceleration: 2 → 2.3	
	>- TurnRate: 60 → 65
	>- Main Weapon:
		- Damage: 150 → 125
		-	Range: 35 → 32
		-	MuzzleVelocity: 35 → 42
		-	Turret Yaw Speed: 60 → 90
		-	DPS: 375 → 312.5
- Loyalist
	>- Health: 3100 → 3000
	>- Speed: 4 → 3.8
	>- Acceleration: 4 → 4.2
	>- EMP explosion on death:
		- Duration: 2s → 1.4s
		- Affected by Stun: Mobile Units → Mobile Units - except for T4 and ACUs
	>- 1st Weapon (Disintegrator Pulse Laser):
		- Damage: 175 → 150
		- Range: 25 → 20
		- DPS: 175 → 150
	>- 2nd Weapon (Heavy Electron Bolter):
		- Damage: 12 → 14
		- Range: 25 → 20
		- Muzzle Velocity: 40 → 35
		- TurretYawSpeed: 90 → 120
		- DPS: 30 → 35

**T3 Ranged Units**
- Sprite Striker
	>- Mass Cost: 640 → 720
	>- Build Time: 3600 → 4000
	>- Health: 450 → 500
	>- Speed: 3 → 2.85
	>- Sizex: 0.8 → 0.95
	>- SizeY: 1.15 → 1.35
	>- SizeZ: 0.6 → 0.8
	>- Firing Randomness while moving: 0.5 → 0.3
	>- Rate of Fire: 0.142 → 0.15
	>- MuzzleVelocity: 120 → 90
	>- TurretYawSpeed: 90 → 110
- Usha-Ah
	>- Mass Cost: 640 → 800
	>- Energy Cost: 8000 → 8800
	>- Build Time: 3600 → 4300
	>- Health: 500 → 700
	>- Speed: 3 → 2.5
	>- Acceleration: 3 → 2.5
	>- UniformScale: 0.08 → 0.095
	>- SizeX: 0.35 → 0.45
	>- SizeY: 1.2 → 1.55
	>- SizeZ: 0.7 → 0.9
	>- Default Fire Mode:
		- Firing Randomness while moving: 0.25 → 0.4
		- Rate of Fire: 0.2 → 0.25
		- Firing Tolerance: 0.5 → 3
		- Mzzle Velocity: 120 → 80
		- TurretYawSpeed: 90 → 70
	>- Ranged Fire Mode:
		- Firing Randomness while moving: 0.5 → 0.2
		- Rate of Fire: 0.07 → 0.066
		- TurretYawSpeed: 90 → 50

**T3 Mobile Artillery**
- Build time is reduced for T3 mobile artillery.
- Build Time: 4800 → 4300

**Experimental Units**
- Cybran
	>- Monkeylord
		- Build Time: 15750 → 27500
		- Mass Cost: 19000 → 20000
	>- Megalith
		- Build Time: 18750 → 60 625
	>- Soul Ripper
		- Build Time: 20000 → 56250
	>- Scathis
		- Build Time: 50000 → 80000
- UEF
	>- Fatboy
		- Build Time: 21 000 → 47 500
		- Shield Recharge Time: 160 → 120
		- Shield Regen Rate: 64 → 100
		- Power Upkeep cost: 500 → 600
	>- Atlantis
		- Build Time: 14 400 → 20 500
	>- Novax Center
		- Build Time: 25 000 → 30 000
- Aeon
	>- Galactic Colossus
		- Power Cost: 343 750 → 330 000
		- Build Time: 20 625 → 51500
		- Claws:
			- Fixed a bug with the claws, credit to EQ.
			- Rate of Fire: 1 → 0.15
	>- Czar
		- Build Time: 33 750 → 50 625
	>- Tempest
		- Build Time: 14 400 → 28 000
		- Muzzle Velocity: 28 → 35
- Seraphim
	>- Ythotha
		- Build Time: 18750 → 46 875
		- Mass Cost: 25 000 → 26 500
		- Per Cost: 312 500 → 330 000
		- Phason Beam Generator Damage: 8000 → 6000
		- Gatling Plasma Cannon Damage: 550 → 610
		- Heavy Sinn Unthe Cannon Damage: 1200 → 1850
		- Fak Damage: 39 → 46
		- Flak Range: 25 → 21
	>- Ahwassa
		- Build Time: 36000 → 67500

**Navy**
- Battleships
	>- Seraphim
		- FiringRandomness: 0.3 → 0.25
		- MuzzleVelocity: 30 → 40
	>- Aeon
		- TurnRate: 35 → 40
		- MaxSpeed: 3.6 → 3.7
		- Range: 100 → 105
- Cybran Carrier
	>- Fixed the aim on the Anti Air weapon of the carrier.
- Bulwark
	>- Damage Overspill: 15% → 25%
	>- Recharge time: 35 → 40
- Shard
	>- Health: 750 → 80

**Structures:**
- T3 Land HQs
	>- Mass Cost: 4 920 → 5 220
	>- Power Cost: 43 900 → 47 400
	>- Build Time: 11 000 → 12 100
- Ravager
	>- Health: 7500 → 6500
	>- Mass Cost: 1 800 → 2 000
	>- Power Cost: 16 000 → 17 600
	>- Build Time: 1 500 → 2000
- T3 Static Artillery
	>- UEF/Cybran/Seraphim/Aeon Range: 750/700/825/900 → 825
	>- Cybran
		- Damage: 4600 → 3700
		- Rate of Fire: 0.1 → 0.13
	>- T3 Mass Fabricator
		- Adjacency from storage: 4.1667% → 3%
		- Adjacency for SML: 20% → 12.5%
- Miscellaneous
	>- T1 Mobile Anti Air
		- Aeon
			- Mass Cost: 55 → 50
			- Damage: 10 → 8
		- UEF
			- Mass Cost: 55 → 50
			- Damage: 16 → 14
		- Seraphim
			- Mass Cost: 55 → 50
			- Damage: 8 → 14
		- Cybran
			- Mass Cost: 55 → 50
			-	Damage: 10 → 9
	>- Fire Beetle
			- Damage: 3500 → 1500
			- AoE: 4.5 → 6
			- Transport class: 2 → 1
			- Stun ability added. Duration → 2s. Stuns all units except Experimentals
			- Friendly Fire → Disabled
			- Health: 300 → 500
	>- T2 Transports
			- Mass Cost: 300 → 330
			- Power Cost: 12000 → 13200
			- Speed: 15 → 14.3
	>- Aurora
			- FiringRandomnessWhileMoving: 0.3 → 0.1
			- MuzzleVelocity: 30 → 25
	>- Ahwassa
			- BombDropThreshold: 4 → 20
	>- T1 Bombers
			- RandomBreakOffDistanceMult: 1 → 1.5
	>- Selen
			- Removed the Power drain from the stealth/cloak ability while not moving.
### Gameplay
- Civilian Structures
	- Adjusted Civilian Building Mass values to make them more consistent. Civilian buildings will give 50-150 mass.
- Cybran Shield
	- Added the ED4 Shield to the list of buildable structures and to the hotbuild keygroup for shields.
- Overcharge
	- The damage dealt by overcharge now scales with the amount of energy drained from storage.
	- Overcharge will drain as much energy as is required to kill any unit within the area of effect of the OC, or 90% of your stored energy.
	- One energy storage is required to unlock Overcharge.
	- One storage is required to kill T1 and T2 land units.
	- Up to three storages will be required to kill T3 land units.
	- The range of the Area of Effect is now displayed when using Overcharge.
	- The OC indicator will turn orange if you do not have enough energy in storage to kill the unit under the cursor.
	- The OC indicator will turn green if you have enough energy in storage to kill the unit under the cursor.
	- The maximum damage is 15k at a cost of ~45k energy
	- Damage vs buildings and vs commanders is unchanged from the previous system. We have added new icons to indicate whether you have enough energy to kill the unit under your cursor.
	- Gray is for idle, Orange means you dont have enough energy to kill and green means you will kill the unit if you OC it.
- Veterancy
	- The vet gained from buildings was too high, leading to problems especially with ACU TML.
	- Veterancy gained from damaging non-combat buildings is reduced by 50%
	- Only a single vet level can be gained for any one kill.
- Teleport
	- Teleporting takes 5 seconds longer. The animation at the teleport destination is unchanged.

### Bug Fixes
- Nuke trajectory is now corrected so it travels parallel to the ground.
- Selens will no longer lose their radar when there is a power stall.
- Units with personal shields that are unloading from transports will now take damage on their health when hit.
- The seraphim T2 torp defence wreck is no longer invisible.

Contributors
CookieNoob
Exotic Retard
JaggedAppliance
MrNukealizer
Petricpwnz
PhilipJFry
speed2
Strogo
Uveso