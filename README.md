# Wordium UI

Wordium UI is the Ember front-end layer for [Wordium](https://www.wordtalk.org). Wordium is a collaborative, structured dictionary.

[![Travis CI](https://travis-ci.org/wordium/wordium-ui.png?branch=master)](https://travis-ci.org/wordium/wordium-ui)

To get it working locally, you will need to setup the development environment to point to the API.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)
* [Bower](http://bower.io/)
* [Ember CLI](http://www.ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

## Installation

* `git clone git@github.com:wordium/wordium-ui.git` this repository
* change into the new directory
* `npm install`
* `bower install`

## Running / Development

* `ember server`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Make sure the Rails back-end ([Wordium api](http://github.com/wordtalk/wordium-api)) is also running, or else you'll see no data.

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

## Further Ember Reading / Useful Links

* [ember.js](http://emberjs.com/)
* [ember-cli](http://www.ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
