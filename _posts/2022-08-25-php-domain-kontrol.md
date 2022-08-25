---
layout: post
title: Php domain karakter doğrulama
description: Php ile girilen domain adının doğru yazılıp yazılmadığını kontrol eder.
summary: Php ile girilen domain adının doğru yazılıp yazılmadığını kontrol eder.
tags: PHP
minute: 2
---
#### Php domain karakter doğrulama

Php ile girilen domain adının doğru yazılıp yazılmadığını kontrol eder.

```php
$url = "http://domain-name.com/";
if (preg_match('/^(http|https|ftp):\/\/([A-Z0-9][A-Z0-9_-]*(?:\.[A-Z0-9][A-Z0-9_-]*)+):?(\d+)?\/?/i', $url)) {
    echo "Your url is ok.";
} else {
    echo "Wrong url.";
}
```
