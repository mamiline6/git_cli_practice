# ターミナルでファイルとリポジトリを作る

## インストールしたもの
- tig
　git でティグティグしてくれる
- hub
　github にハブハブしやすくしてくれる

## コマンド

リポジトリの作成
```sh
$ git init
```

空ファイル生成
本当は指定したディレクトリ／ファイルのタイムスタンプを変更
```sh
$ touch READEME.md
```

vim でREADEME.mdを書く
```sh
$ vi READEME.md
```

vim のキー
- i INSERT 入力モード
- esc Normalモードに戻る
- :wq vi 書いたファイルを上書き保存して閉じる
- :q 変更を破棄して閉じる

git で状態を確認
```sh
$ tig status
```
- u ステージにあげる？
- q もとの画面に戻る？
- C コミットログ

github にリポジトリ作成
```sh
$ hub create
```

リポジトリにプッシュ
```sh
$ git push origin master
````

github の確認
```sh
$ hub browse
```

















