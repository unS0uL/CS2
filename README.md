# Counter-Strike 2 Sublime text highlights, autocomplete, and snippets

## Requirements
Sublime Text 4
This package is developed against build 4143 of Sublime Text.

## Preview

![Screenshot](https://private-user-images.githubusercontent.com/22941824/342741378-e61f4c59-c590-421a-9bb0-3bafdb8aed36.jpeg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTkzMjE2NTEsIm5iZiI6MTcxOTMyMTM1MSwicGF0aCI6Ii8yMjk0MTgyNC8zNDI3NDEzNzgtZTYxZjRjNTktYzU5MC00MjFhLTliYjAtM2JhZmRiOGFlZDM2LmpwZWc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNjI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDYyNVQxMzE1NTFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT02ODkxOTk5MmY1OGZiZDM1OTViNzYzMDdkODI1NjM5OGJlMGQ3YmIwMmQ2YWY3MjNjZDc3M2VjZDg4ZTFiYjYyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.RpBC-6Iz1B_YJixmsouONR8DYmYcqmjwv7CEXw9oLu4)

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
