# dehumanize-date

Parse dates in all the formats humans like to use:

 - today/tomorrow/yesterday
 - next/this/last Wednesday
 - 12th January
 - 12th January 1950
 - 09-08-2008
 - 2008-08-09

Return dates in just the format that computers should use:

 - 2008-08-09

[![Build Status](https://img.shields.io/travis/ForbesLindesay/dehumanize-date/master.svg)](https://travis-ci.org/ForbesLindesay/dehumanize-date)
[![Dependency Status](https://img.shields.io/gemnasium/ForbesLindesay/dehumanize-date.svg)](https://gemnasium.com/ForbesLindesay/dehumanize-date)
[![NPM version](https://img.shields.io/npm/v/dehumanize-date.svg)](http://badge.fury.io/js/dehumanize-date)

[![testling badge](https://ci.testling.com/ForbesLindesay/dehumanize-date.png)](https://ci.testling.com/ForbesLindesay/dehumanize-date)

## Installation

    $ npm install dehumanize-date

## Usage

A simple function which takes a string as an argument and returns a string in the form `yyyy-mm-dd`.

```javascript
var date = dehumanizeDate(userInput);
```

If you want to use US formats for numerical dates you should pass `true` as the second parameter:

```javascript
var date = dehumanizeDate(userInput, true);
```

## License

MIT
