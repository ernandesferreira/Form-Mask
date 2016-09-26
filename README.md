# Form-Mask
Plugin para Formulário Máscara é um plugin que faz o tempo do desenvolvedor para criar máscara para formas em geral, ambas as formas de plugins e de front-end.

Form Mask requires PHP >= 5.3.3.

- [Installation](#installation)
- [Basic Usage](#basic-usage)
- [Formatters](#formatters)
	- [Base](#fakerproviderbase)
	- [Lorem Ipsum Text](#fakerproviderlorem)
	- [Person](#fakerprovideren_usperson)
	- [Address](#fakerprovideren_usaddress)
	- [Phone Number](#fakerprovideren_usphonenumber)
	- [Company](#fakerprovideren_uscompany)
	- [Real Text](#fakerprovideren_ustext)
	- [Date and Time](#fakerproviderdatetime)
	- [Internet](#fakerproviderinternet)
	- [User Agent](#fakerprovideruseragent)
	- [Payment](#fakerproviderpayment)
	- [Color](#fakerprovidercolor)
	- [File](#fakerproviderfile)
	- [Image](#fakerproviderimage)
	- [Uuid](#fakerprovideruuid)
	- [Barcode](#fakerproviderbarcode)
	- [Miscellaneous](#fakerprovidermiscellaneous)
	- [Biased](#fakerproviderbiased)
	
## Installation

```sh
composer require fzaninotto/faker
```

## Basic Usage

Use `Faker\Factory::create()` to create and initialize a faker generator, which can generate data by accessing properties named after the type of data you want.
