# redux-stack

A react/redux boilerplate for personal use.

<img src='https://www.dropbox.com/s/r3q2da52xbihpyq/octopus.jpg?raw=1' width='400px'>

## Requirements

+ NodeJS

## Tech Stack

* [express](http://expressjs.com/) - Server HTTP framework
* [react](https://facebook.github.io/react/) - View layer
* [redux](https://github.com/reactjs/redux) - Frontend state management
* [react-css-modules](https://github.com/gajus/react-css-modules) - CSS modules
* [babel](https://babeljs.io/) - ES6/JSX compiler
* [webpack](https://webpack.github.io/) - Module bundler
* [mocha](https://mochajs.org/) - Testing

## Setup

Install dependencies:

```sh
$ npm install
```

Start the server:

```sh
$ npm start
```

To run the server in release mode, set the environment variable `NODE_ENV=production`

## Test

Run tests:

```sh
$ npm test
```

Watch and re-run tests:

```sh
$ npm test:watch
```

## Release

Generate a release build in `dist/`:

```sh
$ npm run build
```
