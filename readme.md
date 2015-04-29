# basic-auth-token
> Token generated by concatenating username and password with `:` character within a base64 encoded string.

[![Build Status](http://img.shields.io/travis/wilmoore/basic-auth-token.js.svg)](https://travis-ci.org/wilmoore/basic-auth-token.js) [![Code Climate](https://codeclimate.com/github/wilmoore/basic-auth-token.js/badges/gpa.svg)](https://codeclimate.com/github/wilmoore/basic-auth-token.js) [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

```shell
npm install basic-auth-token --save
```

###### npm stats

[![npm](https://img.shields.io/npm/v/basic-auth-token.svg)](https://www.npmjs.org/package/basic-auth-token) [![NPM downloads](http://img.shields.io/npm/dm/basic-auth-token.svg)](https://www.npmjs.org/package/basic-auth-token) [![Dependency Status](https://gemnasium.com/wilmoore/basic-auth-token.js.svg)](https://gemnasium.com/wilmoore/basic-auth-token.js)

## Example

```js
var token = require('basic-auth-token');
token("Aladdin", "open sesame")
//=> QWxhZGRpbjpvcGVuIHNlc2FtZQ==
```

## API

### `token(user, pass)`

###### arguments

 * `user: (String)` username.
 * `pass: (String)` password.

###### returns

 * `(String)` token.

## Reference

- [RFC2617]
- [Security Considerations]
- [Increasing Security]

## Notes

If you want the full [RFC2617] authorization header value, check out [basic-authorization-header](https://www.npmjs.com/package/basic-authorization-header).

## Licenses

[![GitHub license](https://img.shields.io/github/license/wilmoore/basic-auth-token.js.svg)](https://github.com/wilmoore/basic-auth-token.js/blob/master/license)

[RFC2617]: https://tools.ietf.org/html/rfc2617#section-2
[Security Considerations]: https://tools.ietf.org/html/rfc2617#section-4
[Increasing Security]: http://security.stackexchange.com/a/27881/72283
