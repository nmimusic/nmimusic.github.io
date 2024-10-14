---
title: 'Kamuriki Linux 3.7.1'
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
どもども、麻浪迅です。今回は緊急更新。

# 利用規約
Kamuriki Linuxのご利用には、EULAへの同意が必要です。

中村音楽工業 オープンソースソフトウェア エンドユーザーライセンス契約 https://nmimusic.github.io/eula.pdf

# ダウンロード
- [Kamuriki Linux 3.7.1 Standard Edition](https://sourceforge.net/projects/kamurikilinux/files/iso/cheetah/3.7.1/kamuriki-standard-3.7.1-amd64.iso)
- [ソースコード](https://sourceforge.net/projects/kamurikilinux/files/iso/cheetah/3.7.1/kamuriki-3.7.1.tar.gz)

# 主な変更点
カーネル：Realtime 6.1.112-1

- Wineからインターネットが繋がるように設定を変更

# 更新の手順
まず環境を最新の状態にする。
```bash
sudo apt update && sudo apt upgrade
```

次にこのコマンドを実行して、全て「はい」を選ぶ。
```bash
sudo dpkg-reconfigure wine-stable{,-{i386,amd64}}
```

# Kamurikiについて
Kamuriki Linuxは(一社同)中村音楽工業が改造したdpkg系Linux/GNU/Xディストリビューションです。利用にはNMI OSS EULAへの同意が必要です。Kamuriki固有の部分は三条項BSDライセンスで配布されます。ユーザーの皆様はこれに加え、各種ソフトウェアのライセンスにも従う必要があります。

# お問い合わせ
knjbfm at gmail.comまでメールを下さい。日本語と英語で対応できます。 
