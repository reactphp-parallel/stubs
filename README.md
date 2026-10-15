# Stubs (for PHPstan)

[![Continuous Integration](https://github.com/reactphp-parallel/stubs/actions/workflows/ci.yaml/badge.svg)](https://github.com/reactphp-parallel/stubs/actions)
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

## License

The MIT License (MIT)

Copyright (c) 2026 Cees-Jan Kiewiet

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
