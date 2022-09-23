# MicrosoftProducts

## Upgrade auf Winows 10/11 Pro
> [massgravel](https://github.com/massgravel/Microsoft-Activation-Scripts)
```
iwr -useb https://massgrave.dev/get | iex
```
<p align="center">
  <img src="https://thumbs2.imgbox.com/5d/73/06hqHSCY_t.png" width="900px">
</p>

## Office installieren (Beta)
Office entweder mit der `setup.exe` oder mit `winget` installieren. Diese ist Teil des [Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117). .XML-Dateien können [hier](https://config.office.com/deploymentsettings) erstellt werden.
> ### Office LTSC 2021 Professional Plus </br>
> - Access, Excel, OneNote, Outlook, PowerPoint, Publisher, Word
> </br>
```
winget install Microsoft.Office --override "https://github.com/Pfeffimann18/MicrosoftProducts/blob/4bd347a9f1069274d7720c2d3ab0bff39826853c/Office/Office2021ProPlus.xml"
```
</br>

> ### Office LTSC 2021 Professional Plus ++ </br>
> - Access, Excel, OneNote, Outlook, PowerPoint, Publisher, Word
> - zusätzlich mit Visio LTSC Professional 2021 und Project LTSC Professional 2021
</br>
```
winget install Microsoft.Office --override "https://github.com/Pfeffimann18/MicrosoftProducts/blob/4bd347a9f1069274d7720c2d3ab0bff39826853c/Office/Office2021ProPlus++.xml"
```
</br>

### Mit der `setup.exe`
```
setup.exe /configure Office2021ProPlus++.xml
```
</br>

## Installation mit `winget`
</br>

### Grundlegende Programme
```
winget install 7zip.7zip
winget install NordVPN.NordVPN
winget install Mozilla.Firefox
winget install Spotify.Spotify
winget install VideoLAN.VLC
winget install SoftDeluxe.FreeDownloadManager
```
### Entwicklung und Code
```
winget install Git.Git
winget install GitHub.GitHubDesktop
winget install Microsoft.VisualStudioCode
winget install Microsoft.WindowsTerminal
```

### Gaming
```
winget install Valve.Steam
winget install EpicGames.EpicGamesLauncher
```

### Sonstige
```
winget install Powersoftware.AnyBurn
winget install Apple.iTunes
winget install Apple.iCloud
winget install Notepad++.Notepad++
winget install WhatsApp.WhatsApp
winget install Telegram.TelegramDesktop
winget install Audacity.Audacity
winget install HakuNeko.HakuNeko.Nightly
```

### Linux-Subsystem
```
winget install kalilinux.kalilinux
winget install Canonical.Ubuntu.2204
winget install Debian.Debian
```