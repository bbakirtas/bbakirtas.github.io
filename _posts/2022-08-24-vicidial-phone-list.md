---
layout: post
title: Vicidial List Registered Phones
description: Vicidial List Registered Phones
summary: Vicidial List Registered Phones
tags: vicidial
minute: 2
---
#### Vicidial List Registered Phones

- Asterisk Server Registered Phones List "sip show peers"
- Barge (Logged users working with api)
- Monitor (Logged users working with api)
- Call Registered Phones
- Vicidial VERSION: 2.14-859a
BUILD: 220623-0824 
- Phones number of characters 4 if your phones have more edit code.
#### Edit
```html
"$data = system('echo "rootpasswd" | sudo -u root -S perl /usr/share/empty/sipshow.pl');"
```

```html
$extension_g = substr($json[$b],0,4); // Dial Plan Number 1001 if your Dial Plan Number like 10001 change 4 to 5
```
#### Add
```html
sipshow.pl to /usr/share/empty
```
#### Screen
![](https://raw.githubusercontent.com/bbakirtas/vici-phone-list/main/screen.JPG)


[Github Dowload](https://github.com/bbakirtas/vici-phone-list)