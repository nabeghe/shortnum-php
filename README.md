# Shortnum for PHP.

> Shortening numbers and using abbreviated letters in PHP.

With Shortnum, you can easily display numbers like 1000 as 1K.
Shortnum supports the following units:

`'K', 'M', 'B', 'T', 'Qa', 'Qi', 'Sx', 'Sp', 'Oc', 'No', 'Dc', 'Ud', 'Dd', 'Td', 'Qa', 'Qi', 'Sx', 'Sp',
'Oc', 'No'`

<hr>

## 🫡 Usage

### 🚀 Installation

You can install the package via composer:

```bash
composer require nabeghe/colory
```

<hr>

#### Example:

```php
use Nabeghe\Shortnum\Shortnum;

echo "1000 => ".Shortnum::short(1000)."\n"; // 1K
echo "1010 => ".Shortnum::short(1010)."\n"; // 1.01K
echo "1049 => ".Shortnum::short(1049)."\n"; // 1.05K
echo "1050 => ".Shortnum::short(1050)."\n"; // 1.05K
echo "1099 => ".Shortnum::short(1099)."\n"; // 1.1K
echo "1100 => ".Shortnum::short(1100)."\n"; // 1.1K
echo "10000 => ".Shortnum::short(10000)."\n"; // 10K
echo "10500 => ".Shortnum::short(10500)."\n"; // 10.5K
echo "15000 => ".Shortnum::short(15000)."\n"; // 15K
echo "100000 => ".Shortnum::short(100000)."\n"; // 100K
echo "1000000 => ".Shortnum::short(1000000)."\n"; // 1M
echo "1000000000 => ".Shortnum::short(1000000000)."\n"; // 1B
echo "1000000000 => ".Shortnum::short(1000000000)."\n"; // 1B
echo "1000000000000 => ".Shortnum::short(1000000000000)."\n"; // 1T
echo "1000000000000000 => ".Shortnum::short(1000000000000000)."\n"; // 1Qa
echo "1000000000000000000 => ".Shortnum::short(1000000000000000000)."\n"; // 1Qi
echo "1000000000000000000000 => ".Shortnum::short(1000000000000000000000)."\n"; // 1Sx
echo "1000000000000000000000000 => ".Shortnum::short(1000000000000000000000000)."\n"; // 1Sp
echo "1000000000000000000000000000 => ".Shortnum::short(1000000000000000000000000000)."\n"; // 1Oc
echo "1000000000000000000000000000000 => ".Shortnum::short(1000000000000000000000000000000)."\n"; // 1No
```

<hr>

## 📖 License

Copyright (c) Hadi Akbarzadeh

Licensed under the MIT license, see [LICENSE.md](LICENSE.md) for details.