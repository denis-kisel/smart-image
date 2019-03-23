# SmartImage

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Total Downloads][ico-downloads]][link-downloads]
[![Build Status][ico-travis]][link-travis]


## Installation

Via Composer

``` bash
$ composer require denis-kisel/smart-image
```

## Usage
```php
<?php
//Will get storage/app/public/image.jpg
//And will put in the storage/app/public/image_cache/image-200x200.jpg
//Return link on cache image: site.com/storage/image_cache/image-200x200.jpg
SmartImage::cache('image.jpg', 200, 200); 
```


## Credits

- [Denis Kisel][link-author]

[ico-version]: https://img.shields.io/packagist/v/deniskisel/smartimage.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/deniskisel/smartimage.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/deniskisel/smartimage/master.svg?style=flat-square
[ico-styleci]: https://styleci.io/repos/12345678/shield

[link-packagist]: https://packagist.org/packages/denis-kisel/smart-image
[link-downloads]: https://packagist.org/packages/denis-kisel/smart-image
[link-travis]: https://travis-ci.org/denis-kisel/smart-image
[link-styleci]: https://styleci.io/repos/12345678
[link-author]: https://github.com/denis-kisel
