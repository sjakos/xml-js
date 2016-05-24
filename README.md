![Alt text](/logo.png?raw=true "Logo")

[![Build Status](https://ci.appveyor.com/api/projects/status/0ky9f115m0f0r0gf?svg=true)](https://ci.appveyor.com/project/nashwaan/xml-js)
[![Build Status](https://travis-ci.org/nashwaan/xml-js.svg?branch=master)](https://travis-ci.org/nashwaan/xml-js)
[![Build Status](https://circleci.com/gh/nashwaan/xml-js.svg?style=sheild)](https://circleci.com/gh/nashwaan/xml-js)
[![bitHound Overall Score](https://www.bithound.io/github/nashwaan/xml-js/badges/score.svg)](https://www.bithound.io/github/nashwaan/xml-js)
[![Coverage Status](https://coveralls.io/repos/github/nashwaan/xml-js/badge.svg?branch=master)](https://coveralls.io/github/nashwaan/xml-js?branch=master)
[![Code Climate](https://codeclimate.com/github/nashwaan/xml-js/badges/gpa.svg)](https://codeclimate.com/github/nashwaan/xml-js)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/f6ed5dd79a5b4041bfd2732963c4d09b)](https://www.codacy.com/app/ysf953/xml-js?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=nashwaan/xml-js&amp;utm_campaign=Badge_Grade)

[![Dependency Status](https://david-dm.org/nashwaan/xml-js.svg)](https://david-dm.org/nashwaan/xml-js)
[![npm](http://img.shields.io/npm/v/xml-js.svg)](https://www.npmjs.com/package/xml-js)
[![License](https://img.shields.io/npm/l/xml-js.svg)](LICENSE)

Convert XML text to Javascript object (and vice versa) or to JSON text (and vice versa):

![Alt text](/synopsis.png?raw=true "Synopsis Diagram")

## Code Example

Quick start:

```xml
<?xml version="1.0" encoding="utf-8"?>
<note importance=”high” logged=”true”>
    Watch out!
    <time>
        11:00 am
    </time>
</note>
```

## Motivation

There are many XML to JavaScript/JSON converters out there, but could not satisfy the following requirements:

 * Compliant
 * Fast
 * Support streaming

## Installation

```bash
npm install --save xml-js
```

## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests

To perform tests on this project:

```
cd node_modules/xml-js/test
npm test
```

## Contributions

### Reporting

Use [this link](https://github.com/nashwaan/xml-js/issues) to report an issue or bug. Please include a sample code or Jasmine test spec where the code is failing.

### Contributing

If you want to add a feature or fix a bug, please fork the repository and make the changes in your fork. Add tests to ensure your code is working properly, then submit a pull request.

## License

[MIT](https://github.com/nashwaan/xml-js/blob/master/LICENSE)