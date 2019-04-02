# FPDF for YII2

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Total Downloads][ico-downloads]][link-downloads]
![ico-jefferson]
![GitHub All Releases]

This repository is only made for cloning official FPDF releases which are available at: http://www.fpdf.org THERE WILL BE NO DEVELOPMENT IN THIS REPOSITORY!

FPDF is a PHP class which allows to generate PDF files with pure PHP. F from FPDF stands for Free: you may use it for any kind of usage and modify it to suit your needs.

## Installation with Composer
If you're using Composer to manage dependencies, you can use
```php
$ composer require "jeffersoncarvalho/fpdf"
```
or you can include the following in your composer.json file:
```php
{
    "require": {
        "jeffersoncarvalho/fpdf": "1.9.0"
    }
}
```

or you can include the following in your composer.json file:
```php
{
    "require": {
        "jeffersoncarvalho/fpdf": "1.9.0"
    }
}
```

## Usage
Once the extension is installed, simply use it in your code by :
```php
$pdf = new FPDF();
$pdf->AddPage();
$pdf->SetFont('Arial','B',16);
$pdf->Cell(40,10,'Hello World!');
$pdf->Output('D');
```    
## Documentation

Please read documentation of [FPDF](http://fpdf.de/dokumentation/)

## Licence

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/jeffersoncarvalho/fpdf.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/jeffersoncarvalho/fpdf.svg?label=downloads%20Packagist&style=flat-square

[ico-jefferson]:https://img.shields.io/badge/Powered_by-Jefferson_Carvalho-orange.svg?style=flat-square

[GitHub All Releases]:https://img.shields.io/github/downloads/jscarvalho76/fpdf/total.svg?label=downloads%20Git&style=flat-square

[link-packagist]: https://packagist.org/packages/jeffersoncarvalho/fpdf
[link-downloads]: https://packagist.org/packages/jeffersoncarvalho/fpdf
[link-author]: https://github.com/jscarvalho76
[link-contributors]: ../../contributors


