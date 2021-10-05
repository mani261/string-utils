# String Utils

---

Simple string utils for dealing easier with them

# Installation

Install using composer:

```
composer require manicollege/string-utils
```

# Example
```php
<?php

require __DIR__.'/vendor/autoload.php';

use \ManiCollege\StringUtils\Str;

var_dump(Str::contains('abcd', ['ab', 'x']));
```