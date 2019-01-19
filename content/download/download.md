---
title: Download
date: 2018-11-25T00:00:00
draft: false
windows: https://github.com/OrionUO/OrionLauncher/releases/download/v1.30.0/OOrionLauncher-1.30.0-win64.zip
linux: https://github.com/OrionUO/OrionLauncher/releases/download/v1.30.0/orionlauncher-1.30.0-ubuntu-16.04-Qt5.tar.gz
linux2: https://github.com/OrionUO/OrionLauncher/releases/download/v1.30.0/orionlauncher-1.30.0-manjaro-18.02-Qt5.tar.gz
macosx: https://github.com/OrionUO/OrionLauncher/releases/download/v1.30.0/OrionLauncher-1.30.0-macOS.zip
---

RELEASE NOTES

```
2019-01-19

Finally we're here! This release marks the first Orion release with real native multiplatform support, but more than anything, this marks the first time since Ultima Online launch that we have a functional native client for Linux and MacOSX.

To get here, we invested a lot of time and did a lot of changes to the codebase that did not reflect in actual bug fixes, as this was much required so we will be able to continue going forward bringing life back to the project since it was abandoned.

Next, we hope to slowly start improving the client, but more than anything we need your help. We're looking for any developers with any experience willing to learn and so we're willing do help you learn.

Thank you and Enjoy!

Orion Launcher 1.30.0, OrionUO Client v0.1.30.0 and Orion Assistant 2.0.30.0

- New: Ubuntu 16.04+ 64bits support (Client, Launcher and Assistant)
- New: Manjaro Linux 18.02+ 64bits support (Client, Launcher and Assistant)
- New: macOS High Sierra 10.13+ support (Client and Launcher)
- Change: OrionAssist is now in the same folder as OrionUO (no more OA folder)
- Change: Orion.cuo is deprecated and unsupported, configure in OrionUO.cfg
- Change: Orion.dll is deprecated and unsupported
- Change: LoginServer, ClientVersion, Crypt and ClientType entries in OrionUO.cfg
- Change: Cryptography keys are derived automatically from client version if Crypt=yes
- Change: Client now uses SDL2, Win32 API is deprecated and unsupported
- Bugfix: #91 Client crashing on reconnect while character still in game
- BugFix: Issue with POL server where it wasn't possible to pass through a NPC
- Bugfix: Avoid crash on mobiles that flee combat by running away
- Bugfix: OA that was not always able to open doors
- New: Option to disable activating macros while in console mode (emote, whisper, party, etc.)

```

