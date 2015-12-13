# Mozlando Frontend Demo

Original sample code is on [erikras/react-redux-universal-hot-example](https://github.com/erikras/react-redux-universal-hot-example/).

This is an experiment to test out what Redux + React + universal JS looks
like as a demo Addons front-end.

The idea to it to try and do the following:

* Create a basic fake search API that returns random data.
* Create a basic search result page.
* Play with forms that work server-side only as well as via redux.
* It doesn't need to look pretty though we can hack together some styles.

## Getting started

* You'll need `nvm` + `node 4.x` + `npm 3.x` to be able to install the node
  deps. You may need to `npm install -g npm` after updating node.
* Once you have that install the deps with `npm install`.
* To fire things up use `npm run dev`.
* The redux devtools can be shown with `ctrl+shift+h`.

## Building for full universal functionality

CSS for example only fully works with JS when running the dev server.

To see the built-code running fully as a universal app you can built and run
it in production mode with:

```
npm run build
npm run start
```
