NFS Underground on Mac
======================

Launcher for Need for Speed: Underground (PC, patch 1.4) on Apple Silicon.
You still need your own installed game. This zip does not contain the app.

The app is about 226 MB (Wine is inside it). NFSMods only accepts 50 MB,
so the download is on GitHub.

DOWNLOAD (required)
-------------------
https://github.com/dmitriymolokov/nfsu-mac/releases/download/1.0/NFS.Underground.app.zip

Page with notes:
https://github.com/dmitriymolokov/nfsu-mac

INSTALLATION
------------
1. Download NFS.Underground.app.zip from the link above and unzip it.
2. Install your own US 1.4 game.
3. Put the unpatched no-cd Speed.exe in that folder.
   The launcher only accepts this file (about 3.2 MB):

   e159b0eaaad6c02aafa956fbd306d33441e23caf47e1d12a98acce486756c621

   A disc exe that still wants SafeDisc, or an already patched exe, will not start.
4. Put NFS Underground.app next to that Speed.exe.
5. Open the app, pick a resolution and a language, press Play.
   Only the English version has in-game movies.

The first launch unpacks Wine into ~/Library/Application Support/NFSUnderground/.
Later launches reuse it. Your original Speed.exe is not overwritten.
A copy is written next to it as Speed.exe.nfsu-mac.

Resolutions: 1024x640, 1280x800, 1440x900, 1680x1050, 1920x1200.
Default is 1440x900.

Do not put your own d3d9.dll in the game folder.

The window is 16:10. The race camera stays 4:3 unless the game folder also
has ThirteenAG's widescreen fix: dinput8.dll and
scripts/NFSUnderground.WidescreenFix.asi.

NOT INCLUDED
------------
- No Speed.exe
- No game files
- The .app itself is on GitHub, not in this zip

CREDITS
-------
- athei — mtld3d and wine-build (D3D9 to Metal)
  https://github.com/athei/mtld3d
  https://github.com/athei/wine-build
- ThirteenAG — Widescreen Fix (race camera)
  https://github.com/ThirteenAG/WidescreenFixesPack
- Wine

Not affiliated with Electronic Arts. Original game (c) Electronic Arts.