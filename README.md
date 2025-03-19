# duckcode

duckdb on vscode

![duckcode](img/image.png)

## これは何？

- duckdb を vscode 経由で書けるようにした vscode の拡張機能です。
- 特に開発中に集めた CSV や jsonl などをサクッと分析しつつ、SQL ファイルをコード管理して扱うことを目的にしています。

## インストールの仕方

- [こちら](https://github.com/marufeuille/duckcode/releases)から最新の vsix をダウンロードしてください
- [こちら](https://learn.microsoft.com/ja-jp/visualstudio/ide/finding-and-using-visual-studio-extensions?view=vs-2022#install-without-using-extension-manager)の記載に従ってインストールしてください

## 使い方

いずれかの方法で起動できます。

1. Cmd+Shift+P のメニューから Open DuckDB SQLEditor を選択
2. `.sql` ファイルを右クリックし、 `Run SQL in DuckDB` を選択

## やりたいこと(やってないこと)

- 可視化できるデータ種類を増やす (いまのところ、あくまで簡易なものに閉じておきたいのでリッチにするつもりはない)

- marketplace 公開
