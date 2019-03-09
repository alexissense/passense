# @alexisanzieu/passense

![npm (scoped)](https://img.shields.io/npm/v/@alexisanzieu/passense.svg)
![npm bundle size](https://img.shields.io/bundlephobia/min/@alexisanzieu/passense.svg)

## Install

```
$ npm install @alexisanzieu/passense
```

## Usage

```js
const passense = require("@alexisanzieu/passense");

//You need to pass a string value inside the function

passense("this is a valid password");
//=>true

passense("4344");
//=>Error: The min lenght is 7 characters
//     at passense (C:\Users\alexi\Documents\Dev\local\test\node_modules\@alexisanzieu\passense\build\index.js:3:15)
```