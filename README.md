# FYM App - Outlook Mail

An Electron-based client for MS Outlook.

## Pre-Request
The latest version of git, node and npm installed on your system. Clone the repo using this command.

```
git clone https://github.com/mjakal/fym-app.git
```

## How to run in development mode

cd into fym-app folder and run these commands.

```
npm install
npm start
```
## How to build for production

cd into fym-app folder and run this command.

```
npm run dist
```

When done, your distributable package will be placed inside /dist folder.

To build for other platforms, open package.json with your favorite text editor and edit the line below.

```
"dist": "build -l --x64"
```

-l flag represents linux os, modify this flag depending on you os.
options: [-m -w -l] (Mac|Windows|Linux).