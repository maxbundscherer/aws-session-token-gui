## Changes to origin
- Get access-token from aws not id-token (forked from **innFactory**)

## Let's get started
1. ``npm install`` (install dependencies)
2. ``npm start`` (run project on your device)
3. (Opt) ``npm run package`` (package project - see ``./release/``)

# Get a Amazon Web Service Token via GUI
A small proof of concept with React, Electron and AWS-SDK. 
More Infos in German - [innFactory.de/blog](https://innfactory.de/blog/52-javascript-desktop-app-electron)

<img src="screenshot.PNG" width="90%">

<br />
<br />

Install dependencies:
```
$ cd aws-access-token-gui
$ npm install
```

Package the app for your local platform:
```
$ npm run package
```

<br />
<br />

## Architecture
<img src="architecture.png" width="80%">

## Dependencies

electron-react-boilerplate<br />
https://github.com/chentsulin/electron-react-boilerplate

<br />

material-ui<br />
https://github.com/callemall/material-ui

<br />

reflexbox<br />
https://github.com/jxnblk/reflexbox

<br />

electron-json-storage<br />
https://github.com/jviotti/electron-json-storage

<br />

aws-sdk-js<br />
https://github.com/aws/aws-sdk-js
