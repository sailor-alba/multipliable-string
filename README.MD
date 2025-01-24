# multipliable-string [![NPM version](https://img.shields.io/npm/v/multipliable-string.svg?style=flat)](https://www.npmjs.com/package/multipliable-string) [![NPM monthly downloads](https://img.shields.io/npm/dm/multipliable-string.svg?style=flat)](https://npmjs.org/package/multipliable-string) [![NPM total downloads](https://img.shields.io/npm/dt/multipliable-string.svg?style=flat)](https://npmjs.org/package/multipliable-string)

> A class for creating a multipliable strings, which you can multiply as same, as in Python

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save multipliable-string
```

## Usage

You can import class `MultipliableString` and work with it as same, as with `String` class in JavaScript. For multiply you should call the `multiply()` method.

```js
const MultipliableString = require('multipliable-string');

console.log(`Javascript goes b${new MultipliableString('r').multiply(30)}`); //=> Javascript goes brrrrrrrrrrrrrrrrrrrrrrrrrrrrrr

const myVar = new MultipliableString('Test');
console.log(myVar.multiply(10)); //=> TestTestTestTestTestTestTestTestTestTest
```

### Author

**Demon of indifference**

* [GitHub Profile](https://github.com/d-indifference/)
* [Twitter Profile](https://twitter.com/d_indifference)

### License

Copyright © 2021, [Demon of indifference](https://twitter.com/d_indifference).
Released under the [MIT License](LICENSE).

***
