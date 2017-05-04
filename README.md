# Typed Text Buffer  [![Build Status](https://travis-ci.org/typed-typings/npm-text-buffer.svg?branch=master)](https://travis-ci.org/typed-typings/npm-text-buffer)

[![Greenkeeper badge](https://badges.greenkeeper.io/types/npm-text-buffer.svg)](https://greenkeeper.io/)

The type definition for [`text-buffer`](https://github.com/atom/text-buffer.git)

This is not complete. I only implement those that is needed for `env-atom`. Contribution welcome!

## LICENSE

MIT

## Contributing

```sh
# Fork this repo
npm install

npm run watch

# add tests, make changes, pass tests ... then [ctrl+c]
npm run publish
```

## Updating

Update `typings.json/version` to match the source version you are typing against.
e.g. if you are creating typings for `chai@3.5.0`, then:

```js
// typings.json
{
  "version": "3.5.0"
  // ...
}
```
