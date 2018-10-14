# DDIF
Diff Tool

## Usage

## How To Build

### Install Dependence Libraries

```
cd src
npm install
bower install
```

### Change Icons

```
npm install -g electron-icon-maker
electron-icon-maker --input=./images/ddiff.png --output=.
```

### Package App

```
npm install electron-packager -g
electron-packager --overwrite ./src ddiff --platform=darwin --arch=x64 --electronVersion=3.0.3 --icon=icons/mac/icon.icns
```

## Licence
GNU Lesser General Public License v3.0
