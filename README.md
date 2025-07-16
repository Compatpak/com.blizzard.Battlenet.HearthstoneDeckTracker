# Hearthstone Deck Tracker (Unofficial)
## Building
> **_NOTE:_**  With org.winestaging.Sdk, org.winestaging.Platform, and com.blizzard.Battlenet installed.
```console
flatpak run org.flatpak.Builder build-dir --repo=../Compatpak/repo --force-clean com.blizzard.Battlenet.HearthstoneDeckTracker.yml
```
## Installing
```console
flatpak install ../Compatpak/repo com.blizzard.Battlenet.HearthstoneDeckTracker
```
## Running
```console
flatpak run com.blizzard.Battlenet.HearthstoneDeckTracker
```
## Removing
```console
flatpak remove com.blizzard.Battlenet.HearthstoneDeckTracker
```
## Troubleshooting
- Check if Flatpak is installed
```console
flatpak list | grep HearthstoneDeckTracker
```
- Enter Flatpak in command line mode
```console
flatpak run --command=sh com.blizzard.Battlenet.HearthstoneDeckTracker
```
## Flatpak locations
- Installation directory             = /var/lib/flatpak/app/com.blizzard.Battlenet.HearthstoneDeckTracker/
- Wine prefix                        = ~/.var/app/com.blizzard.Battlenet/data/wine
