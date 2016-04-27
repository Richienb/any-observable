# any-observable [![Build Status](https://travis-ci.org/sindresorhus/any-observable.svg?branch=master)](https://travis-ci.org/sindresorhus/any-observable)

> Support any [Observable](https://github.com/zenparsing/es-observable) library and polyfill

Like [`any-promise`](https://github.com/kevinbeaty/any-promise). *(Docs are lacking here, so refer to those docs for now)*


## Install

```
$ npm install --save any-observable
```

You must also install the Observable library you want:

```
$ npm install --save zen-observable
```


## Usage

```js
const Observable = require('any-observable'); // using `zen-observable` since it's installed

Observable.of(1, 2).forEach(x => console.log(x));
//=> 1
//=> 2
```


## Related

- [is-observable](https://github.com/sindresorhus/is-observable) - Check if a value is an Observable
- [observable-to-promise](https://github.com/sindresorhus/observable-to-promise) - Convert an Observable to a Promise


## License

MIT © [Sindre Sorhus](https://sindresorhus.com)
