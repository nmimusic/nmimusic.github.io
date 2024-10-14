---
title: 'Kamuriki Linux 3.7'
date: 2024-09-14T10:11:59+09:00
banner: /img/discography/others/kamu-logo.png
draft: false
categories:
- Linux
tags:
- KamurikiLinux
- リリースノート
comments: false
showMeta: true
showActions: false
---

# 前書き
どもども、麻浪迅です。まずみんなに謝らなきゃいけないコトがある。リリースが半月も遅れてしまい、申し訳ありません。

ビルドシステムの不具合やAlisの開発中止のゴタゴタでNMIのLinux部門が大変な事態になっているのです。

なんとか公開できたのが救いだね。

# 利用規約
Kamuriki Linuxのご利用には、EULAへの同意が必要です。

中村音楽工業 オープンソースソフトウェア エンドユーザーライセンス契約 https://nmimusic.github.io/eula.pdf

# ダウンロード
- [Kamuriki Linux 3.7 Standard Edition](https://sourceforge.net/projects/kamurikilinux/files/iso/cheetah/3.7/kamuriki-standard-3.7-amd64.iso)
- [ソースコード](https://sourceforge.net/projects/kamurikilinux/files/iso/cheetah/3.7/kamuriki-3.7.tar.gz)

# 主な変更点
カーネル：Realtime 6.1.106-3

- ビルドシステムを[DebISO](https://github.com/nmimusic/debiso)に変更
- GPG鍵の更新

[上流での変更点はこちら](https://www.debian.org/News/2024/20240831)

# 更新の手順
まず[この手順](support/kamu-3.7-key-update/)に従ってGPG鍵を更新する。

次に環境を最新の状態にする。
```bash
sudo apt update && sudo apt upgrade
```

# Kamurikiについて
Kamuriki Linuxは(一社同)中村音楽工業が改造したdpkg系Linux/GNU/Xディストリビューションです。
Kamuriki固有の部分は三条項BSDライセンスで配布されます。ユーザーの皆様はこれに加え、各種ソフトウェアのライセンスにも従う必要があります。

# お問い合わせ
knjbfm at gmail.comまでメールを下さい。日本語と英語で対応できます。 
