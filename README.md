# About

Unofficial wrapper for Claude AI, providing a native Linux desktop experience.

## Disclaimer

This project and its contributors are not affiliated with claude.ai. This is simply an Electron wrapper that loads the official Claude AI web application.

## Credits

This project is based on [gemini-desktop](https://github.com/kenvandine/gemini-desktop), originally developed by Ken VanDine and contributors.

## License

This project is licensed under the GPLv3 License. See the [LICENSE](LICENSE) file for details.

## Requirements

You will need to install [npm](https://www.npmjs.com/), the Node.js package manager. On most distributions, the package is simply called `npm`.

## Cloning the source code

Once you have npm, clone the wrapper to a convenient location:

```bash
git clone https://github.com/rhafaelcm/claude-desktop.git
```

## Building

```bash
npm install
npm start
```

On subsequent runs, `npm start` will be all that's required.

## Updating the source code

Simply pull the latest version of master and install any changed dependencies:

```bash
git checkout main
git pull
npm install
```