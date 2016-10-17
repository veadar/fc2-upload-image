#fc2 upload image

##これは何？

fc2に画像をアップロードするAppleScript製ドロップレットです。

アップロードしたい画像ファイルをこのアプリのアイコンへドラッグ＆ドロップ。

##対応 OS

OS X 10.10以降

macOS 10.12で作成。

## 保存されるデータの場所

以下の場所にパスワードなどのデータが平文で保存されます。

- ``~/Library/Cookies/fc2uploader_cookie_[アプリ名].txt``
- ``~/Library/Preferences/org.[アプリ名].fc2photo``

アプリ名を変えれば違う設定で始められます。

アンストール時には上記2ファイルを捨てると設定も捨てられます。

##ダウンロード

Downloadをクリック → [Download](https://github.com/veadar/fc2-upload-image/releases)

古いバージョンは[ブログ](http://veadardiary.blog29.fc2.com/blog-entry-3415.html)よりダウンロードしてください

##参考にさせていただいたコード

- [Cocoaの機能を使ってdefaultsコマンドを実行するAppleScriptハンドラ](http://qiita.com/szk-3/items/7b23c77196ba8d26ed77)
- [ドラッグ＆ドロップでFC2ブログに複数の画像をまとめてアップロードするAppleScript その4](http://chocolife.blog80.fc2.com/blog-entry-65.html)