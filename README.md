pkg-packager-appdmg
===================

> A [pkg-packager][pkg-packager] to build macOS bundles (.app) and Apple Disk Images (DMG).

## Installation

```sh
$ npm install pkg-packager-appdmg
```

## Usage

> TODO

```js
$ echo 'console.log("hello world")' > hello.js
$ pkg-package --type appdmg hello.js ## assumes `macos` as host
$ open ./build/x64/macos/hello.dmg
```

## License

MIT

[pkg-packager]: https://github.com/little-core-labs/pkg-packager