<details>
<summary>Archived Release Notes (Click to open)</summary>
```
2018-09-06

OrionUO Client v0.1.10.1
- Bugfix: Fix character selection screen with empty slots
- Bugfix: Fix character creation issue with POL server for client protocol 7.013.0
- Bugfix: Fix OrionAssistant so it receives lists for skills and spells
- Bugfix: Cleanup WispDataStreams
- Change: uo_debug.cfg has been renamed onion.cfg Please update your file.

2018-09-04

OrionUO Client v0.1.10.0
- Add PVPcaller Highlighting framework.
- Macro name bugfix
- Fix bug with not saving config
- Stop coloring GMs Yellow on Invuln
- Fix Aura Color for GM Ivuln
- Fix binary streams being modified by windows
- Fix relative pathing bug

2018-08-21

Orion Launcher v1.1.5.1
- Temporary reconstruction of updater while website is down.

Orion Assistant v2.0.16.7
- Added DisplayEquipmentInfo Journal Parsing.

2018-04-07

OrionUO Client v0.1.9.6
- Fixed client crash caused wrong reading algorithm of Corpse.def

Orion Assistant v2.0.16.6:
- Fixed application hanging after it was closed.

Orion Assistant v2.0.16.5
- Fixed crashing after script runs.

Orion Assistant v2.0.16.4
- Improved performance on scripts threading.
- Added parsing of packet 0xBF->0x10, this packet sets names after a single click on old era shards.
- Fixed issues with updating of laststatus.
- Slightly changed layout of hotkeys form. Added a Copy button for hotkeys and OK button to close the form.
- Implemented guild member tracking system in Orion Map.

OrionUO Client v0.1.9.5
- Resolved all text books bugs and missing features.
- Added a few more container gumps data.
- If you still won't be able to open certain containers after update, try deleting /OrionData/containers.txt

OrionUO Client v0.1.9.4
- Found and fixed a tiny memory leak.
- Fixed shop list displaying no names or attributes instead of names.
- Fixed emotes text and color management.
- Added screen coordinates caching based on gump id.

OrionUO Client v0.1.9.3
- Fixed crashes caused by animations patched with Body/Bodyconv.def files.

OrionUO Client v0.1.9.2
- Fixed remaining problems with journal prefixes.

OrionUO Client v0.1.9.1
- Fixed problems with reading of verdata.mul.

OrionUO Client v0.1.9.0
- Mul animation files will be read with file streams instead of being memory mapped. This fixes a couple of issues caused by virtual memory shortage for a lot of users.
- Uop animations loading speed increased on client launch.
- AnimationSequece.uop file parsing is in progress ( ~70% done )
- Fixed some cosmetic issues with fonts, text boxes and item names parsing.
- Fixed dead bonded pets not being rendered as ghosts.
- Orion client now asks for admin privileges upon launching.

OrionCrashReporter v1.0.0.0 release
- Fixed zip archive naming and added dpi awareness config

OrionUO Client v0.1.8.2
- Fixed cache updating issues with party and parsing of /accept command
- Added OrionCrashReporter.exe support and the binary itself

OrionUO v0.1.4.2
- Fixed the translation of information about the current selected world tile from the client to the assistant.

Orion Assistant v2.0.12.2
- Fixed critical bug with crash after changing the character's serial.
- Fixed the behavior of the checkbox Stay On Top.
- The interface to get the coordinates and type of the world object over which the mouse cursor is currently located is added.
- Removed garbage from the procurement dialogue control ship.

OrionUO v0.1.4.1
- Corrects the calculation of the width of the ASCII text.
- Fixed the calculation of the maximum weight for customers above version 5.
- Fixed object name queries.
- Added interface for transferring data about the current tile (in the world) under the mouse.
- A property manager has been created, now the properties should not vanish.

Orion Assistant v2.0.12.1
- Fixed a critical error that interfered with the stable operation of the program.
- The weight calculation formula has been fixed (for customers above version 5).

Orion Assistant v2.0.12.0
- Added additional checks before applying some elements of the lists that increases the stability.
- Refactoring work with a party/group has been implemented.
- Fixed "Save aero" reading process.
- Fixed InvokeVirture function issue.
- Fixed several issues with the targeting system.
- Added additional mouse buttons support.
- Added some changes in the hotkey system.
- Fixed "External Code" option when running one instance of the script.
- Named "External Code" macroses are now displayed in the list of running scripts with their given name.
- Drag & drop has been implemented in OA lists.
- Fixed crash while saving hotkeys.
- Fixed saving hotkeys.
- Added system to get the mouse coordinates in the client window. To do this, open the script editor and, with the active editor window, press Ctrl + Q.
- Read the CustomPath client.
- Fixed OpenContainer function. OA waits immediately for updating the items in the container, otherwise it returns control by timeout.
- Fixed the maximum values "Min/Mid Value" in the editor of display elements.
- Added a ship control tab -> Main tab.
- Fixed several issues with the specification of objects amount.
- Fixed MegaCiloc packets handler.
- Added profiles functionality and function of obtaining a profile.
- Added prompts and screenshots functionality.
- Buy/Sell vendor system (List editor, progress bar and other functions) has been implemented.

OrionUO Client v0.1.4.0
- Max View Range has been increased to 24 tiles.
- Fixed application of map/statics patches.
- Added automatic selection of the saved server and character.
- Fixed several issues with the context menus.
- Some debugging messages have been removed from the log.
- Fixed the displacement of the "contracted" gumps relatively to the mouse cursor.
- Fixed an issue with the dumping of items in the trade gump.
- Crashlog information has been changed.
- Changes in lightening options.
- Added CustomPath to specify a folder with OrionUO.exe.
- Optimization in calculations.
- Damage text has been fixed.
- Refactoring system of displaying text on the screen.
- Fixed several issues with display of some interface gumps.
- Now the text displayed on the screen does not go beyond it and remains in the window until the talker disappears.
- Screenshot alpha-channel has been fixed.
- Fixed worldmap size determination system.
- Fixed some issues with worldmap loading.
- Fixed a width of the chat text.
- Fixed boundaries of chat systems.
- Fixed positioning of small sized gumps.
- Server gumps have been refactored. Now the elements do not go beyond its boundaries.
- Fixed display of objects (mainly OSI).
- Fixed duplicate rows in tooltips.
- Fixed gump parser.
- Font manager has been refactored.
- Blocked unnecessary requests of tooltips, which caused disconnects.

OrionUO Client v0.1.3.0
- Rollback of packets has been implemented and extensions, which depend on the era, now operating in the correct way.
- Fixed an issue with the request for tooltips in bulk containers.
- Fixed repeated request of tooltips.
- Added events for additional mouse buttons (for the next version of the OA).
- Fixed targetting issues in the container gumps.
- Fixed "You lost connection" gump.
- Fixed saving / loading of some options (typos).
- Duplicates of sent messages (if they were sent in turn) are not added to the console stack.
- Added an option to switch between interface render modes.
- Fixed several issues with the death/corpse animations.
- Several fixes have been added to the packet handler of the pop-up menu.
- Added Intloc files support.
- The animation selection system has been optimized.

Orion Launcher v1.1.2.2
- Typo fix in agruments creation.

OrionUO Client v0.1.2.0
- Fixed some critical errors.
- Drawing process of the interface menu (gump) is now implemented using FrameBuffers instead of GL Lists (if the video card supports it), which significantly increases the performance, especially when interface is very saturated.
- Mini-map gump has been rectified.
- Gumps positioning on the screen have been fixed. From now on they might go beyond the screen to an acceptable distance (which would be at least 40 pixels on the screen).
- Fixed speech packet processing.
- Fixed an issue with the offset of elements for the menu-lists (graymenu).
- Fixed some screenshot feature issues.
- Fixed Ciloc obtaining issues.
- Several changes in the city selection screen have been added.
- Fixed a crash with an invalid index when updating animated objects.
- Fixed saving of config fields and config reboot while changing characters ID.

Orion Launcher v1.1.2.1
- Added way to move items in lists: accounts, proxy.

Orion Launcher v1.1.2.0
- Add checkbox for turn off init warnings in client.
- Added timer for check updates. Delay 15 min.

OrionUO Client v0.1.1.1
- Fixed bug with buff gump update

Orion Assistant v2.0.11.0
- Fixed items update in the corpses.
- Targetting system, which caused some crashes, has been rewritten.
- The "Sort scripts in lists" checkbox has been added to the Scripts / Hotkeys / Global config tab to sort the scripts in the drop-down lists.
- Fixed the config loading issues and while changing characters ID.
- An issue with non-standard screen scales has been fixed.

OrionUO Client v0.1.1.0
- Fixed an issue with updating buffs status gump.
- Optimizations have been implemented to reduce load and increase OrionUO stability.
- Added tooltips support for vendor gumps.
- The system for UOP files support has been rewritten.
- Added reading of the files MultiCollection.UOP, MainMisc.UOP (speech section).
- Distance of removing objects has been temporarily increased by 1 tile.
- Adjustments in the system of dragging objects from the paperdoll.
- Fixed the background color in the screenshots.
- Fixed color in some components of server gumps.
- Refactoring the loading of world maps. Support for UOP maps. Now the map cache is saved to the OrionData folder. Fixed crashes that occurred when loading maps earlier.
- Added option for auto-mapping the world map when entering the game. In order to reduce crashes and to avoid long-term loading issues, it is recommended to disable this option for old PCs especially during PvP.
- All built-in gumps were detached from the character serial ID.
- Fixed several issues of animation groups, now all animations should be displayed correctly in accordance with the original UO client (cast animation, death, blows, etc.).
- Fixed an issue with empty slots in the list of characters window. When player re-entry into the game, in the characters list window (after the server selection screen), if the list is empty - it redirects to the character creation screen (profession choice).
- Fixed a bug with reading the tiledata blocks from Verdata.mul file.
- Added an argument for setting the character's name during launch (shall be specified in the launcher).
- Amount of messages in the journal have been increased from 50 to 150.
- Mini-map gump optimization and rectification have been implemented.

Orion Assistant v2.0.10.0
- Mechanism for processing information about objects has been completely rewritten and now it corresponds to the original UO client.
- GUI mechanism (OA) has been modified, mainly on the Filters tab.
- Assistant interface and it's interaction with the client has been refactored. The communication load between OA and the client is decreased therefore the probability of crashes is much lower.
- Added the "Close" function for the gumps.
- Added "Object inspector" to display information about the object (using "_info" command). In order to activate this option, tick "Object Inspector" checkbox in Main tab list of the assistant.
- Fixed NPC name saving issue.
- Fixed properties obtaining process.
- Fixed issues in the pop-up menu of the script editor.
- Skills working process have been refactored.
- Update information on the Wiki.

OrionUO Client v0.1.0.0
- The algorithm for reading the AutoLoginName.cfg file has been fixed, now the spaces are not omitted.
- Added finalization of custom houses building system.
- Option settings are saved in text form from now (in the file orion_options.cfg in the Desktop folder and in the root folder of the UO).
- Fixed the world objects drawing system that now completely corresponds to the original UO client.
- Fixed several issues in the removed-objects packet handler.
- Added some changes in the output of debugging information.
- Fixed an issue with the colors of static objects.
- Fixed the output of the static objects name (Unicode for new clients).
- Fixed algorithm for sending anti-cheat packet.
- Fixed selection of objects in the vendor-shop gumps.
- Fixed an issue with animation indexes replacement.
- Fixed use of standard colors (from *.def files).
- Fixed algorithm for determining "NoDraw" tiles.
- Added double click action possibility to enlarge the mini-map gump.
- Some Orion control packets have been added.
- Added changes in "Plugins" interface.
- Fixed an issue with incorrect drawing component when using Resizepic function in gumps.
- Fixed drafting of a response packet for CGumpGeneric.
- Fixed condition for outputting the world objects tooltips.
- Fixed TextEntry for CGumpGeneric, the text transferred in width does not go beyond the acceptable scope.
- Fixed an issue with coordinates of Multi objects installation.
- Skills algorithm has been rewritten. Names/buttons of skills can be changed instantly from the server.

Orion Assistant v2.0.9.0
- Fixed a crash with Multi (Houses, ships) objects.
- Fixed several issues with sending empty packets of 'speech' request to the server.
- Fixed an issue with clamped hotkeys that caused some crashes.
- Fixed several issues with gump reading functions. Work with the gumps have not been finished yet.
- Added PlayWav function to play .WAV type files.
- Fixed wrong display of counters on the title.
- Some changes have been added in the object search system.

OrionUO Client v0.0.0.9
- Fixed several issues with bulletin board and its internal gumps.
- Book gumps have been fixed.
- Fixed the maximum width of in-game text objects, now it corresponds to the original UO client.
- Fixed bugs with send/request data of mega-ciloc's in the system.
- Changes in gump system that prevent the output of gumps outside the screen.
- Fixed several issues with packet parsing and buttons selection when working with Generic gumps (server gumps).
- Character steps request system is completely reworked, now it corresponds to the original UO client.
- Fixed character death animation.
- Fixed selection of the user's current locale.
- Completely redesigned drag-and-drop system for the in-game objects.
- Fixed several issues when moving objects in the trade gumps.
- Fixed an error with the uploading files.
- The option "Lock the game window" have been changed and it blocks both resizing and moving of the game window.
- Drag & drop distance has been corrected.
- Character movement/displacement have been fixed, now the game picture does not twitch.
- Added Ciloc selection for some messages in the gumps and theirs tooltips.
- Fixed the mouse cursor points.
- Fixed several issues with in-game world objects.
- Tiledata.mul data fields have been fixed, now it corresponds to the original UO client.
- Completely redesigned system of updating objects, corresponds to the original client.
- Processing of some packets have been added.
- NPC names delay has been fixed, basefont is not saved anymore.
- Added some debugging information in the log file.
- Fixed targeting and objects dragging in some gumps.
- Saving system of object colors have been fixed.
- Added option for highlighting different types of targets (beneficial, harmful, neutral).
- 'Skills' gump working logic has been changed.
- 'Object Handler 'selection has been fixed.
- Added the option to set custom offsets and open / close containers sounds.
- Fixed an issue with updating content in vendor gumps.
- Fixed several issues with closing gumps which are out of reach.
- Fixed adding versioned content to the main gump.
- Fixed color appliance to the 'xmfhtmlgumpcolor' components.
- Fixed a crash on some parts of the world map.
- Custom housing gump and builder have been added. (Test version)
- Fixed the work of prompts.
- Multiple internal optimizations have been added.

Orion Assistant v2.0.8.2
- Fixed replacing of 0 argument bug for TargetTile functions
- Fixed crashing on context menus
- Added return types for Select functions in gumps and menus
- Added cliloc parsing
- Added mega cliloc properties
- Added dpi awareness argument for win build
- Added 'cancel' keyword for menu choices
- Added bool return type for UseType/UseFromGround functions
- Added functions CreateGumpHook, WaitGump and CancelWaitGump for interactions and processing of gumps
- Fixed No death screen option. It wasn't working
- Fixed recursive searching for scroll types. It won't find scrolls inside of a spellbook anymore
- Added functionality to replace a piece of string
- Added processing of walk ack packet

OrionUO Client v0.0.0.8
- Added parsing and rendering of custom houses data sent by server ( not customization itself yet)
- Fixed issues with text entries in generic gumps
- Fixed issue with tooltip attributes not being capitalized
- Fixed issue with some reagents requirements within spellbooks for some spells
- Fixed line ending issue with books
- Fixed crashing on map gump opening
- Fixed rendering for alpha-blended objects
- Added functionality for virtues gump
- Fixed issues with garbage collection of animation textures, especially when player is moving
- Fixed issues with updating of party members status bars
- Added Impassable flag check in client files for "Hide vegeation" and "Trees to stumps" enchanced options
- Added single click equipment info display
- Fixed issues with ping packet causing disconnects on custom emulators
- Fixed all known problems with mega cliloc requests. Object handles will be displayed with server names instead of cliloc ones if server sends mega cliloc data.
- Fixed issue with displaying tooltips of items which are inside of containers
- Fixed ping value display going down to 0 when player isn't moving. Also ping packet will be sent every 20 seconds to display more recent ping data.

Orion Assistant v2.0.8.0
- Fixed crash when saving an object that does not exist in the GUI lists.
- Fixed casting spells.
- Fixed special abilities.
- Fixed an issue with journal messages, now cleaning mechanism does not clear the journal entirely when removing a specific message.
- Fixed a bug with *.UOP map files.
- Fixed the cancellation of client's target when using assistant functions related to existing in-game targets.
- Fixed the return value when retrieving the name of the object, now returns an empty string.
- Fixed crash with Dress Agent.
- Typos and inaccuracies in the GitHub's Wiki have been corrected.
- Added backlight to the assistant buttons (pictures). Thus, button can be visible when it is highlighted and pressed.
- Added global variables laststatus, lastobject.
- Added the OpenContainer function for opening containers.
- Added flags "ignorefriends" and "ignoreenemies" for search functions.
- Added checkboxes for assistant's log in order to record effects, sounds and animation packets.
- Added data output of coordinates of the maps when they are opened.
- Function ObjectExists is added to check the existance of the object in the assistant's memory.
- Added text output when using InfoGump function.
- InfoMenu function is update and can be added with additional parameter.
- Added "Reload" script button in the Scripts tab.
- New Filters tab is added: Speech filter, Text replaces, Sound filter.
- RequestName function is added to get/request the name of the object.
- Added functions: OAVersion, Connected, Time, Date, Random.
- InvokeVirture function is added.
- Added functions "JournalCount" and "JournalLine".
- SetText function for the JournalMessage object has been added.
- Added the ability to select menu elements by index or to make random choices in WaitMenu.

Orion Assistant v2.0.7.0
- Fixed mechanics of 'injured' flag. It will ignore dead characters and characters without status.
- Fixed issue with configs getting erased after crashes.
- Fixed issues with synchronisation of scripts deletion and launching from hotkeys. This should result in less crashes.
- Some fixes with menu processing.
- Searching for text in journal will work for Russian too.
- Added InfoGump command.
- Added functionality for auto targeting of tiles( ValidateTargetTile() and ValidateTargetTileRelative() ).
- Fixes in function for tiles auto searching.
- Fixed refreshing of path to autoload script on OA launch.
- Added path saving for each loaded script file ( apart for each character too )
- Added Launch() for launching of external programs.
- Added Contains() and Split() for string operations.
- Added UseAbility() for AoS abilties and UseWrestlingDisarm() and UseWrestlingStun() ( pre AoS ).
- Added saving/loading of tiles into a file for automatic tiles searching. OA/GlobalConfig/Tiles.xml.
- Added logging of incomming sounds into system journal of OA.
- Added LastJournalMessage().
- Added GetLastTargetPosition() and GetLastAttackPosition() to retrieve last known coordinates (PositionObject data type) of lasttarget/lastattack ( makes possible to throw aoe spell/explo pot on the ground where target went invisible ? )
- OA EN Wiki is fully up-to-date now.

OrionUO First version
- Fixed moving of gumps outside game screen.
- Fixed gumps moving function to work with minimized gumps as well.
- Fixed playing of wrong intro music file for older clients.
- Fixed use of AoS abilities.
- Fixed right clicking on object handle. It will close them.
- Fixed updating of object handle texture.
- Fix original macros file (from new clients) convertion.
- Fixed 'say' macro.
- Fixed item names in object handles.
- Fixed Buy/Sell gumps item container size.
- Added camel case output for cliloc strings.
- Added packets for old Wrestling Stun and Disarm requests.
- Added functionality to get data from .uop map files for OA.
- Fixed issues with window resizing at character selection screen.
- Fixed characters selection in the World.
- Fixed target handling on statusbar gump.
- Fixed calculation for abilities and ability reset.
- Fixed some vulnerabilities of the client.
- Fixed application of patches of animations.
- Fixed updation last target after ClientLastTarget function (from OA).
- Fixed cast spells (from books and macros).
- Fixed HTML data parsing.
- Fixed save/load info for default open container/paperdoll gumps coordinates.
- Added Orion version in to crashlog.
- Changed some default configuration values.

```
</details>
