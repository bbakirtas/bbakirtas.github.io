---
layout: post
title: PHP ile domain urlsini almak
description: PHP ile girilen domainin url adresini almak
summary: PHP ile girilen domainin url adresini almak
tags: PHP
minute: 2
---
#### PHP ile girilen domainin url adresini almak

PHP ile girilen domainin sonundaki tagları kaldırıp urlyi bulan kod.

```php
$url = "http://domain-name.com/index.html";
preg_match('@^(?:http://)?([^/]+)@i', $url, $matches);
$host = $matches[1];
echo $host; // domain-name.com
```
