# Counter-Strike 2 Sublime text highlights, autocomplete, and snippets

## Requirements
Sublime Text 4
This package is developed against build 4143 of Sublime Text.

## Preview

![Screenshot](https://repository-images.githubusercontent.com/706438692/1fc26af9-4a1f-448f-9a99-bcf9c1d6eca7)

## Installation

### OS X

Download the package and copy ```CS2``` folder from zip to:
```bash
/Users/mac_user/Library/Application Support/Sublime Text/Packages/User
```
OR
```bash
$ git clone https://github.com/unS0uL/CS2.git CS2
$ ln -s `pwd`/CS2 ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
```

### Linux

```bash
$ git clone https://github.com/unS0uL/CS2.git CS2
$ ln -s `pwd`/CS2 ~/.config/sublime-text-3/Packages/
```

### Windows

On Windows, you can use directory junctions instead of symlinks (symlinks require administrative rights; directory junctions don't):


Download the package and copy ```CS2``` folder from zip to:
```bash
%APPDATA%/Sublime Text 3/Packages/User
```
OR
```powershell
# Using PowerShell
PS> git clone https://github.com/unS0uL/CS2.git CS2
PS> cmd /c mklink /J "$env:APPDATA/Sublime Text 3/Packages/CS2" (convert-path ./CS2)
```

Alternatively, download the portable version and clone this repository directly as a subdirectory of the `Data` folder.

Open *.cfg files and enjoy

## Thanks
Big thanks Sublime text developer team for the best editor and examples for developing this packet!

Thanks (https://developer.valvesoftware.com/) and (https://cstrike2.oof.lv/) for the cvar list.

Thanks (https://github.com/kvishno/CSGO-Syntax-Sublime-Text/tree/master) and (https://github.com/gustavnikolaj/sublimetext2-csgo/tree/master) for an idea for developing that package.
