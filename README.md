# CleanWin
<h3 align ="center">CleanWin automates setting up Windows devices</h3>
<p align="center">
<a href="https://github.com/pratyakshm/CleanWin"><img src="https://img.shields.io/static/v1?label=pratyakshm&message=CleanWin&color=blue&logo=github" alt="pratyakshm - CleanWin"></a>
<a href="https://github.com/pratyakshm/CleanWin"><img alt="GitHub all releases" src="https://img.shields.io/github/downloads/pratyakshm/CleanWin/total?color=blue"></a>
<a href="https://github.com/pratyakshm/CleanWin"><img src="https://img.shields.io/github/stars/pratyakshm/CleanWin?style=social" alt="stars - CleanWin"></a>
<a href="https://github.com/pratyakshm/CleanWin"><img src="https://img.shields.io/github/forks/pratyakshm/CleanWin?style=social" alt="forks - CleanWin"></a>
<a href="#license"><img src="https://img.shields.io/badge/License-GPL_v3-blue" alt="License"></a>
</p>

## Brief
CleanWin does everything from removing junk (your hardware doesn't count, yet), cleaning up the Windows UI, setting up privacy policies, Windows Update policies, disabling unnecessary features and enabling useful ones meanwhile retaining maximum app functionality. It also uses [`Winstall`](https://github.com/pratyakshm/CleanWin/blob/main/doc/WINSTALL.md) and [`winget import`](https://docs.microsoft.com/en-us/windows/package-manager/winget/import) to batch install apps you want. Sounds pretty cool, eh?

## Documentation
### 💡 Read the docs before using CleanWin
| Type | Doc | 
|--------------|--------|
| Tasks CleanWin does | [`TASKS.md`](https://github.com/pratyakshm/CleanWin/blob/main/doc/TASKS.md) |
| Winstall | [`WINSTALL.md`](https://github.com/pratyakshm/CleanWin/blob/main/doc/WINSTALL.md) |
| winget import | [`WINGETIMPORT.md`](https://github.com/pratyakshm/CleanWin/blob/main/doc/WINGETIMPORT.md) |
| Frequently asked questions | [`FAQ.md`](https://github.com/pratyakshm/CleanWin/blob/main/doc/FAQ.md) |
| Reverting changes | [`REVERT.md`](https://github.com/pratyakshm/CleanWin/blob/main/doc/REVERT.md) |
| LICENSE | [`LICENSE`](https://github.com/pratyakshm/CleanWin/blob/main/LICENSE) |
| Docs folder | [`doc`](https://github.com/pratyakshm/CleanWin/tree/main/doc) |
| Wiki | [Wiki](https://github.com/pratyakshm/CleanWin/wiki) | 

***

## Prerequisites
### Windows Terminal  
Get it from [Microsoft Store](https://www.microsoft.com/store/productId/9N0DX20HK701) (recommended method for automatic updates).  
Other installation methods include: 
   - Getting the latest release from [GitHub](https://github.com/microsoft/terminal/releases)
   - Windows Package Manager CLI (winget): ``winget install --id=Microsoft.WindowsTerminal --source winget``   
### Windows version
CleanWin runs on the most recent Windows versions:
- Windows 10 21H1 
- Windows 11 21H2  
The OS must be up-to-date.  
Windows Pro or up is recommended for all features to work.   
Older Windows versions are not supported.  
### Internet connection
CleanWin needs an active internet connection for all features to work as documented.

***

## Running CleanWin
### You can use either of the two following methods
### 1. Main branch (recommended)
Open Windows Terminal as Administrator.  
To execute CleanWin, paste  
`Invoke-Expression ((New-Object System.Net.WebClient).DownloadString('https://git.io/JmqTS'))`     
**Warning:** GUI is done and dusted, its deprecated tech.
For user convenience, GUI app uninstaller is [merged as a choice into](https://github.com/pratyakshm/CleanWin/blob/main/doc/TASKS.md#cleanwin-gui) CLI now.
### 2. GitHub release
  Get the [latest release](https://github.com/pratyakshm/CleanWin/releases/latest) or [browse all releases](https://github.com/pratyakshm/CleanWin/releases).
   
***

## Known issues
Known issues are being tracked [here](https://github.com/pratyakshm/CleanWin/issues/16).  

## Contributing 
CleanWin accepts all kinds of contributions such as finding bugs, fixing bugs, adding features, removal of deprecated features and/or values, etc. I'm excited to work with the users and fellow PowerShell enthusiasts to further improve this project.

I ask that **before you start your work on a feature that you would like to request or contribute**, please read CleanWin [Principles](https://github.com/pratyakshm/CleanWin/wiki/Principles). I will be happy to work with you to figure out good approaches and provide guidance throughout feature development, and help avoid any wasted or duplicated effort.

***

## License
[GPL version 3](https://github.com/pratyakshm/CleanWin/blob/main/LICENSE) ©️ Pratyaksh Mehrotra ([@pratyakshm](https://github.com/pratyakshm)).
