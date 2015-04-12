# basic-auth-token

[![npm](https://img.shields.io/npm/v/basic-auth-token.svg)](https://www.npmjs.org/package/basic-auth-token)  [![NPM downloads](http://img.shields.io/npm/dm/basic-auth-token.svg)](https://www.npmjs.org/package/basic-auth-token) [![Dependency Status](https://gemnasium.com/wilmoore/basic-auth-token.js.svg)](https://gemnasium.com/wilmoore/basic-auth-token.js) [![Code Climate](https://codeclimate.com/github/wilmoore/basic-auth-token.js/badges/gpa.svg)](https://codeclimate.com/github/wilmoore/basic-auth-token.js) [![Build Status](http://img.shields.io/travis/wilmoore/basic-auth-token.js.svg)](https://travis-ci.org/wilmoore/basic-auth-token.js) [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/feross/standard) [![LICENSE](http://img.shields.io/npm/l/basic-auth-token.svg)](license)

> Token generated by concatenating username and password with `:` character within a base64 encoded string.

    $ npm install basic-auth-token --save

## Example

    var token = require('basic-auth-token');
    token("Aladdin", "open sesame")
    //=> QWxhZGRpbjpvcGVuIHNlc2FtZQ==

## API

###### `token(user, pass)`

 * `user` username.
 * `pass` password.

## Reference

- [RFC2617]
- [Security Considerations]
- [Increasing Security]

## Notes

If you want the full [RFC2617] authorization header value, check out [basic-authorization-header](https://www.npmjs.com/package/basic-authorization-header).

## License

  [MIT](license)

[RFC2617]: https://tools.ietf.org/html/rfc2617#section-2
[Security Considerations]: https://tools.ietf.org/html/rfc2617#section-4
[Increasing Security]: http://security.stackexchange.com/a/27881/72283
