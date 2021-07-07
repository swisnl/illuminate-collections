# illuminate-collections

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Total Downloads][ico-downloads]][link-downloads]
[![Made by SWIS][ico-swis]][link-swis]

Import [Laravel's Collections](https://laravel.com/docs/collections) into non-Laravel packages easily, without needing to require the entire `illuminate\support` package, while also supporting older PHP/Laravel versions. ([Why not pull `illuminate\support` in framework-agnostic packages](https://mattallan.org/posts/dont-use-illuminate-support/))

It just installs [illuminate/support](https://packagist.org/packages/illuminate/support) on PHP < 7.3 or Laravel < 8 and [illuminate/collections](https://packagist.org/packages/illuminate/collections) on PHP >= 7.3 or Laravel >= 8 and uses the same major versioning.

**This package will get major version tags up to and including the next Laravel LTS, which will probably be Laravel 9 in January 2022!**

## Install

Via Composer

``` bash
$ composer require swisnl/illuminate-collections
```

## Usage

Simply use `Illuminate\Support\Collection` as you normally would!

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email security@swis.nl instead of using the issue tracker.

## Credits

- [Jasper Zonneveld][link-author]
- [All Contributors][link-contributors]
- [All Laravel Contributors][link-laravel-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

## SWIS :heart: Open Source

[SWIS][link-swis] is a web agency from Leiden, the Netherlands. We love working with open source software. 

[ico-version]: https://img.shields.io/packagist/v/swisnl/illuminate-collections.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/swisnl/illuminate-collections.svg?style=flat-square
[ico-swis]: https://img.shields.io/badge/%F0%9F%9A%80-made%20by%20SWIS-%23D9021B.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/swisnl/illuminate-collections
[link-downloads]: https://packagist.org/packages/swisnl/illuminate-collections
[link-author]: https://github.com/JaZo
[link-contributors]: ../../contributors
[link-laravel-contributors]: https://github.com/illuminate/collections/graphs/contributors
[link-swis]: https://www.swis.nl
