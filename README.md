# pouchdb-authentication-electron-test

![A screenshot showing the electron app in use](screenshot.png)

This is a minimal Electron application based on the [Quick Start Guide](http://electron.atom.io/docs/latest/tutorial/quick-start) within the Electron documentation.

I created this project to quickly check most of the pouchdb-authentication features. This is not meant to be _the_ way to use pouchdb-authentication in an electron app. This was/is meant to be my testing ground but hopefully provides a good intro for other people who would like to use pouchdb-authentication in an electron app.

For general pouchdb inside electron usage, you may also find [hello-electron-with-pouchdb](https://github.com/nolanlawson/hello-electron-with-pouchdb) by @nolanlawson worthwhile to check out.

## To Use
make sure you are running a couchDB or pouchDB on localhost:5984. Or change the line in index.html. Also make sure to have *npm* installed.

Then:
```bash
# Install dependencies and run the app
npm install && npm start
```

Learn more about Electron and its API in the [documentation](http://electron.atom.io/docs/latest).

#### License [CC0 (Public Domain)](LICENSE.md)
