# Stubs (for PHPstan)\

[![Continuous Integration](https://github.com/reactphp-parallel/stubs/actions/workflows/ci.yml/badge.svg)](https://github.com/reactphp-parallel/stubs/actions)
[![Latest Stable Version](https://poser.pugx.org/react-parallel/stubs/v/stable)](https://packagist.org/packages/react-parallel/stubs)
[![License](https://poser.pugx.org/react-parallel/stubs/license)](https://packagist.org/packages/react-parallel/stubs)

* [PHPStan](https://phpstan.org/)
* [ext-parallel](https://github.com/krakjoe/parallel)

## Installation

To use this extension, require it in [Composer](https://getcomposer.org/):

```
composer require --dev react-parallel/stubs
```

If you also install [phpstan/extension-installer](https://github.com/phpstan/extension-installer) then you're all set!

<details>
  <summary>Manual installation</summary>

If you don't want to use `phpstan/extension-installer`, include extension.neon in your project's PHPStan config:

```
includes:
    - vendor/react-parallel/stubs/extension.neon
```

</details>
