# parse-weeks

> Parse a comma separated list of ranges and numbers into an array of all numbers covered

## Install

    $ npm install --save parse-weeks

## Usage

```js
const parseWeeks = require('parse-weeks');

parseWeeks('1')
// => [1]

parseWeeks('1, 3');
// => [1, 3]

parseWeeks('1-2, 4-5');
// => [1, 2, 4, 5]

parseWeeks('12-14, 4-5')
// => [12, 13, 14, 4, 5]
```

## Licence

MIT &copy; [Ben Evans](https://bencevans.io)