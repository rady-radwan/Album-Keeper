# Album Keeper

A Windows app for organizing photos and videos into dated albums and categories, without ever changing the original files.

## Download

[**Download AlbumKeeper-Setup-1.0.1.exe**](https://github.com/rady-radwan/Album-Keeper/raw/main/AlbumKeeper-Setup-1.0.1.exe) (78 MB, Windows 10/11, 64-bit), then double-click it to install. No admin rights needed.

SHA-256: `04D328BC11C98873FD982C690BC57650AE057CAFCC302B45480CD593686494D4`

Windows may show "Windows protected your PC" because the app isn't signed by a known publisher. Click **More info**, then **Run anyway**.

## What it does

- Albums with a name, a date or date range, and a description
- Sort albums by date, by name, by when you created them, or drag them into your own order
- Categories that hold several albums (for example Travel or Family)
- One photo can be in many albums; it's stored only once
- Originals are copied byte for byte and checked with a SHA-256 fingerprint
- Save any photo, a selection, or a whole album back to your computer as the exact original files
- Viewer with zoom and camera details, slideshow, favorites, captions and search

Your library is kept in `Documents\Album Keeper Library`. Uninstalling the app doesn't delete it.

If your security software blocks the Documents folder, Album Keeper keeps the library in `%LOCALAPPDATA%\Album Keeper\Library` instead and tells you so. You can choose another folder in Settings.

## What's new in 1.0.1

- Fixes the app staying invisible in the background when Windows or security software blocks the Documents folder
- The window now always opens, and any startup problem is explained on screen
- Adds a log file (Settings → Open log folder) to help diagnose problems
