**ABANDONED! We decided to abandone the meta-data package because of inconsistencies in the version systems used by the PDF generation libraries. As it is up to the developers to define which PDF generation library is used in their code it should be configured as a direct dependency in their own composer.json file too.**

**Please remove this package from your composer.json and replace it by direct dependencies to [`setasign/fpdi`](https://packagist.org/packages/setasign/fpdi) and [`setasign/tfpdf`](https://packagist.org/packages/setasign/tfpdf).**

# FPDI-tFPDF
A kind of metadata package for Composer with fixed dependencies for the latest versions of FPDI and tFPDF

## Installation with [Composer](https://packagist.org/packages/setasign/fpdi-tfpdf)

```bash
$ composer require setasign/fpdi-tfpdf:2.3
```

or you can include the following in your composer.json file:

```json
{
    "require": {
        "setasign/fpdi-tfpdf": "^2.3"
    }
}
```
