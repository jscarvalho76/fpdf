# FPDF for YII2

This repository is only made for cloning official FPDF releases which are available at: http://www.fpdf.org THERE WILL BE NO DEVELOPMENT IN THIS REPOSITORY!

FPDF is a PHP class which allows to generate PDF files with pure PHP. F from FPDF stands for Free: you may use it for any kind of usage and modify it to suit your needs.

## Installation with Composer
If you're using Composer to manage dependencies, you can use

    $ composer require "jeffersoncarvalho/fpdf:1.9.0"

or you can include the following in your composer.json file:

    {
        "require": {
            "jeffersoncarvalho/fpdf": "1.9.0"
        }
    }

or you can include the following in your composer.json file:

    {
        "require": {
             "jeffersoncarvalho/fpdf": "1.9.0"
        }
    }

## Usage
Once the extension is installed, simply use it in your code by :

    $pdf = new FPDF();
    $pdf->AddPage();
    $pdf->SetFont('Arial','B',16);
    $pdf->Cell(40,10,'Hello World!');
    $pdf->Output('D');
    
## Documentation

Please read documentation of [FPDF](http://fpdf.de/dokumentation/)

## Licence

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.