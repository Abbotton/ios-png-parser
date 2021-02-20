# ios-png-parser
A PHP-based tool for parsing IOS application icons in IPA files
# Installation
```
composer require abbotton/ios-png-parser
```
# Usage
```php
use IosPngParser\Parser;

$parser = new Parser();
$encryptedPngFile = "/data/wwwroot/example.com/encrypted.png";
$decryptedPngFile = '/data/wwwroot/example.com/decrypted.png';
$parser::fix($encryptedPngFile, $decryptedPngFile);
```
# Enjoy