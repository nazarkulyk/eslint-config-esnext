## eslint-config

### Pluggable [ESLint](http://eslint.org/docs/about/) [configs](http://eslint.org/docs/developer-guide/shareable-configs) for [ECMAScript Next](https://kangax.github.io/compat-table/esnext), [Node.js](https://nodejs.org) that you can import, extend and override

[![npm version][version-img]][npm-url]
[![npm downloads][downloads-img]][npm-url]
[![GitHub issues][issues-img]][issues-url]
[![Deps][deps-img]][deps-url]
[![Dev Deps][devdeps-img]][deps-url]

#### Usage

See individual packages

- [Recommended](https://github.com/nazarkulyk/eslint-config-esnext/tree/master/packages/recommended)
- [ESNext](https://github.com/nazarkulyk/eslint-config-esnext/tree/master/packages/esnext)

To add a git-hook to your commits, consider using [husky](https://github.com/typicode/husky)

```shell
npm install --save-dev husky
```

And in your `package.json`:

```json
  "scripts": {
    "precommit": "eslint ."
  }
```

---

#### Config

These configs are biased and opinionated, and err on the side of too many rules instead of too few. Think of them as a superset of your repo's lint config, and discard what you don't like in them. It's easy to override and disable the rules you find inconvenient.

- [Recommended](https://github.com/nazarkulyk/eslint-config-esnext/tree/master/packages/recommended)
- [ESNext](https://github.com/nazarkulyk/eslint-config-esnext/tree/master/packages/esnext)
- [ESNext Style Guide](https://github.com/nazarkulyk/eslint-config-esnext/tree/master/packages/esnext/style-guide)
- [Node.js](https://github.com/nazarkulyk/eslint-config-esnext/tree/master/packages/node)
- [Node.js Style Guide](https://github.com/nazarkulyk/eslint-config-esnext/tree/master/packages/node/style-guide)

[gitter-img]: https://badges.gitter.im/kunalgolani/eslint-config.svg
[gitter-url]: https://gitter.im/kunalgolani/eslint-config?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge
[version-img]: https://img.shields.io/npm/v/@nazarkulyk/eslint-config-recommended.svg
[npm-url]: https://www.npmjs.com/package/@nazarkulyk/eslint-config-recommended
[downloads-img]: https://img.shields.io/npm/dt/@nazarkulyk/eslint-config-recommended.svg
[deps-url]: https://github.com/nazarkulyk/eslint-config-esnext/blob/master/package.json
