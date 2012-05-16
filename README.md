#JGM fork

Added support for hogan.js (see https://github.com/danshultz/hem)

To install: make sure you've removed any existing versions (look in /usr/local/lib/node_modules and/or ~/node_modules), clone this repo, then run the following from the newly created hem dir

    npm link 

--------------------------------------------------------------------------------------------------------

#Introduction

Hem is a project for compiling CommonJS modules when building JavaScript web applications. You can think of Hem as [Bundler](http://gembundler.com/) for Node, or [Stitch](https://github.com/sstephenson/stitch) on steroids. 

This is rather awesome, as it means you don't need to faff around with coping around JavaScript files. jQuery can be a npm dependency, so can jQueryUI and all your custom components. Hem will resolve dependencies dynamically, bundling them together into one file to be served up. Upon deployment, you can serialize your application to disk and serve it statically. 

#Installation

    npm install -g hem

#Usage

Please see the [Hem guide](http://spinejs.com/docs/hem) for usage instructions.