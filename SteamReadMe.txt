[h1]Auto Upgrade Selected Crew[/h1]


Allows the user to invoke the "auto upgrade skills" on only selected crew members.

Press the mod's hotkey (by default Left Bracket) to upgrade.  Can be changed in the config.

This allows the user to be selective on which crew are upgraded, or auto upgrade even after the "auto upgrade" dialog has been closed.

[h1]Steam Workshop[/h1]

For Steam Users, subscribing to this mod does not install the mod.
Follow the instructions in Installation section below.

[h1]Compatibility[/h1]
[list]
[*]Some mods instruct the user to overwrite the game's original files.  This mod may not be compatible with those mods.
[list]
[*]This mod does not affect the original game files.
[/list]
[*]Safe to add and remove from existing saves.
[/list]

[h1]Configuration[/h1]

The configuration file will be created on the first game run and can be found at [i]<Steam Directory>\steamapps\common\Shortest Trip to Earth\BepInEx\config\AutoUpgradeSelectedCrew.cfg[/i].  The changes will take effect the next time the game is run.
[table]
[tr]
[td]Name
[/td]
[td]Default
[/td]
[td]Description
[/td]
[/tr]
[tr]
[td]UpgradeKey
[/td]
[td]LeftBracket
[/td]
[td]The hotkey to upgraded the selected crewmembers
[/td]
[/tr]
[/table]

[h1]Support[/h1]

If you enjoy my mods and want to buy me a coffee, check out my [url=https://ko-fi.com/nbkredspy71915]Ko-Fi[/url] page.
Thanks!

[h1]Installation[/h1]

This section covers how to install the BepInEx mod loader and the mod itself.

[h2]BepInEx Setup[/h2]

If BepInEx has already been installed, skip to the Mod Install section.
[list]
[*]Download BepInEx from https://github.com/BepInEx/BepInEx/releases/download/v5.4.23.2/BepInEx_win_x64_5.4.23.2.zip
[*]Extract of the BepInEx zip file into the game's directory:
[i]<Steam Directory>\steamapps\common\Shortest Trip to Earth[/i]
[*]Move all of the files in the new [i]BepInEx_win_x64_5.4.23.2[/i] folder to the game's root directory.
[*]If installed correctly, the following folders and files will exist in the game's directory:
[/list]
[code]
<Game Directory>
│   doorstop_config.ini
│   ST Earth.exe
├───BepInEx
├───Data
[/code]
[list]
[*]Run the game.  Once the main menu is shown, exit the game.
[*]If the install was successful, there will now be a [i]<Game Directory>/BepInEx/plugins[/i] directory.
[/list]

[h2]Mod Install[/h2]
[list]
[*]Download the AutoUpgradeSelectedCrew.zip.
[list]
[*]If on Nexumods.com, download from the Files tab.
[*]Otherwise, download from https://github.com/NBKRedSpy/STTE-AutoUpgradeSelectedCrew/releases/
[/list]
[*]Extract the contents of the zip file into the [i]<Game Dir>/BepInEx/plugins[/i] folder.
[*]Run the Game.  The mod will now be enabled.
[/list]

[h1]Uninstalling[/h1]

[h2]Uninstalling This Mod Only[/h2]

This method removes this mod, but keeps the BepInEx mod loader and any other mods.

Delete the directory [i]<Steam Directory>\steamapps\common\Shortest Trip to Earth\BepInEx\plugins\AutoUpgradeSelectedCrew[/i].

[h2]Uninstall the Mod and BepInEx[/h2]

This resets the game to an unmodded state by deleting BepInEx and any BepInEx mods.

Delete the following files and folders in the game's directory:
[code]
BepInEx  (<-- Folder)
.doorstop_version
changelog.txt
doorstop_config.ini
winhttp.dll
[/code]

[h1]Credits[/h1]

[url=https://www.flaticon.com/free-icons/arrows]Arrows icons created by Pixel perfect - Flaticon[/url]

[h1]Change Log[/h1]

[h2]1.0.0[/h2]
[list]
[*]Release
[/list]

[h1]Source Code[/h1]

Source code is available on GitHub at https://github.com/NBKRedSpy/STTE-AutoUpgradeSelectedCrew
