---
title: 'Kamuriki Linux 3.9'
date: 2025-03-16T19:13:48+09:00
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
どもども、麻浪迅です。アップストリームでの更新があったので、こっちも更新。

それと私事ではありますが、高専卒業できるっぽいよ！！ヤッピー

# 利用規約
Kamuriki Linuxのご利用には、EULAへの同意が必要です。

[中村音楽工業 オープンソースソフトウェア エンドユーザーライセンス契約](https://nmimusic.github.io/eula.pdf)

なお、Kamuriki Linuxの固有部分は三条項BSDライセンスの下で利用可能です。
```
BSD 3-clause License

Copyright (c) 2021-2025, Nakamura Musical Industries.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS “AS IS” AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED.
IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

# Kamurikiを入手
<!--- [Kamuriki Linux 3.10 Professional Edition (DVD)](https://nmimusic.booth.pm/items/6478705)-->
- Kamuriki Linux 3.10 Professional Edition (DVD) **2025年3月20日登場予定**
- [Kamuriki Linux 3.9 Standard Edition (ISO)](https://sourceforge.net/projects/kamurikilinux/files/iso/cheetah/3.10/kamuriki-3.10-amd64.iso)
- [ソースコード (tar.gz)](https://sourceforge.net/projects/kamurikilinux/files/iso/cheetah/3.10/kamuriki-standard-3.10-src.tar.gz)

**USBにはDDモードで焼いて下さい。**

# 主な変更点
- カーネルを6.1.129に更新

## 主なパッケージバージョン
- Linux RT 6.1.129
- GCC 12.2.0
- binutils 2.40
- glibc 2.36
- X.org Server 21.1.7
- LXQt 1.2.0
- Firefox 128.8.0 ESR
- Thunderbird 128.8.0 ESR
- LibreOffice 7.4.7
- VLC 3.0.21
- Wine 10.0
- Python 3.11.2

アップストリームでの更新情報は[こちら](https://www.debian.org/News/2025/20250111)

# 更新の手順
環境を最新の状態にする。
```bash
sudo apt update && sudo apt upgrade
```

# Kamurikiについて
Kamuriki Linuxは(一社同)中村音楽工業が改造したdpkg系Linux/GNU/Xディストリビューションです。利用にはNMI OSS EULAへの同意が必要です。Kamuriki固有の部分は三条項BSDライセンスで配布されます。ユーザーの皆様はこれに加え、各種ソフトウェアのライセンスにも従う必要があります。

# お問い合わせ
knjbfm at gmail.comまでメールを下さい。日本語と英語で対応できます。 
