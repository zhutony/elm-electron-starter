# Elm Electron Starter
Get up and running with a cross-platform desktop app built in Elm.

![Type-Safe IPC Messages](/demo.gif)

Electron allows you to render web pages in Elm as native desktop interfaces. Electron runs a web page and manages native desktop interfaces (quit application, set global shortcut, create multiple windows, etc.) using NodeJS. See [jlord.us/essential-electron/](http://jlord.us/essential-electron/) for an excellent, readable conceptual overview of Electron.

### Main Stack
* `Electron`
* `Elm` (for the browser window part of Electron)
* `typescript` (for the NodeJS part of Electron)
* `webpack` with hot-module replacement
* `elm-test`

Elm Electron Starter uses typescript for the NodeJS code. It communicates between NodeJS/Typescript process and the Elm application using the npm package `elm-electron` to get type-safe inter-process messages.

## Setup
To run, just
```bash
git clone https://github.com/dillonkearns/elm-electron-starter.git
npm install
npm start
```

Do a project-wide case-insensitive search for `your` and fill in all instances of `yourname`, `yourappname`, etc.
