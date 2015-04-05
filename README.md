# PHP Lib Bootstrap

[![Latest Stable Version](https://poser.pugx.org/raphhh/php-lib-bootstrap/v/stable.svg)](https://packagist.org/packages/raphhh/php-lib-bootstrap)
[![Build Status](https://travis-ci.org/Raphhh/php-lib-bootstrap.png)](https://travis-ci.org/Raphhh/php-lib-bootstrap)
[![Scrutinizer Quality Score](https://scrutinizer-ci.com/g/Raphhh/php-lib-bootstrap/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/Raphhh/php-lib-bootstrap/)
[![Code Coverage](https://scrutinizer-ci.com/g/Raphhh/php-lib-bootstrap/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/Raphhh/php-lib-bootstrap/)
[![Total Downloads](https://poser.pugx.org/raphhh/php-lib-bootstrap/downloads.svg)](https://packagist.org/packages/raphhh/php-lib-bootstrap)
[![Reference Status](https://www.versioneye.com/php/raphhh:php-lib-bootstrap/reference_badge.svg?style=flat)](https://www.versioneye.com/php/raphhh:php-lib-bootstrap/references)
[![License](https://poser.pugx.org/raphhh/php-lib-bootstrap/license.svg)](https://packagist.org/packages/raphhh/php-lib-bootstrap)

A bootstrap for a lib in PHP. Don't set, just code!  


## About

This bootstrap will install all the basic files and settings to start a PHP library. 

This assumes you'll use [Git](http://git-scm.com/) for vcs, 
[Composer](https://getcomposer.org/) for dependencies, 
[PHPUnit](https://phpunit.de/) for testing, 
[Travis](https://travis-ci.org) and [Scrutinizer](https://scrutinizer-ci.com/) for integration servers.

## Files architecture

    ├── src
    |   └── Dummy.php
    ├── tests
    |   └── DummyTest.php
    ├── vendor
    ├── .editorconfig
    ├── .gitattributes
    ├── .gitignore
    ├── .scrutinizer.yml
    ├── .travis.yml
    ├── composer.json
    ├── LICENSE
    ├── phpunit.xml.dist
    └── README.md

- "public" is the web entry point.
- "src" contains all your PHP code.
- "tests" contains all your PHP tests. See [PHPUnit](https://phpunit.de/) for more information.
- "vendor" contains all your PHP dependencies. See [Composer](https://getcomposer.org/) for more information.

## Installation

### With Samurai (recommended)

Just execute [Samurai](https://github.com/Raphhh/samurai) with 'lib' boostrap.

```
$ samurai new lib
```

### With Composer

First, execute [Composer](https://getcomposer.org/) to create your project.

```
$ composer create-project raphhh/php-lib-bootstrap path/to/my/project
```

Go into your project.

```
$ cd path/to/my/project
```

Then, you need to replace composer.json with your specific info.

## Usage

### Launch unit tests

This bootstrap is configured to use [PHPUnit](https://phpunit.de). To run the tests, cd to your project and enter the following command in your console:
```
$ vendor/bin/phpunit
```
