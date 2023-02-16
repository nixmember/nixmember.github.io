---
title: "Instalacija"
description: ""
lead: ""
draft: false
images: []
menu:
  docs:
    parent: "uvod"
weight: 200
toc: true
---

Iz komandne linije vašega servera pokrenite sljedeću komandu kako bi instalirali programe potrebne za NixMember:

```bash
sudo apt install git bash curl
```

Nakon toga, potrebno je skinuti program na Vaš server:

```bash
git clone https://github.com/nixmember/nixmember && cd nixmember
```

Te pokrenuti program:

```bash
./base.sh
```