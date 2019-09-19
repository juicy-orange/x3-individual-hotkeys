# x3-individual-hotkeys
X3 Mod to introduce ship 30+ hotkeys for individual ship command management

## Purpose
To use VoiceAttack with X3 and command individual ships and that needs alot of hotkeys.

## How do I use it?
X3 Albion Prelude game with LxXRM 2.0 mod installed.
You install mod using Cycrow's X-Universe Plugin Manager (https://forum.egosoft.com/viewtopic.php?t=265915)
To work, this mod requires 'Hotkey Manager' by Cycrow installed.

## What does it do?
It presents you with following shortcuts:
- All Actions: opens dialog to select all available actions this plugin offers
- Select Role Ship: switches current ship role for next command
- Designate Role Ship: if target is ship you own it will open dialog that allows you to mark selected ship for custom role
- Designate Custom Locations: if target is a station or a ship, and you are allowed to dock there, you can mark selected target as named location
- Run To Safety: issues previously selected role ship to flee to jump to owned HQ, nearest Shipyard, Equipment Dock, Trade Station or any station in this particular order
- Attack My Target: issues previously selected role ship to attack selected target whatever it may be (it cannot attack if target is selected role ship)
- To Nearest Shipyard: issues previously selected role ship to jump/fly to nearest shipyard you can dock at
- To Nearest Trade Station: issues previously selected role ship to jump/fly to nearest trade station
- To Nearest Equipment Dock: issues previously selected role ship to jump/fly to nearest Equipment Dock
- To HQ: issues previously selected role ship to jump/fly to player HQ it such exist
- To Custom Location: issues previously selected role ship to jump/fly to named location selected in shown dialog
- To Location Alpha: issues previously selected role ship to jump/fly to named location
- To Location Beta: issues previously selected role ship to jump/fly to named location
- To Location Gamma: issues previously selected role ship to jump/fly to named location
- To Location Delta: issues previously selected role ship to jump/fly to named location
- Follow Me: issues previously selected role ship to follow player's ship
- Protect Me: issues previously selected role ship to attack nearby enemies of player's ship
- Collect All Wares: issues previously selected role ship to collect wares in current sector
- Dock With Me: issues previously selected role ship to dock with player's ship if possible
- Dock At Target: issues previously selected role ship to at player selected ship or station if possible
- Select Mule: selects role ship for next command
- Select Fighter: selects role ship for next command
- Select Carrier: selects role ship for next command
- Select Mobile Homebase: selects role ship for next command
- Select Support Alpha: selects role ship for next command
- Select Support Beta: selects role ship for next command
- Select Support Gamma: selects role ship for next command
- Select Support Delta: selects role ship for next command
- Show Ship Location: displays subtitle of ship's sector name, for current role ship
- Target Dock At: if target is owned ship, opens dialog to dock target at custom locations or nearest locations
- Stop Current Command: issues previously selected role ship to stop any command it might be doing
- Player To Trade Station: forces player ship to start docking at nearest trade station
- Player To Nearest Station: forces player ship to start docking at nearest (any) station
- Player To Safety: similar to 'Run To Safety', but for current player ship, a sort of panic button

Majority of commands are specific to what is called 'a role ship'. Such ship must be previously marked through 'Designate Role Ship'.
Then such ship must be selected via a hotkey or through 'Select Role Ship' to be able to receive further commands. Such ship will stay 'selected' until user selects a different role.

There are limited amount of hotkeys to select ship roles or custom locations. However, there are more options to designate and select through dialogs. Keep this in mind if you ever need more roles or locations.

## X3 Game Compatibility
This mod is tested to be fully working using LxXRM 2.0 located here: https://forum.egosoft.com/viewtopic.php?f=94&t=399184
So I would advise to install LxXRM to fully enjoy what this mod provides. As LxXRM provides different options for installation, you can choose bare minimum (support scripts it installs), which should be enough for functionality of this mod.
If you plan on using vanilla (mod-less) version of X3, certain hotkeys may not work, notably 'Collect All Wares'. However, majority of commands would work correctly.

## Development
For anybody looking to further extend functionality I find 'All Actions' hotkey to be indispensable to test available commands.