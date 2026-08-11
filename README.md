# FB Suite

[![Latest Version on Packagist](https://img.shields.io/packagist/v/mortezamasumi/fb-suite.svg?style=flat-square)](https://packagist.org/packages/mortezamasumi/fb-suite)
[![License](https://img.shields.io/packagist/l/mortezamasumi/fb-suite.svg?style=flat-square)](LICENSE.md)

Meta-package that requires every `fb-*` Filament package in one go, so consuming projects can install one dependency instead of listing each package (and bumping each version) individually.

```bash
composer require mortezamasumi/fb-suite
```

Bundles:

- [fb-essentials](https://github.com/mortezamasumi/fb-essentials)
- [fb-auth](https://github.com/mortezamasumi/fb-auth)
- [fb-sms](https://github.com/mortezamasumi/fb-sms)
- [fb-user](https://github.com/mortezamasumi/fb-user)
- [fb-profile](https://github.com/mortezamasumi/fb-profile)
- [fb-message](https://github.com/mortezamasumi/fb-message)
- [fb-passwd](https://github.com/mortezamasumi/fb-passwd)
- [fb-report](https://github.com/mortezamasumi/fb-report)
- [fb-setting](https://github.com/mortezamasumi/fb-setting)
- [fb-activity](https://github.com/mortezamasumi/fb-activity)
- [fb-copydb](https://github.com/mortezamasumi/fb-copydb)

This package ships no code of its own — each `fb-*` package registers its own Laravel service provider via package auto-discovery. To pick a subset instead, require the individual packages directly.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
