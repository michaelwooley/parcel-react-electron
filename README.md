# parcel-react-electron

A minimal React.js + SASS + Electron boilerplate with [parcel as bundler](https://github.com/parcel-bundler/parcel). Parcel is an alternative web application bundler to Webpack.

## Installation

```bash
$ git clone https://github.com/michaelwooley/react-parcel-sass-electron-boilerplate.git

$ cd react-parcel-sass-electron-boilerplate

$ npm i
```

## Usage

### Development mode

Run this command to start dev server and Electron app:

```bash
$ npm run dev
```

### Production mode and packaging app

Run this command to bundle code in production mode

```bash
# Parcel bundle code once and create executables
$ npm run build
```

## Changes relative to `Snjoo/parcel-react-electron`

- Add SASS
- Change file organization so that all app code contained in `src` directory.
- Changed scripts so that can develop/build in one command
  - **WINDOWS NOTE:** in the script `dev:electron` we set an environmental variable assuming Windows: `set ELECTRON_START_URL=http://localhost:1234`. On unix-style systems just use: `ELECTRON_START_URL=http://localhost:1234`
- Add default pop-up of developer tools in development mode.
- Add default context menu.
