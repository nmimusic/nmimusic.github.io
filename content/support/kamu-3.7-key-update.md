---
title: 'Kamuriki Linux: GPG鍵の更新'
date: 2024-09-10T16:03:24+09:00
draft: false
categories:
- Support
comments: false
showMeta: true
showActions: false
---

GPG鍵の更新が行なわれました。新しい鍵は「```BDB9 5A53 1AF1 0907 EEDA CA9C 413E A564 B814 D95B```」です。
以下の手順で更新をして下さい。

(環境によってコマンド欄の表示が乱れる場合があります)

```bash
curl -fsSL https://sourceforge.net/projects/kamurikilinux/files/kamuriki-archive.key|sudo gpg -o /etc/apt/trusted.gpg.d/kamuriki-archive.gpg --dearmor
sudo apt update
```

近日公開予定のバージョン3.7以降は、この鍵が追加されます。
