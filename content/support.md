---
title: 'サポートページ'
---

# 個別
- [CDエクストラのご案内](/cdextra)
- [DSDディスクプレイヤーの一覧](/dsd-disc-compatible-list)
- [ミュージックカードの使い方](/musiccard)
- [その他よくある質問（FAQ、通称ふぁきゅー）](/faq)

---
# ルリタニア ミュージック エンターテインメント製アダルトゲームの動作について
2025年1月8日

RMEから発売されるゲームは、エンジンに「吉里吉里SDL2」を用いています。RURITANIAでは、以下の環境で動作を確認しています。

- Ubuntu AMD64バイナリ 
    - Debian 12
    - Debian 13
    - Ubuntu 24.04
- Win32 AMD64バイナリ
    - Windows(R) 11 日本語版

32ビットバイナリや、MacOS、BSDなど他のOSでの動作はサポートされません。

---
# Kamuriki LGX 3.7 GPG鍵の更新
2024年9月10日

GPG鍵の更新が行なわれました。新しい鍵は「```BDB9 5A53 1AF1 0907 EEDA CA9C 413E A564 B814 D95B```」です。
以下の手順で更新をして下さい。

(環境によってコマンド欄の表示が乱れる場合があります)

```bash
curl -fsSL https://sourceforge.net/projects/kamurikilinux/files/kamuriki-archive.key|sudo gpg -o /etc/apt/trusted.gpg.d/kamuriki-archive.gpg --dearmor
sudo apt update
```

近日公開予定のバージョン3.7以降は、この鍵が追加されます。
