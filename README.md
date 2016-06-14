slim-minify
===========

Slim middleware to minify HTML output generated by the slim PHP framework. It removes whitespaces, empty lines, tabs
beetween html-tags and comments to reduce traffic. This script is a summary of stackoverflow answers.

## Usage

Copy the file Minify.php to 'Slim/Middleware/'. Register minify via $app->add():

```php
$app = new \Slim\Slim(.....));
$app->add(new \Slim\Middleware\Minify() );
```

or use the composer:
```
    "require": {
        "christianklisch/slim-minify": "0.4.4"
    }
```

## Contributors

* Christian Klisch http://www.christian-klisch.de


## Copyright and license

Copyright 2014 released under [MIT](LICENSE) license.
