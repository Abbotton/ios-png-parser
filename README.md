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
$ipaFilePath = '/path/to/dot/ipa/file';
$pngImgName = '/path/to/save/parsed/png/image';
$parser::fix($ipaFilePath, $pngImgName);
```
# Enjoy