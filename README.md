# site-desktop-packager

## Clone & Run Locally

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/malbruk/site-desktop-packager
# Go into the repository
cd site-desktop-packager
# Install dependencies
npm install
# Run the app
npm start
```

## Build

To build the application and generate .exe file, run this command:

```bash
# Build the app
npm run make
```

The .exe file is generated in this path:

`your\project\path\out\make\squirrel.windows\x64`

## Pack Site as Desktop Application

Put you web site files (html, css, js, images, etc) in `site` folder.

The main html should be named: index.html.

Build and take the .exe file 🚀
