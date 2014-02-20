*This repository is a mirror of the [component](http://component.io) module [ramitos/dots](http://github.com/ramitos/dots). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ramitos-dots`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# dots

loading animation with dots. [demo](http://ramitos.github.com/dots)

## install

```bash
$ component install ramitos/dots
```

## example

```js
var dots = require('dots');

var loading = dots(document.getElementById('loading'));

loading.start();

setTimeout(function () {
  loading.stop();
}, 5000);

setTimeout(function () {
  loading.rm();
}, 6000);
```

## api

#### dots(element[, interval])

`interval` defaults to `250ms`

#### start()

#### stop()

#### rm()

## license

MIT