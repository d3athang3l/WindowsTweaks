# MicrosoftProducts

## Upgrade auf Winows 10/11 Pro


## Office installieren
Office entweder mit der `setup.exe` oder mit `winget` installieren. Diese ist Teil des [Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117). .XML-Dateien können [hier](https://config.office.com/deploymentsettings) erstellt werden.
> Office LTSC 2021 Professional Plus </br>
> - Access, Excel, OneNote, Outlook, PowerPoint, Publisher, Word
> </br>
> Office LTSC 2021 Professional Plus ++ </br>
> - Access, Excel, OneNote, Outlook, PowerPoint, Publisher, Word
> - zusätzlich mit Visio LTSC Professional 2021 und Project LTSC Professional 2021
</br>

```
winget intall Microsoft.Office --override "https://github.com/Pfeffimann18/MicrosoftProducts/blob/4bd347a9f1069274d7720c2d3ab0bff39826853c/Office/Office2021ProPlus.xml"
```
```
winget intall Microsoft.Office --override "https://github.com/Pfeffimann18/MicrosoftProducts/blob/4bd347a9f1069274d7720c2d3ab0bff39826853c/Office/Office2021ProPlus++.xml"
```