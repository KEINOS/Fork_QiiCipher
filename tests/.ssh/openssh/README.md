# 新書式（OpenSSH 形式）の公開鍵・秘密鍵

```shellsession
$ ssh -V
OpenSSH_8.4p1, OpenSSL 1.1.1k  25 Mar 2021

$ tree
.
├── README.md ............ このファイル
├── no_pass .............. パスフレーズなしの公開・秘密鍵ペア置き場
│   ├── README.md ........... 読んでねファイル
│   ├── id_ed25519 .......... ed25519 秘密鍵
│   ├── id_ed25519.pub ...... ed25519 公開鍵
│   ├── id_rsa .............. rsa 秘密鍵 (4096 bit)
│   └── id_rsa.pub .......... rsa 公開鍵
└── with_pass ............ パスフレーズありの公開・秘密鍵ペア置き場
    ├── README.md ........... 読んでねファイル
    ├── id_ed25519 .......... ed25519 秘密鍵
    ├── id_ed25519.pub ...... ed25519 公開鍵
    ├── id_rsa .............. rsa 秘密鍵 (4096 bit)
    └── id_rsa.pub .......... rsa 公開鍵
```

## 注意

**このディレクトリの公開鍵・秘密鍵はテスト用です**。動作テスト目的以外で使うと `pͪoͣnͬpͣoͥnͭpͣa͡inͥ` な事になります。