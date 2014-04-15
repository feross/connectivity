# connectivity [![npm](https://img.shields.io/npm/v/connectivity.svg)](https://npmjs.org/package/connectivity)

#### Detect if the network is up (do we have connectivity?)

![internet!](https://raw.githubusercontent.com/feross/connectivity/master/img.jpg)

The module answers the most important question: is the cat picture delivery system (internet) working?

### usage

```js
var connectivity = require('connectivity')

connectivity(function (online) {
  if (online) {
    console.log('connected to the internet!')
  } else {
    console.error('sorry, not connected!')
  }
})
```

Also works in the browser with [browserify](http://browserify.org/)!

### license

MIT. Copyright [Feross Aboukhadijeh](https://www.twitter.com/feross).
