# Base32 Encoding

## Install
`npm i --save @dwlib/base32-encoding`

## Usage
```javascript
// CJS
const base32Encoding = require('@dwlib/base32-encoding');
// ESM
import Base32Encoding from '@dwlib/base32-encoding';
import * as base32Encoding from '@dwlib/base32-encoding';
// Module Exports
const {
  Base32Encoding,
  BASIC,
  HEX
} = base32Encoding;

Base32Encoding.BASIC.alphabet; // => 'ABCDEFGHIJKLMNOPQRSTUVWXYZ234567'
Base32Encoding.HEX.alphabet; // => '0123456789ABCDEFGHIJKLMNOPQRSTUV'
```
