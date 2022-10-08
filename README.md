# electron-login-screen

A simple project template for starting Electron Projects, using tailwindcss and node js. 

**Clone and run for a quick way to see Electron in action.**

<a ><img src="https://i.ibb.co/ct7BwxP/Screenshot-from-2022-09-20-11-39-59.png" alt="Screenshot-from-2022-09-20-11-39-59" border="0"></a>


A basic Electron application needs just these files:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.
- `preload.js` - A content script that runs before the renderer process loads.


## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git https://github.com/mintech-dot/electron-login-screen
# Go into the repository
cd electron-login-screen
# Install dependencies
npm install
# Run the app
npm start
```

## Resources for Learning Electron

- [electronjs.org/docs](https://electronjs.org/docs) - all of Electron's documentation
- [Electron Fiddle](https://electronjs.org/fiddle) - Electron Fiddle, an app to test small Electron experiments

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
