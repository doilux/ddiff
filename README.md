# DDDIF
Diff Tool

## Usage
Move dddiff-darwin-x64/dddiff.app to application directory.

## How To Deploy
### Change Icons

```
npm install -g electron-icon-maker
electron-icon-maker --input=./images/dddiff.png --output=.
```

### Package App

```
npm install electron-packager -g
electron-packager --overwrite ./src dddiff --platform=darwin --arch=x64 --electronVersion=3.0.3 --icon=icons/mac/icon.icns
```

## Licence
GNU Lesser General Public License v3.0
