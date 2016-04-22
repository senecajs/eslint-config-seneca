![Logo][]
# eslint-config-seneca

[![Npm][BadgeNpm]][Npm]
[![Gitter][BadgeGitter]][Gitter]

- __Sponsor__: [nearForm][Sponsor]

A config for ESLint that adheres to Seneca's linting guidelines. All applicable repos
within the Senecajs org must be linted using this config.

If you're using this config, and need help, you can:

- Post a [github issue][Issue],
- Tweet to [@senecajs][Tweet],
- Ask on [gitter][Gitter].

## Install
To install, simply use npm,

```bash
npm install eslint-config-seneca eslint-plugin-standard eslint-plugin-hapi
```

__Note:__ If you are using ESLint v1 use v1.x.x. If you are using ESLint v2 use 2.x.x.

## Usage
Create an `.eslintrc` file with the following contents.

```json
{
  "extends": "seneca"
}
```

Once created ESLint will auto load the config when you next lint.

## Contributing
The [Senecajs Organization][Org] encourages __open__ and __safe__ participation.

- __[Code of Conduct][CoC]__

If you feel you can help in any way, be it with documentation, examples, extra testing, or new
features please get in touch.

## License
Copyright (c) 2015-2016, Dean McDonnell and other contributors. Licensed under __[MIT][Lic]__.


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
