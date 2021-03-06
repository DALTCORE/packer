# Laravel Packer

This package provides you with a simple tool to set up a new Laravel package. It provides a complete boilerplate code that could actually be done by a package. Use what you need, remove the remaining.

## Installation

Via Composer

    $ composer require daltcore/packer

Then add the service provider in `config/app.php`:

    'Laravolt\Packer\PackerServiceProvider',

## Usage

### New package
The command will handle practically everything for you. It will create a packages directory, creates the vendor and package directory in it, pulls in a skeleton package, sets up composer.json, creates a service provider, registers the package in config/app.php and the app's composer.json. So you can start right away with only this command:

``` bash
$ php artisan laravolt:packer:new vendor_name package_name
```

## Credits

This package was originally forked from [Jeroen-G/laravel-packager awesome package](https://github.com/Jeroen-G/laravel-packager).
