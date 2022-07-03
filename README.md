Laravel-Identicon Package
=========================
[![Laravel Package][ico-laravel]][link-repo]
[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Total Downloads][ico-downloads]][link-downloads]

> This is the wraper package of [Identicon][link-identicon] Package for laravel projects.

### Installation

```bash
$ composer require ncoderslab/laravel-identicon
```

## Usage

This is the wrapper package of [Identicon][link-identicon] for laravel projects. All features available in [Identicon][link-identicon] are avialable in this package as well

### Example Methods

Generate and Display an identicon image:

```php
Identicon::displayImage('nCoders Lab');
```

Generate and get the image data

```php
$imageData = Identicon::getImageData('nCoders Lab');
```

Generate and get the base 64 image uri ready for integrate into an HTML img tag. The below example is using blade templating

```
<img src="{{ Identicon::getImageDataUri('nCoders Lab') }}" alt="nCoders Lab Identicon" />
```

...

And all the other remaining methods from the main library.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-laravel]: https://img.shields.io/badge/Laravel-6~8-FF2D20.svg?style=flat-square&logo=laravel&labelColor=black&logoColor=white
[ico-version]: https://img.shields.io/packagist/v/ncoderslab/laravel-identicon.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/ncoderslab/laravel-identicon.svg?style=flat-square

[link-repo]: https://github.com/ncoderslab/laravel-identicon
[link-packagist]: https://packagist.org/packages/ncoderslab/laravel-identicon
[link-downloads]: https://packagist.org/packages/ncoderslab/laravel-identicon
[link-author]: https://github.com/ncoderslab
[link-identicon]: https://github.com/yzalis/Identicon