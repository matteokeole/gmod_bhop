## Garry's Mod local bhop server (Windows)

See also the [tutorial series](https://www.youtube.com/playlist?list=PLudurQtb5NjzF0r7hftDz4b-Xcqg2HF6X) by Gravious (original author).

### SteamCMD

1. Download SteamCMD through the [Valve Developer website](https://developer.valvesoftware.com/wiki/SteamCMD#Downloading_SteamCMD)
1. Extract the archive into `SteamLibrary\steamcmd`

### Garry's Mod dedicated server

1. Run `SteamLibrary\steamcmd\steamcmd.exe`
1. Type `login anonymous`
1. Type `app_update 4020 validate`

### Flow Network

1. Download the [Flow Network](https://github.com/matteokeole/gmod-bhop/raw/main/Flow%20Network.zip) folder
1. Copy `Flow Network\Gamemodes\Flow Network - All gamemodes\Flow Network - Bunny Hop\Start Server.bat` to `SteamLibrary\steamcmd\steamapps\common\GarrysModDS`
1. Replace `SteamLibrary\steamcmd\steamapps\common\GarrysModDS\garrysmod\cfg\server.cfg` by `Flow Network\Other\Config\server.cfg`
1. Copy `Flow Network\Gamemodes\Flow Network - All gamemodes\Flow Network - Bunny Hop\Gamemode` to `SteamLibrary\steamcmd\steamapps\common\GarrysModDS\gamemodes\bhop`

### Admin panel

1. Find your Steam ID [here](https://www.steamidfinder.com) (it looks like `STEAM_0:0:XXX`)
1. Open `SteamLibrary\steamcmd\steamapps\common\GarrysModDS\garrysmod\gamemodes\bhop\gamemode\core_data.lua`
1. Set `OperatorID` to your Steam ID

### Maps

1. Download the compressed map through an archive like [this one](https://fastdl.gflclan.com/garrysmod/maps)
1. Extract the BSP file
1. Copy the file into `SteamLibrary\steamapps\common\GarrysMod\garrysmod\maps` (and also `SteamLibrary\steamcmd\steamapps\common\GarrysModDS\garrysmod\maps` if that doesn't work)

***

*The message "Can't load essential data" may appear if the current map doesn't have start and end zones.*