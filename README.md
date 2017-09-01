# Devign temporary

Temporary page for Devign.it until the full website is finished.
Based on [Playground Starterkit](https://github.com/Corentinfardeau/three-js-flag) from [Corentin](http://corentinfardeau.fr/). Although I'd like to wrote all the Three.js code myself; I couldn't. Big s/o to [Vaalentin](http://vaalentin.github.io/) for the awesome dissolving background.

Following instructions are copied from the original README.md. Please contact me if you have any further questions <3

## Including
* [Gulp](http://gulpjs.com/)
* [Sass](http://sass-lang.com/)
* [Three.js](https://threejs.org/)
* [GSAP](http://greensock.com/gsap)
* [Browserify](http://browserify.org/)
* [Browsersync](https://www.browsersync.io/)
* [Babel - ES6](https://babeljs.io/)

## Before everything
- You'll need [Node](https://nodejs.org/) (which includes NPM).
- Install Gulp using `npm install -g gulp`. This installs Gulp globally and is needed later.
- Clone this repo to your local computer
- Edit project.json with your datas
- Install the nodes modules
```shell
$ npm install
```
## Run the project

There is three kind of environments available : `dev`,  `staging`, `live`. To change the config of each environement you need to edit the __project.json__ file.

- Build and watch the app with __development configs__
```shell
$ npm start
```
* Build app with __staging config__
```shell
$ npm run staging
```
* Build app with __live configs__
```shell
$ npm run live
```

### License

MIT
