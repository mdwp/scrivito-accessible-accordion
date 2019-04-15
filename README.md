# Scrivito Accessible Accordion
[![CMS: Scrivito](https://img.shields.io/badge/CMS-Scrivito-brightgreen.svg)](https://scrivito.com) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

An accordion React Component/Scrivito widget for the Scrivito CMS that let you store an anchor ID.

## Screenshot

![Screenshot](https://raw.githubusercontent.com/mdwp/scrivito-accessible-accordion/master/accordion-screenshot.png)

## Installation

Open your terminal.

`$ cd` to your Scrivito project

```shell
$ npm install scrivito-accessible-accordion
```

Import the widget in your javascript (e.g. in `index.js` or `Widgets/index.js`).

Add this line to your index.js:

```js
import "scrivito-accessible-accordion";
```

Also add the styling for react-accessible-accordeon a dependency of this widget.

```scss
@import "~react-accessible-accordion/dist/fancy-example.css";
```

## Features
The Scrivito Headline Widget has one extra feature compared to the *normal* headline Widget.
It can store an anchor ID. The Widget should be used in conjunction with our Scrivito Advanced Button widget which offers a link to anchors and smooth scrolling.

## Development

With `npm run build` you can build the package into `build/`.

With `npm start` you'll start a continues process, that rebuilds `build/` automatically once the source code is changed.

To add this library locally do the following in your scrivito app:

```
npm install file:<path to build folder>
```

e.g.

```
npm install file:../scrivito-accessible-accordion/build/
```

To publish the package:

```
npm i && npm run build && cd build/ && npm publish
```

## Check code quality

With `npm run eslint` and `npm run es-check` you can check your coding quality.