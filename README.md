# Laravel GIT Commit Checker


## Requirement

- Laravel 9.32 or later
- If you're using Laravel 8.0 or earlier, please use version 1.x

## Installation

You can install the package via composer:

```shell
composer require ducal/git-commit-checker
```

Publish the configuration:

```bash
php artisan vendor:publish --tag=git-commit-checker-config
```

### Install GIT hooks

Run this command to install:

```shell
php artisan git-commit-checker:install
```

Run test manually (made sure you've added all changed files to git stage):

```shell
php artisan git-commit-checker:pre-commit-hook
```

### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

### Security

If you discover any security related issues, please email contact@ducalstudio.com instead of using the issue tracker.

## Credits

- [Ducal Studio](https://github.com/ducalstudio)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
