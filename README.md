# windoomgrader

windoomgrader is a Windows 10 reimplementation of doomgrader. It downgrades Doom Eternal to a stable version that does not use Denuvo Anti Cheat (DAC).

Linux users should use [the original doomgrader script](https://github.com/lpww/doomgrader) instead of this.

If you do not trust [this script](doomgrader.ps1) or you do not trust [depotdownloader](https://github.com/SteamRE/DepotDownloader) then **DO NOT RUN THIS**. The author assumes no responsibility whatsoever.

## Instructions

1. Install the latest [Microsoft .NET Core Runtime](https://dotnet.microsoft.com/download/dotnet-core/current/runtime).
1. Install Doom Eternal using Steam but do not launch it.
1. Note the install path for Doom Eternal. You can find it by right clicking it in your Steam Library, clicking properties, going to the local files tab, and clicking the "browse local files button".
1. Run [doomgrader.ps1](doomgrader.ps1) in PowerShell. You will be prompted for:
    - A path for downloaded depots. Make sure you have about 35.9 GB of free space.
    - The path to your Doom Eternal installation. This needs about 43.8 GB of space.
    - Your Steam username, password, and (if applicable) a Steam Guard code. These are used by [depotdownloader](https://github.com/SteamRE/DepotDownloader).

If a new update is released for Doom Eternal then Steam may apply that update at any time. If your downgraded installation gets re-upgraded then you will have to rerun the script.

For this reason it's recommended to leave the downloaded depot files alone even though they take up a lot of space.