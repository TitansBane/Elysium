![Logo](/image/Elysium_Banner.png)

# Elysium

- [Elysium](#elysium)
  - [Preface](#preface)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Change Steams Update Behavior](#change-steams-update-behavior)
      - [Clean Skyrim](#clean-skyrim)
      - [Start Skyrim](#start-skyrim)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy Game Folder Files](#copy-game-folder-files)
    - [ENB](#enb)
  - [How to start up Elysium](#how-to-start-up-elysium)
  - [Updating](#updating)
  - [Noteworthy Mods](#noteworthy-mods)
    - [Gameplay](#gameplay)
    - [Quest and Encounter Mods](#quest-and-encounter-mods)
    - [Followers](#followers)
    - [Audio and Weather](#audio-and-weather)
  - [Creating your Character](#creating-your-character)
  - [In-Game MCM Options](#in-game-mcm-options)
  - [Other Post Installation FAQ](#other-post-installation-faq)
    - [Controlmap](#controlmap)
    - [Ultrawide Options](#ultrawide-options)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
    - [Removing the Modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)
  - [Changelog](#changelog)

## Preface

Elysium is a visually focused list that is fully featured with hundreds of new additions and optional Creation Club support. Many new additions, such as Vokrii, Apocalypse, Nemesis, LotD, 3DNPC, and a wide variety of new content, were added. You should expect a more challenging game with this list. 

As for stability and conflict resolution, Elysium is base off of TPF and has been patched for the new additions to ensure consistency and compatibility across the board. In the case where patches didn't already exist or were inadequate, they have been created.

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2, and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right-click the game in your Library->Properties), navigate to the _General_ tab, and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behavior

Bethesda is still updating SSE (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. It would be best if you also disabled the Steam Cloud while you're at it.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting its contents.

#### Start Skyrim

After you have done everything above and got a clean SSE installation-ready, start the Launcher and let it do the initial graphics check. Do not worry about this part as the installation will replace these graphics settings. Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads, or Program Files folder. It's best to create a Wabbajack folder near your drive's root level like `C:/Wabbajack.`

#### Downloading and Installing

The download and installation process can take a very long time, depending on your system specs. Wabbajack will calculate the number of threads it will use at the start of the installation. To have the highest amount of threads and fastest speed, it is advised to place the working folder on an SSD.

1. Open Wabbajack.
2. Click Browse Modlists and download Elysium from the Modlist Gallery. Wait until you are forwarded to the next window.
3. Adjust the download and installation paths. The recommended Installation Path is a blank folder at the root of a drive, such as C:\Elysium. The Download Path will update automatically. You can move it elsewhere if you want.
4. Click the Go/Begin button.
5. Wait for Wabbajack to finish.

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off, so you lose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

## Post-Installation

### Copy Game Folder Files

Copy all of the files from the `Installation Folder/Game Folder Files` directory into your game folder.

 - Just to be really clear about this, since there has been some confusion: there is a folder installed by Wabbajack called "Game Folder Files." The contents of this folder are what you need to copy into your Skyrim folder. Not the folder itself, and definitely not everything that Wabbajack installed on your PC. It's just a few .dll files, skse_loader, things like that. It's only about 12 MB of files.

### ENB

Elysium comes configured with [Rudy ENB for Cathedral Weathers](https://www.nexusmods.com/skyrimspecialedition/mods/39113)

Suppose you want a different ENB. You can choose from a wide variety of ENBs on the Nexus that support Cathedral Weathers. To replace the ENB installed, delete the enbcache folder, enbseries folder, enbseries.ini, and replace those with the new ENB. You don't have to delete the enblocal.ini as that contains tweaks that don't affect how it looks but rather things like screenshot formats, vsync settings.

A few other ENB suggestions are:

- [Ljoss](https://www.nexusmods.com/skyrimspecialedition/mods/30971)
- [Silent Horizons](https://www.nexusmods.com/skyrimspecialedition/mods/21543)
- [Serio's ENB](https://www.nexusmods.com/skyrimspecialedition/mods/30506)
- [Soul Spectrum ENB](https://www.nexusmods.com/skyrimspecialedition/mods/29675)

**Note:**
Please check that vsync is set to disable in enblocal.ini otherwise you will either be stuck compiling shaders or a black screen, or the menu with no options.

## How to start up Elysium

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it is launched, there will be a dropdown box on the top right and a big run button right next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button. You have to run SKSE through Mod Organizer 2 in order to play Elysium from now on.

## Updating

If this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Noteworthy Mods

### Gameplay

Elysium uses the full suite of Enai Siaion's mods, which are:

1. [Apocalypse - Magic of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/1090)
1. [Evenstar - Minimalistic Standing Stones of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/41256)
3. [Growl - Werebeasts of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/31245)
4. [Morningstar - Minimalistic Races of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/22298)
5. [Sacrilege - Minimalistic Vampires of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/42408)
6. [Summermyst - Enchantments of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/6285)
7. [Thunderchild - Epic Shouts and Immersion](https://www.nexusmods.com/skyrimspecialedition/mods/1460)
8. [Triumvirate - Mage Archetypes](https://www.nexusmods.com/skyrimspecialedition/mods/39170)
9. [Vokrii - Minimalistic Perks of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/26176)
10. [Wildcat - Combat of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/1368)
11. [Wintersun - Faiths of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/22506)

Various other mods are used to flesh out all aspects of the game as well such as:

1. [Morrowloot Miscellania](https://www.nexusmods.com/skyrimspecialedition/mods/27094) for overhauling Skyrim's loot system.
2. [Reliquary of Myth - Artifact Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/31612) for overhauling Skyrim’s unique items.
3. [Animated Armoury - New Weapons with animations](https://www.nexusmods.com/skyrimspecialedition/mods/15394) which adds new weapons to Skyrim with custom attack animations, for both the Player and NPCs.
4. [Complete Crafting Overhaul Remastered](https://www.nexusmods.com/skyrimspecialedition/mods/28608) which overhauls the crafting component of the game.
5. [Weapons Armor Clothing and Clutter Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/18994) which fixes bugs and inconsistencies for Skyrim's weapons, armors, clothing, jewelry, and clutter items.
6. [Spell Perk Item Distributor](https://www.nexusmods.com/skyrimspecialedition/mods/36869) and [Enemy (R)evolution of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/37228) allows for enemies to use spells and perks from mod-added stuff.
7. [Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751) drastically changes how pacing in the game is accomplished. Rather than only getting experience on skill level-ups, you now gain experience level for completing quests and killing monsters.
8. [Know Your Enemy](https://www.nexusmods.com/skyrimspecialedition/mods/13807) adds trait based weakness and resistances based on armor and enemy type.

### Quest and Encounter Mods

Elysium comes with a wide variety of new quests and encounters. A few are listed below.

[Legacy of the Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/11802) is an enormous mod that shapes the way how you play the game. The museum is a very robust house mod with the ability to display almost every item in the game and also has extensive mod support, which is utilized to some extent in Elysium.

[Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194) adds over 250 fully voiced NPCs, 25+ followers, 15+ marriage candidates, and 50+ quests to flesh out the world of Skyrim fully. Every hold will feel more lively, with more NPCs walking and talking with each other.

[Missives](https://www.nexusmods.com/skyrimspecialedition/mods/17576?tab=files) adds a large number of localized radiant quests found at Missive Boards of varying difficulty and with varying rewards. Missives have been extended to Solstheim as well.

[Vigilant](https://www.nexusmods.com/skyrimspecialedition/mods/11849) adds a whole new set of quests, enemies, equipment to the game revolving around the Vigilants of Stendarr and Daedra. Vigilant has been tweaked to start at level 30 to prevent easy access to high-level gear and fighting bosses that are almost impossible to beat at lower levels.

[The Tools of Kagrenac](https://www.nexusmods.com/skyrimspecialedition/mods/14168) is a medium-sized quest that expands Arniel's Endeavor to acquire Sunder and Wraithguard, completing the trifecta.

[Forgotten City](https://www.nexusmods.com/skyrimspecialedition/mods/1179) is an excellent choice-driven quest mod with many endings surrounding the disappearance of a civilization.

[Clockwork](https://www.nexusmods.com/skyrimspecialedition/mods/4155) is a DLC-sized quest mod involving a castle high in the Velothi Mountains, which feature a obtainable player home.

[Immersive World Encounters](https://www.nexusmods.com/skyrimspecialedition/mods/18330) adds a large number of more than 70+ new random events as well as modifying some of the vanilla events.

Elysium also has a lot of modified vanilla quests such as:

1. [Save the Icerunner - Lights Out Alternate Route](https://www.nexusmods.com/skyrimspecialedition/mods/34681)
2. [Finding Deerkethus](https://www.nexusmods.com/skyrimspecialedition/mods/19550)
3. [Finding Helgi and Laelette](https://www.nexusmods.com/skyrimspecialedition/mods/28973)
4. [Finding Velehk Sain](https://www.nexusmods.com/skyrimspecialedition/mods/19815)

### Followers

[Inigo](https://www.nexusmods.com/skyrimspecialedition/mods/1461) is a fully voiced Khajiit adventuring companion with over 7000 lines of unique dialogue - much of it about you. He'll level alongside you and avoid most traps. If you are sneaking, he will not chatter, and he will whisper if you talk to him. He can run out of arrows. He is highly skilled in archery, one-handed, and sneak.

[Lucien](https://www.nexusmods.com/skyrimspecialedition/mods/20035) is a fully voiced Imperial follower with around 3000 lines of immersive, lore-friendly dialogue. Though he arrives in Skyrim as a cowardly scholar, he will gradually gain strength and confidence by your side until he grows into a hero in his own right.

### Audio and Weather

[Audio Overhaul Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/12466) and [Immersive Sounds Compendium](https://www.nexusmods.com/skyrimspecialedition/mods/523) offer an amazing base for Skyrim's ambiance and foley.

### Creation Club

Elysium has an optional MO2 profile that utilizes all Creation Club content for the Legacy of the Dragonborn and various other mods. Fully integrated into Skyrim's world and is the recommended profile for Elysium. It requires all forty-eight purchasable downloadables to start up and play.

## Creating your Character

After starting a new game, you will be dropped in the Alternate Start - Live Another Life cell where you can customise your character, then configure your mods before you actually start playing.

Stand still and wait until all messages have run through in the upper left corner (check the screenshot below). Then hit ESCAPE and create a manual save before you continue.

## In-Game MCM Options

All the required MCM options have been automated for you. Enjoy the game or tweak the following to your liking:

#### Lucien 
- (If you set a nickname that's supported he can call you by that name)

#### VIGILANT
 - No tweak here; you can manually adjust the difficulty if you find the mod too easy. Just note that this is a LATE GAME QUEST. It will make much more sense if you do it after the Dawnguard questline and the House of Horrors quest.

**Note: Dodging is provided by the Mod "The Ultimate Dodge Mod". Please head to System > Controls > Sneak and change the Keybind to whatever you want to use to dodge with. I recommend side mouse buttons. If you do not change this to something else, your character will not sneak or be stuck sneaking.**

## Other Post Installation FAQ

### Controlmap

These are currently the custom controls added by Mods. Feel free to customize them within the Mod's MCM menus

- Immersive HUD - Toggle HUD: X
- The Ultimate Dodge Mod - Dodge : Ctrl **Note to change this keybind you want to rebind the Sneak key in Skyrim Settings > Controls**
- The Ultimate Dodge Mod - Change Dodging Style : G (This changes between side-stepping and rolling) **Note your character may be stuck in the air the first time you dodge. Pressing this will fix it**

### Ultrawide Options

Adding widescreen support is a matter of replacing interface mods with compatible versions. Thankfully, there is a central mod page offering widescreen patches for pretty much every interface mod out there.

You will want to install the Complete Widescreen Fix for Vanilla and SkyUI 2.2 and 5.2 SE from [here](https://www.nexusmods.com/skyrimspecialedition/mods/1778?tab=files).

### Tweaking the Game Settings

I highly recommend using [BethINI](https://www.nexusmods.com/skyrimspecialedition/mods/4875) which is included in this Modlist (can be found in `MO2/tools/BethINI`). I recommend tweaking the `Detail` section for more FPS:

- `Shadow Resolution`: Very big one. A good balance is `2048` which is the borderline between high FPS drainage and garbage looking shadows.
- `Ambient Occlusion`: Highly recommended to turn either this or your ENB version off. Do not have the game AO and an ENB AO turned on at the same time.
- `Remove Shadows`: If you really struggle, use this. This will disable all Shadows (not recommended)

### Removing the Modlist

You can remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder, so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a lot!!
- Phoenix and her team - for creating this excellent guide and allowing me to create this fork.
- Halgari and everyone in the WJ Team - Wabbajack is incredible, and so are you!

## Contact

While I am sometimes available on the [Wabbajack Discord](https://discord.gg/wabbajack), I would advise checking the [Issues](https://github.com/TitansBane/Elysium/issues) (open **and** closed ones) on GitHub first if you have any problems. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU**.

## Changelog

See [Changelog](CHANGELOG.md).

## Licenses

- [ReShade License](RESHADELICENSE.md)

***

[[Back to top]](#elysium)
