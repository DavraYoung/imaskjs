# imaskjs
vanilla javascript input mask

[![Build Status](https://travis-ci.com/uNmAnNeR/imaskjs.svg?branch=master)](https://travis-ci.com/uNmAnNeR/imaskjs)
[![Coverage Status](https://coveralls.io/repos/github/uNmAnNeR/imaskjs/badge.svg?branch=master)](https://coveralls.io/github/uNmAnNeR/imaskjs?branch=master)
[![npm version](https://badge.fury.io/js/imask.svg)](https://badge.fury.io/jas/imask)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lernajs.io/)

<a href="https://opencollective.com/imask/donate" target="_blank">
  <img src="https://opencollective.com/imask/donate/button.png?color=blue" width=300 />
</a>

## Features
* get and set *raw* and *unmasked* values easily
* no external dependencies
* *overwrite* mode
* **RegExp** mask
* **Function** mask
* **Number** mask (integer and decimal)
* **Date** mask (various format support, *autofix* mode)
* **Dynamic/on-the-fly** mask
* **Pattern** mask
  - show placeholder always and only when necessary
  - unmasked value can contain fixed parts
  - optional input parts (greedy)
  - custom definitions
  - reusable blocks
  - **Enum** and **Range** masks

## Plugins
* [Vue plugin](https://github.com/uNmAnNeR/imaskjs/tree/master/packages/vue-imask)
* [Angular plugin](https://github.com/uNmAnNeR/imaskjs/tree/master/packages/angular-imask)
* [React plugin](https://github.com/uNmAnNeR/imaskjs/tree/master/packages/react-imask)
* [React Native plugin<sup>beta</sup>](https://github.com/uNmAnNeR/imaskjs/tree/master/packages/react-native-imask)

## Install
`npm install imask` and `import IMask from 'imask';`

or use CDN:

`<script src="https://unpkg.com/imask"></script>`

## Build & Test
`npm run make`

## Compatibility
Supports all major browsers and IE11+ [need to support older?](https://imask.js.org/guide.html#support-older)

## Docs, Examples, Demo
[https://imask.js.org/](https://imask.js.org/)

## Many Thanks to
[@Viktor Yakovlev](https://github.com/vcrazyV)

[@Alexander Kiselev](https://github.com/MaaKut)

## Support Development
[Paypal](https://www.paypal.me/alexeykryazhev/3)
