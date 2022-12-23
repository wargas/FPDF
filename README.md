# FPDF
**This repository is only clone official FPDF releases which are available at: http://www.fpdf.org**
**THERE WILL BE NO DEVELOPMENT IN THIS REPOSITORY!**

FPDF is a PHP class which allows to generate PDF files with pure PHP. F from FPDF stands for Free: you may use it for any kind of usage and modify it to suit your needs.

## Installation with [Composer](https://packagist.org/packages/setasign/fpdf)

If you're using Composer to manage dependencies, you can use

    $ composer require wargas/fpdf:^1.8

or you can include the following in your composer.json file:

```json
{
    "require": {
        "wargas/fpdf": "^1.8"
    }
}
```

# Get Started

```php
use Wargas\FPDF\FPDF;

$pdf = new FPDF();

$pdf->AddPage();
$pdf->SetFont('Arial', '', 10);
$pdf->Write(10, "Example 01");
$pdf->Image("data:image/png;base64,iVBORw0KGgoAAAA....");
$pdf->Output('I');
```
