---
layout: post
title: Python FTP Download Progress Bar
description: Python FTP Download Progress Bar
summary: Python FTP Download Progress Bar
tags: python
minute: 1
---


```python
import requests
import shutil
from tqdm.auto import tqdm
import os
import ftplib
from time import sleep


host = 'ftp.site.com'
port = 21
ftp = ftplib.FTP()
ftp.connect(host,port)
ftp.login('user','pass')

for name, facts in ftp.mlsd():
    print (name)
    if(facts["type"] == 'file'):
            print("Download a file ", name)
            ftp.sendcmd("TYPE i")
            boyut = ftp.size(name)
            length = boyut
            generator = (3 * n for n in range(length))  # just doing something random
            for n in tqdm(generator, total=length):
                pass
```
