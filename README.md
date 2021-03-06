# ![Angular 1.5+ ES6 & Component API Example App](project-logo.png)

> Example Angular 1.5+ (ES6 + Components) codebase that adheres to the [RealWorld](https://github.com/gothinkster/realworld-example-apps) spec and API.

View the **[demo application](https://angularjs.realworld.io)** or **[learn how to build the application from scratch](https://thinkster.io/angularjs-es6-tutorial)**!

# Before Starting...

This fork exists to have the following changes:

 * Added [Chrome debugging for Visual Studio Code](https://code.visualstudio.com/blogs/2016/02/23/introducing-chrome-debugger-for-vs-code). This requires seperately installing the "Debugger for Chrome" extension.
 * Added sourceMap generation, to support aforementioned debugging.
 * Added Yarn.  It's just a lock file...

# Getting started

1. Clone repo
2. `npm install`
3. `gulp`

Make sure you have gulp installed globally (`npm install -g gulp`)

### Making requests to the backend API

For convenience, we have a live API server running at https://conduit.productionready.io/api for the application to make requests against. You can view [the API spec here](https://github.com/GoThinkster/productionready/blob/master/api) which contains all routes & responses for the server.

The source code for the backend server (available for Node, Rails and Django) can be found in the [main RealWorld repo](https://github.com/gothinkster/realworld).

If you want to change the API URL to a local server, simply edit `src/js/config/app.contants.js` and change `api` to the local server's URL (i.e. `localhost:3000/api`)

<br />

[![Brought to you by Thinkster](https://raw.githubusercontent.com/gothinkster/realworld/master/media/end.png)](https://thinkster.io)
