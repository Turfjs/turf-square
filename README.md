turf-square
===========
[![Build Status](https://travis-ci.org/Turfjs/turf-square.svg?branch=master)](https://travis-ci.org/Turfjs/turf-square)

Calculates the minimum square bounding box for another bounding box.

```js
var square = require('turf-square')

var bbox = [0,0,5,10]]

var squared = square(bbox)

console.log(square) // [-2.5, 0, 7.5, 10]
```
