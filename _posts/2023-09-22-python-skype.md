---
layout: post
title: Python Skype Kullanımı
description: Python Skype Kullanımı
summary: Python Skype Kullanımı
tags: python,python skype
minute: 1
---
```python
!pip install skpy
from skpy import Skype, SkypeChats
sk = Skype('username@hotmail.com', 'password') # connect to Skype

sk.user
sk.contacts
sk.chats
sk.chats.recent()

def msg(mesaj):
    ch = sk.chats["8:sendmessageid"]
    ch.sendMsg(mesaj)

```
