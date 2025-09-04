## Unofficial Online Auto-Installer for Two Hours One Life

This is a smart online Two Hours One Life installer built with [Inno Setup](http://www.jrsoftware.org/isinfo.php).  
It automatically fetches the latest release of [Two Hours One Life](https://github.com/twohoursonelife/OneLife) and installs it to `%APPDATA%` or a folder of your choice.  

**[Download the latest installer](https://github.com/Defalt36/TwoLifeInstaller/releases/latest/download/2HOL-setup.exe)**

## Information

- Uses [7-Zip](https://www.7-zip.org/), bundled with the repo and licensed accordingly.
- Uses [JsonParser](https://github.com/koldev/JsonParser), a public domain library for JSON parsing.

## Notes

- If installed on some folders the cache and logs will be written on %localappdata%\VirtualStore instead of the game folder.

- Auto updates will break if installed on a folder you need administrative privileges to write. Can be mitigated by running game executable as administrator.
