# Serenity

![unique-installs](https://img.shields.io/endpoint?style=for-the-badge&url=https%3A%2F%2Fbuild.wabbajack.org%2Fmetrics%2Fbadge%2Fserenity%2Funique_installs_badge.json)  
![build-status](https://img.shields.io/endpoint?label=%20Status&style=for-the-badge&url=https%3A%2F%2Fbuild.wabbajack.org%2Flists%2Fstatus%2Fserenity%2Fbadge.json)

- [Serenity](#serenity)
  - [Preamble](#preamble)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Change Steams Update Behavior](#change-steams-update-behavior)
      - [Set the Game language to English](#set-the-game-language-to-english)
      - [Clean Skyrim](#clean-skyrim)
      - [Start Skyrim](#start-skyrim)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy Game Folder Files](#copy-game-folder-files)
    - [Getting an ENB](#getting-an-enb)
  - [Noteworthy Mods](#noteworthy-mods)
    - [Requiem](#requiem)
    - [Quest and Encounter Mods](#quest-and-encounter-mods)
    - [Expanded Cities Towns and Villages](#expanded-cities-towns-and-villages)
    - [NPC Retextures](#npc-retextures)
    - [Followers](#followers)
    - [Audio and Weather](#audio-and-weather)
    - [New Equippables](#new-equippables)
  - [How to start up Serenity](#how-to-start-up-serenity)
  - [Updating](#updating)
  - [Creating your Character](#creating-your-character)
  - [In-Game MCM Options](#in-game-mcm-options)
    - [All Geared up Deriv](#all-geared-up-deriv)
    - [A Matter of Time (Preference)](#a-matter-of-time-preference)
    - [ESF: Companions](#esf-companions)
    - [Extended UI (Preference)](#extended-ui-preference)
    - [Follower Framework](#follower-framework)
    - [Honed Metal](#honed-metal)
    - [Immersive HUD (Preference)](#immersive-hud-preference)
    - [LOTD Settings](#lotd-settings)
    - [LOTD : The Curator's Tracker (Preference)](#lotd--the-curators-tracker-preference)
    - [Lucien (Preference)](#lucien-preference)
    - [Requiem](#requiem-1)
    - [Quick Light](#quick-light)
    - [SkyUI](#skyui)
    - [Thieves Guild Requirements](#thieves-guild-requirements)
    - [VioLens](#violens)
    - [XPMSSE (Preference)](#xpmsse-preference)
  - [FAQ](#faq)
    - [Ultrawide Options](#ultrawide-options)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
  - [Removing the Modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)
  - [Contributing](#contributing)
  - [Changelog](#changelog)

## Preamble

![serenity-banner](cover/Cover.png)

Serenity is my goal of having a vanilla Requiem experience in Skyrim Special Edition. The aim is to provide the feeling of requiem with the stability of Skyrim Special Edition as well as a slew of bug fixes, graphical improvements and Legacy of the Dragonborn integration. This is an ongoing project and changes will definitely be made along the way but the aim is to not stray away from the core Requiem experience.

Serenity uses Requiem 4.0.1 and has some armor mods supported by the Requiem Out-fitted mod and contains DLC sized mods which are

- Wyrmstooth (with requiem patch from lilmoefow)
- Dragonborn (Fozar's Patch, tweaked and modified to work for Requiem 4.0)
- Legacy of the Dragonborn (with Requiem Patch and Museum Integration)
- Vigilant

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it.

#### Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about this part as the installation will replace this graphics settings.
Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack
2. Click on Browse Modlists, and download Serenity from the gallery.
3. Once the download is done set the Installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, Desktop. Put it somewhere easy like `C:/Modlists/Serenity`). The downloads path should automatically fill in the installation path.
4. Click the Go/Begin button
5. Wait for Wabbajack to finish
6. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you loose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

**Windows is reporting that a virus has been detected**:

Windows 10 has started to auto quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2 saying a threat was detected . This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for windows defender can be found [here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Copy Game Folder Files

Download the latest ENB Series from [here](http://enbdev.com/download_mod_tesskyrimse.htm) and copy `d3d11.dll` and `d3dcompiler_46e.dll` to your game folder.

Copy the all of the files from the `MO2/Game Folder Files` directory into your game folder.

### Getting an ENB

This list uses Obsidian Weathers Weathers so you want to get an ENB that is compatible.

Once you found a preset you like. Download it and extract the enbseries folder, enbseries.ini and enblocal.ini to your Skyrim Special Edition directory.

**Note :**
Please check that vsync is set to disable in enblocal.ini otherwise you will be stuck compiling shaders.

## Noteworthy Mods

### Requiem

[Requiem](https://www.nexusmods.com/skyrim/mods/19281) is a project with the goal of turning Skyrim into a better roleplaying experience by making game more immersive, semi-realistic and coherent, with the tend to find a compromiss between old school mechanics and more modern approaches.

Requiem is the core mod behind Serenity. It overhauls the entire game with regards to Races, Combat, Standing Stones, Dragons, Perks, Difficulty and much much more. Requiem offers an unleveled world in where everything is static and doesn't level with the player.

### Quest and Encounter Mods

Serenity comes with a wide variety of new quest and encounters. A few are listed below.

[Legacy of the Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/11802) is a very large mod that shapes the way how you play the game. The museum is a very robust house mod with the ability to display almost every item in the game and also has an extensive mod support which is utilised to some extent in Serenity. Serenity also comes with a Requiem display room for it thanks to [pamposzek](https://www.nexusmods.com/skyrimspecialedition/mods/36998).

[Missives](https://www.nexusmods.com/skyrimspecialedition/mods/17576?tab=files) adds a large number of localized radiant quests found at Missive Boards of varying difficulty and with varying rewards. Missives has been extended to Solstheim as well as Wyrmstooth.

[Vigilant](https://www.nexusmods.com/skyrimspecialedition/mods/11849) adds a whole new set of quests, enemies, equipment to the game revolving around the Vigilants of Stendar and Daedra. It has also been patched to work well with Requiem. For a good time you want to be atleast level 30 before attempting this.

[Wyrmstooth](https://archive.org/details/wyrmstooth1.18SSE) adds a new world and a series of quests involving killing a dragon for a bounty. It's a very well done quest mod.

### Expanded Cities Towns and Villages

Serenity uses the full suite of [JK's Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/6289) along with all of the interior patches for it.

### NPC Retextures

I have to give credits to Darkladylexy from the popular [Lexy's Legacy of the Dragonborn Special Edition](https://lexyslotd.com) guide for her extremely well done choices of NPC mods. It is a combination of a lot of NPC mods with carefully picking which npc comes from which mod itself. For an overview of every single NPC that is retextured. Please see [this section on her guide](https://lexyslotd.com/guide/npc-retextures-page/)

The NPC retextures are largely in this order except a select few NPCs

1. WICO - Windsong Immersive Character Overhaul
2. Followers Hirelings and Housecarls
3. Metalsabers Beautiful Orcs of Skyrim
4. The Ordinary Women
5. Pandorable's NPCs
6. Kalilies NPCs
7. Fresh Faces
8. Pandorable's NPCs - Dawnguard
9. Pandorable's NPCs - Dragonborn
10. Bijin Warmaidens
11. Bijin Wives
12. Bijin NPCs
13. Seranaholic
14. Valerica
15. eeekie's Enhanced NPCs
16. RS Children Overhaul

For an overview of every single NPC that is retextured. Please see [this section on her guide](https://lexyslotd.com/guide/npc-retextures-page/).

In addition There is also NPC retextures for Interesting NPCs done by Cuyima as well as an NPC retexture for Legacy of the Dragonborn done by 1NGR.

### Followers

[Inigo](https://www.nexusmods.com/skyrimspecialedition/mods/1461) is a fully voiced khajiit adventuring companion with over 7000 lines of unique dialogue - much of it about you. He'll level alongside you and avoid most traps. If you're sneaking he won't chatter and he'll whisper if you talk to him. He can run out of arrows. He's highly skilled in archery, one-handed, and sneak.

[Lucien](https://www.nexusmods.com/skyrimspecialedition/mods/20035) is a fully voiced Imperial follower with around 3000 lines of immersive, lore-friendly dialogue. Though he arrives in Skyrim as a cowardly scholar, he'll gradually gain strength and confidence by your side until he grows into a hero in his own right.

### Audio and Weather

[Audio Overhaul Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/12466) and [Immersive Sounds Compendium](https://www.nexusmods.com/skyrimspecialedition/mods/523) offer an amazing base for skyrim's ambiance and foley.

### New Equippables

[Cloaks of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/6369) provides cloaks to various NPCs. For the purpose of balance and not to be overpowered with Requiem, the regular cloaks cannot be enchanted and the pre-enchanted cloaks have been toned down a level or two.

[Heavy Armory](https://www.nexusmods.com/skyrimspecialedition/mods/6308) adds around 100 new weapons into the game that is evenly distributed to all the enemies and NPCs.

[Requiem - OUT-Fitted](https://www.nexusmods.com/skyrimspecialedition/mods/34496) is a fantastic mod by jap2112 that incorporates nearly a dozen mods to fit into the world of Requiem. Serenity is using all but one of the suite which covers :

1. Common Clothes and Armors
2. Guard Armor Replacer
3. New Legion
4. Expanded Skyrim Weaponry
5. Blackened Steel Armor and Weapons
6. Unplayable Faction Armor
7. NordwarUA's Race Armor Expansion
8. Nordic Wanderer
9. Black Mage Armor
10. Triss Armor Retextured
11. Volkihar Knight - Vampire Armor

## How to start up Serenity

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Creating your Character

Upon entering the game you will be greeted with a notification from the Relic Notifications Mod. Hit OK and wait for another pop-up from it, usually takes about a minute.  Once it's done you can proceed with creating your character. Once you've named your character wait for all the messages in the top left to fade away then open your inventory and close it. This will start up Requiem. Once Requiem has finished its installation you may proceed with the next section. While creating your character you may receive a pop up asking you if you want to scan now or later from Relic Notifications. Hit scan now to proceed.

## In-Game MCM Options

Once the game has loaded. Wait until there are no more messages on the top left corner. Then you can hit escape and click on Mod Configuration to continue this section.
Mods or sections with (Preference) next to their name is solely preferential and do not affect the balance of the game.

### All Geared up Deriv

- Player (Preference)
  - Enable Mic Item Display : Disabled
- NPC :
  - Enable Weapons (Preference): Enabled
  - Enable Misc Item Display : Disabled (There's been numerous reports of NPCs crashing with this Enabled. Hence, it's recommended to be Disabled)

### A Matter of Time (Preference)

- Presets :
  - Load user settings

### ESF: Companions

- Presets :
  - Apply the Reasonable - 24 Quests Preset
- Joining → Thieves Guild Members :
  - Thieves Guild Members Can Join : Enabled
- Miscellaneous → Beast Blood :
  - Aela Will Offer : Unlimited

### Extended UI (Preference)

- Stats Menu
  - Hide Legendary UI Elements - Enabled
  - Show attribute modifiers - Enabled
  - Show skill modifiers - Enabled
- Console
  - Fullscreen : Enabled

### Follower Framework

- System → Save/Load Configuration :
  - Load from File : Click

### Honed Metal

- General :
  - Crafting Cost Multiplier : 0.85
  - Tempering Cost Multiplier : 0.35
  - Enchanting Cost Multiplier : 0.75
  - Recharge Cost Multiplier : 0.85
  - Materials Cost Multiplier : 1.10
- Maintenance :
  - Crafting Time : 0.5
  - Enchanting Time : 0.5
  - Recharging Time : 0.0
  - Common Materials Acquisition Time : 0.02

### Immersive HUD (Preference)

- Set this up however you like. There are some default options already tweaked
  
### LOTD Settings

- LOTD Settings → General → Shippment Crate Locations :
  - Carriages : Enabled
  - Inns : Enabled
  - Player Houses : Enabled

### LOTD : The Curator's Tracker (Preference)

- Settings → Mod Settings :
  - Live Another Life Config : Live Another Life Start

### Lucien (Preference)

- If you use a player name thats in this selection, Lucien will call you by this name

### Requiem

- Combat :
  - No non-hostile Bull Rush/Trample : Enabled
- Atmosphere :
  - Heartbeat threshold : 10%
  - Killmove health threshold : 0%
  
### Quick Light

- Quick Light → Brightness :
  - Brightness - Bright

### SkyUI

- General → Item List :
  - Font Size : Small
  - Category Icon Theme : CELTIC
- Advanced → SWF Version Checking :
  - Map Menu : Disabled
  - Favorites Menu : Disabled
  - Inventory Menu : Disabled
  - Barter Menu : Disabled
  - Container Menu : Disabled
  - Crafting Menu : Disabled

### Thieves Guild Requirements

**Note :**
This may be a little finicky when loading presets so you will have to follow the steps exactly

1) Go to Misc Options
2) Click Load Preset
3) Click on Main Quest, Radiant Quests and Misc Options again
4) Click Load Preset again. The settings will now stick.

### VioLens

- Profile System → Menu Settings :
  - Load : SERENITY

### XPMSSE (Preference)

**Note :**
Using these settings I've found to have reduced save bloat by quite a bit.

- Styles :
  - Disable Style Cloak Spell : Enabled
  - Style Fitting Animations (All) : Disabled
  - Style Fitting Dual Wield Animations (All) : Disabled
  - Style Fitting Shield Animations (All) : Disabled
  - Style Fitting Mixed Animations (All) : Disabled

The rest can be set up however you like. I personally have Swords on back

## FAQ

### Ultrawide Options

If you have an ultrawide monitor (21:9), the UI will be off. You will want to reinstall Dear Diary with the widescreen option. Pick any options on the FOMOD you want but ensure Extended UI, More Informative Console and Morehud is ticked.
You will also want to install the SkyHud - High Resolution Widescreen Fix from [here](https://www.nexusmods.com/skyrimspecialedition/mods/1778/?).

### Tweaking the Game Settings

I highly recommend using [BethINI](https://www.nexusmods.com/skyrimspecialedition/mods/4875) which is included in this Modlist (can be found in `MO2/tools/BethINI`). I recommend tweaking the `Detail` section for more FPS:

- `Shadow Resolution`: Very big one. A good balance is `2048` which is the borderline between high FPS drainage and garbage looking shadows.
- `Ambient Occlusion`: Highly recommended to turn either this or your ENB version off. Do not have the game AO and an ENB AO turned on at the same time.
- `Remove Shadows`: If you really struggle, use this. This will disable all Shadows (not recommended)

## Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- lilmoefow - for the requiem patches over on the requiem discord
- erri120 & jdsmith2816 - Repository template
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you

## Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack), I would advise checking the [Issues](https://github.com/ixanza/serenity/issues) (open **and** closed ones) on GitHub first if you have any problems. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU**.

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
