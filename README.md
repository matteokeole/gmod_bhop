## Garry's Mod local bhop server (Windows)

See also the [tutorial series](https://www.youtube.com/playlist?list=PLudurQtb5NjzF0r7hftDz4b-Xcqg2HF6X) by Gravious.

### Setup SteamCMD

1. Download SteamCMD through the [Valve Developer website](https://developer.valvesoftware.com/wiki/SteamCMD#Downloading_SteamCMD)
2. Extract the archive into `SteamLibrary\steamcmd`

### Install Garry's Mod dedicated server

1. Run `SteamLibrary\steamcmd\steamcmd.exe`
2. Type `login anonymous`
3. Type `app_update 4020 validate`

### Admin panel

1. Find your Steam ID online (it should look like `STEAM_0:1:XXX`)
1. Open `SteamLibrary\steamcmd\steamapps\common\GarrysModDS\garrysmod\gamemodes\bhop\gamemode\core_data.lua`
2. Set `OperatorID` to your Steam ID