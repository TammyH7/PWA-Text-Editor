# Progressive Web Applications (PWA) : Text Editor

## Description.
The application is a web text editor where the user can create notes or code snippets with or without an internet connection and where the user can reliably retrieve them for later use.  The integrated service worker and Cache API's ensure that the application will remain fully functional even without and active internet connection.  This application allows the user to access visited pages even if the application is offline.

## Mock-Up

The following animation demonstrates the application functionality:

![Demonstration of the finished Module 19 Challenge being used in the browser and then installed.](/assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished Module 19 Challenge with a manifest file in the browser.](/assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished Module 19 Challenge with a registered service worker in the browser.](/assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished Module 19 Challenge with a IndexedDB storage named 'jate' in the browser.](/assets/03-idb-storage.png)

## Table of Contents:
- [Installation Process](#Installation-Process)
- [Built With](#Built-With)
- [License](#License)

## Deployed GitHub-Gist Link:

Gist link: 

## GitHub Repository

GitHub link:
https://github.com/TammyH7/PWA-Text-Editor-app


## Installation Process:

* This text editor require a number of methods and store data to an IndexedDB database to be builded up.

* This application will require the installation of Node.js and various npm packages.

*   Node Package Manager (npm) is a software manager and installer which puts the modules in place so that the node project can utilize it, and also, it manages dependency conflicts intelligently and initialized using **npm init**. The package.json will be generated and will contains all the details of the application in which the user have inputted during the npm initialization. 

## Built With:

This application will use the following npm packages:
 - npm install express (express.js)
 - npm install --save-dev webpack (Webpack)
 - npm install webpack-dev-server --save-dev (webpack-dev-server)
 - npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
 - npm install --save-dev css-loader (CSS-loader)
 - npm install babel (Babel)
 - npm install concurrently --save (run multiple commands concurrently.) (Concurrently)
 - npm npm install idb (IndexedDB)

NOTE: The required modules are bundled in the package.json file and at CLI or integrated terminal type in **npm run install**, the modules will be installed.       

## License & Copyright ©

MIT License  © 2024 All Rights Reserved.
