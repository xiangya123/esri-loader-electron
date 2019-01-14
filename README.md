# esri-loader-electron

![Screenshot of electron app with an ArcGIS map](./esri-loader-electron-screenshot.png)

A fork of [electron-quick-start](https://github.com/electron/electron-quick-start) that demonstrates how to use [esri-loader](https://github.com/Esri/esri-loader) in an electron application.

## Adding esri-loader to an Electron Application

To add esri-loader to your own electron application, all you need to do is:

1. Install esri-loader w/ `npm install esri-loader`
1. Add a [container for the map or scene view](./index.html#L13-L14).
1. Add the code to load and use esri modules to [your JavaScript](./renderer.js)

See the esri-loader documentation for more information on [how to use esri-loader](https://github.com/Esri/esri-loader#usage).

The following comes from the electron-quick-start README:

## Electron Quick Start

**Clone and run for a quick way to see Electron in action.**

This is a minimal Electron application based on the [Quick Start Guide](https://electronjs.org/docs/tutorial/quick-start) within the Electron documentation.

**Use this app along with the [Electron API Demos](https://electronjs.org/#get-started) app for API code examples to help you get started.**

A basic Electron application needs just these files:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.

You can learn more about each of these components within the [Quick Start Guide](https://electronjs.org/docs/tutorial/quick-start).

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/electron/esri-loader-electron
# Go into the repository
cd esri-loader-electron
# Install dependencies
npm install
# Run the app
npm start
```

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## Resources for Learning Electron

- [electronjs.org/docs](https://electronjs.org/docs) - all of Electron's documentation
- [electronjs.org/community#boilerplates](https://electronjs.org/community#boilerplates) - sample starter apps created by the community
- [electron/esri-loader-electron](https://github.com/electron/esri-loader-electron) - a very basic starter Electron app
- [electron/simple-samples](https://github.com/electron/simple-samples) - small applications with ideas for taking them further
- [electron/electron-api-demos](https://github.com/electron/electron-api-demos) - an Electron app that teaches you how to use Electron
- [hokein/electron-sample-apps](https://github.com/hokein/electron-sample-apps) - small demo apps for the various Electron APIs

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
