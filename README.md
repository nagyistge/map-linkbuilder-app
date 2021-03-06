# HERE Link Builder

[![Build Status](https://travis-ci.org/heremaps/map-linkbuilder-app.svg?branch=gh-pages)](https://travis-ci.org/heremaps/map-linkbuilder-app)

See the [LICENSE](LICENSE) file in the root of this project for license details.

### Synopsis

**Share.here.com** URLs allow you to share HERE Objects - route, address or a POI (Point of Interest).
The `share.here.com` link will be consumed by the `share.here.com` service and your user will be redirected to an appropriate application, depending on their device.
The redirection logic is handled server-side.

[Link Builder](http://heremaps.github.io/map-linkbuilder-app/) is a simple interface to create valid `share.here.com` URLs and code snippets.

You can use the output in your application to provide location related information to your users cross-platform - web, Android and iOS.

### API Reference

For extended documentation see [here](https://developer.here.com/rest-apis/documentation/deeplink-web).

### Installation

Make sure you have already installed the latest version of Node.js (at least version 6.10.3) and NPM (Node Package Manager) and then run:

    npm install

### Running the server

    npm run server

A static http server will be started on port 5000, i.e. [http://localhost:5000](http://localhost:5000)

### Tests

Make sure your server is running and execute

    npm test

> **NOTE**: Tests rely on Firefox 47+. As described on [NPM](https://www.npmjs.com/package/selenium-webdriver), you need to download Mozilla's **[geckodriver](https://github.com/mozilla/geckodriver/releases/)** in order to run them.

### Other helpful commands

Lint:

    npm run lint

### Credits

* [selenium](https://github.com/SeleniumHQ/selenium)
* [jshint](https://github.com/jshint/jshint)
* [mocha](https://github.com/mochajs/mocha)
* [awesomplete](https://github.com/LeaVerou/awesomplete) by [Lea Verou](https://github.com/LeaVerou)
* [http-server](https://github.com/indexzero/http-server) by [indexzero](https://github.com/)
