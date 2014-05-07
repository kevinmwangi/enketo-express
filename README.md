enketo-express [![Build Status](https://travis-ci.org/kobotoolbox/enketo-express.png)](https://travis-ci.org/kobotoolbox/enketo-express)
==============

A node.js version of Enketo Smart Paper developed for KoBo Toolbox.

\- UNDER ACTIVE DEVELOPMENT, NOT READY TO BE USED YET \-

### How to install

* install [Node.js](http://nodejs.org/) 0.10.26 or later if you don't have it already (check with `node -v`)
* install [Grunt Client](http://gruntjs.com) 4.4.x globally with `npm install -g grunt-cli` if you don't have it already (check with `grunt --version`)
* clone this repository
* clone git submodules (I think) with `git submodule update --init --recursive`
* install dependencies with `npm install` from the project root
* build with `grunt` from the project root

### How to run
* run with `node .` or `npm start` from project root
* you can now check that the app is running by going to ....

### How to update
* update git repository with `git pull -v`
* update git submodules with `git submodule update --init --recursive`
* re-build with `grunt`

### Developer tools
* install nodemon (`npm install -g nodemon`) and start app during development with `nodemon` to automatically restart the server when a file changes
* the easiest way to start the app in development and debugging mode with livereload is with `grunt develop` 

### Differences with [MartijnR/enketo](https://github.com/MartijnR/enketo) 

+ this one is 100% JavaScript
+ this one is much easier to install
+ this one will have cross-browser (media) file inputs
- this one will not store the application in your browser for offline launch - it requires a constant connection to the server
- this one will not store records locally in your browser - it will submit records immediately to the server
- this one will not store draft records (see previous)

### Differences with [enketo.org](https://enketo.org)

- no form authentication
- no Grid Theme
- no /forms app
- no /formtester app
