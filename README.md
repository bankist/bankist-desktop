# Bankist desktop

Simple [Electron](http://electronjs.org) application to install [Bankist app](https://bankist.xyz) in MacOS

![Bankist desktop](screenshot-1.png?s=200)
![Bankist desktop](screenshot-2.png?s=200)

## Getting started

- Clone the [Bankist app repository](https://github.com/bankist/bankist)
- Clone this repository at the same level
- `cd bankist`
- `npm install` to install Bankist app dependencies
- `npm run ionic:build --prod` to build the Bankist app
- Copy the `www` folder to a `html` folder inside the Bankist desktop project
- `cd bankist-desktop`
- `npm install` to install the application's dependencies
- `npm start` to start the application
- `npm run dist` to build the application to the dist folder
