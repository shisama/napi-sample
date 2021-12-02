@shisama/napi-sample
===

This is the sample repository for napi-rs.

https://www.npmjs.com/package/@shisama/napi-sample

## Usage

Execute the following command to install this package.

```
npm install @shisama/napi-sample
```

Import the package and call the function.

```javascript
const napi = require('@shisama/napi-sample');
const { equal } = require('assert');

equal(napi.fibonacci(10), 55);
```

## LICENSE

MIT