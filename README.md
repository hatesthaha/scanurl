# URL Scanner

扫描一个数组url链接

## Install

Composer

``` bash
$ composer require wuwenhan/scanurl
```

## Usage

``` php
$urls = [
    'http://www.apple.com',
    'http://php.net'
];
$scanner = new \wuwenhan\scanurl\Scanurl($urls);
print_r($scanner->getInvalidUrls());
```

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.