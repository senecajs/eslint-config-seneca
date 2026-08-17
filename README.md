![Seneca](http://senecajs.org/files/assets/seneca-logo.png)
> A [Seneca.js][] plugin

# @seneca/eslint-config

| ![Voxgig](https://www.voxgig.com/res/img/vgt01r.png) | This open source module is sponsored and supported by [Voxgig](https://www.voxgig.com). |
|---|---|

## Install

To install, simply use npm,

```bash
npm install eslint-config-seneca eslint-plugin-standard eslint-plugin-hapi
```

__Note:__ If you are using ESLint v1 use v1.x.x. If you are using ESLint v2 use 2.x.x.

## Quick Example

Create an `.eslintrc` file with the following contents.

```json
{
  "extends": "seneca"
}
```

Once created ESLint will auto load the config when you next lint.

## More Examples

See [test/](test/) for usage examples.

## Motivation

Shared ESLint configuration for Seneca.js projects.

## Support

If you're using this module and need help, you can:

- Post a [github issue][]
- Tweet to [@senecajs][]

## API

Extends standard ESLint rules with Seneca-specific conventions.

## Contributing

The [Senecajs org][] encourages open participation. If you feel you can help in any way, be it with documentation, examples, extra testing, or new features please get in touch.

### Running tests

```sh
npm run test
```

## Background

Used across all official Seneca plugins to maintain consistent code style.

[![Npm][BadgeNpm]][Npm]
[![Gitter][BadgeGitter]][Gitter]
[BadgeNpm]: https://img.shields.io/npm/v/eslint-config-seneca.svg
[BadgeGitter]: https://badges.gitter.im/senecajs/seneca.svg
[CoC]: http://senecajs.org/conduct
[Gitter]: https://gitter.im/senecajs/seneca
[Issue]: https://github.com/senecajs/eslint-config-seneca
[Lic]: ./LICENSE
[Logo]: http://senecajs.org/files/assets/seneca-logo.jpg
[Npm]: https://www.npmjs.com/package/eslint-config-seneca
[Org]: https://github.com/senecajs/issues
[Sponsor]: http://nearform.com
[Tweet]: https://twitter.com/senecajs
