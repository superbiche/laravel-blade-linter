# Laravel Blade Linter

[![Latest Version on Packagist](https://img.shields.io/packagist/v/bdelespierre/laravel-blade-linter.svg?style=flat-square)](https://packagist.org/packages/bdelespierre/laravel-blade-linter)
[![Build Status](https://img.shields.io/travis/bdelespierre/laravel-blade-linter/master.svg?style=flat-square)](https://travis-ci.org/bdelespierre/laravel-blade-linter)
[![Quality Score](https://img.shields.io/scrutinizer/g/bdelespierre/laravel-blade-linter.svg?style=flat-square)](https://scrutinizer-ci.com/g/bdelespierre/laravel-blade-linter)
[![Total Downloads](https://img.shields.io/packagist/dt/bdelespierre/laravel-blade-linter.svg?style=flat-square)](https://packagist.org/packages/bdelespierre/laravel-blade-linter)

Performs syntax-checks of your Blade templates. Just that.

## Installation

You can install the package via composer:

```bash
composer require bdelespierre/laravel-blade-linter
```

## Usage

```bash
php artisan blade:lint
```

Or if you want to lint specific templates or directories:

```bash
php artisan blade:lint resources/views/
```

### Testing

``` bash
composer test
```

### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

### Security

If you discover any security related issues, please email benjamin.delespierre@gmail.com instead of using the issue tracker.

## Credits

- [Benjamin Delespierre](https://github.com/bdelespierre)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

## Laravel Package Boilerplate

This package was generated using the [Laravel Package Boilerplate](https://laravelpackageboilerplate.com).
