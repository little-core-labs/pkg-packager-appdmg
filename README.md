pkg-packager-dmg
================

> A [pkg-packager][pkg-packager] builder for Apple Disk Images (DMG).

## Installation

```sh
$ npm install pkg-packager-dmg
```

## Usage

> TODO

```js
$ echo 'console.log("hello world")' > hello.js
$ pkg-package --type dmg hello.js ## assumes `macos` as host
$ open ./build/x64/macos/hello.dmg
```

## License

MIT

[pkg-packager]: https://github.com/little-core-labs/pkg-packager
