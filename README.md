# Helpers for supporting private class methods and fields for Acorn

[![NPM version](https://img.shields.io/npm/v/@cfware/acorn-private-class-elements.svg)](https://www.npmjs.org/package/@cfware/acorn-private-class-elements)

This is a plugin for [Acorn](http://marijnhaverbeke.nl/acorn/) - a tiny, fast JavaScript parser, written completely in JavaScript.

It provides helpers for implementing support for private class elements. The emitted AST follows [an ESTree proposal](https://github.com/estree/estree/pull/180).

## Installation

Installing this module requires taking advantage of npm's aliases feature:

```
npm install -D acorn-private-class-elements@npm:@cfware/acorn-private-class-elements
```

This will allow other acorn plugins which depend on `acorn-private-class-elements@^0.1.0` to use this module instead.

## Purpose of this fork

This fork is to obtain bug-fixes that have not been merged into the upstream project:

* Compatibility with acorn 7.x (merged upstream)
* Move mocha to devDependencies (merged upstream)
* Use `Parser.acorn` if available

Only production bug fixes will be accepted here and only if they are also submitted to upstream.

## License

This plugin is released under an [MIT License](./LICENSE).
