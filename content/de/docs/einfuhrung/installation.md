---
title: "Installation"
description: ""
lead: ""
draft: false
images: []
menu:
  docs:
    parent: "einfuhrung"
weight: 200
toc: true
---

Führen Sie in der Befehlszeile Ihres Servers den folgenden Befehl aus, um die für NixMember erforderlichen Programme zu installieren:

```bash
sudo apt install git bash
```

Danach müssen Sie das Programm auf Ihren Server herunterladen:

```bash
git clone https://github.com/nixmember/nixmember && cd nixmember
```

Und starten Sie das Programm:

```bash
./base.sh
```