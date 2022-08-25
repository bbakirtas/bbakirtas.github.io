---
layout: post
title: PHP ile eposta kontrol
description: PHP ile eposta kontrol
summary: PHP ile eposta kontrol
tags: PHP
minute: 2
---
#### PHP ile eposta kontrol

PHP ile eposta kontrol kısa kod.

```php
if (filter_var('test+email@fexample.com', FILTER_VALIDATE_EMAIL)) {
    echo "Your email is ok.";
} else {
    echo "Wrong email address format.";
}
```
