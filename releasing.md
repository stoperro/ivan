To do for each release
----------------------

###Pull from master

###Things to change around in the code:

 - Search for "0.50.6" in the project files and set this to 0.50.7 etcetera, depending on what the next verison is
 - Run `./autogen.sh` to generate the Autotools build system with the updated version number
 - Search for "increment" in the project files and increment the number associated with the bone files, savefiles and high score versions etc
 - Update this file (releasing.md) to the _next_ release number with the instructions for the next release

###Compile the game

###Include the following files in a zip folder for each release:

**Folder: IvanWin0507**

**Files = 10**

  - AUTHORS
  - COPYING
  - IVAN.EXE
  - LICENSING
  - msvcp50.dll
  - msvcrt.dll
  - NEWS
  - README
  - README.md
  - SDL2.dll

**Subfolder: Graphics**

**Files = 16**

  - Char.pcx
  - Cursor.pcx
  - Effect.pcx
  - Enner.pcx
  - Font.pcx
  - FOW.pcx
  - GLTerra.pcx
  - Humanoid.pcx
  - Icon.bmp
  - Item.pcx
  - IVlad.pcx
  - Menu.pcx
  - OLTerra.pcx
  - Smiley.pcx
  - Symbol.pcx
  - WTerra.pcx

**Subfolder: Script**

**Files = 9**
**Subfolders = 1**

  - char.dat
  - define.dat
  - dungeon.dat
  - glterra.dat
  - gwterra.dat
  - item.dat
  - material.dat
  - olterra.dat
  - owterra.dat

**Subfolder: Script\dungeon**

**Leave only dungeon data files in here***

###Then commit changes, with the release tag v0507
Tag can be appended to latest commit

###Push changes