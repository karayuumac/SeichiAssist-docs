# SeichiAssist-docs

## 環境構築

pythonをインストールしている前提で説明します。

1. mkdocsのインストール
    ```
    pip install mkdocs
    ```
2. materialテーマをインストール
    ```
    pip install mkdocs-material
    ```
3. fontawsome_markdownのインストール
    ```
    pip install fontawesome_markdown
    ```

## ページの編集方法

1. markdownファイルを作成または編集し、保存する

2. ローカルサーバを起動
    ```
    mkdocs serve
    ```

3. オートリロードが効いているので、保存するだけで変更が適用される

## Github Pagesにアップロード

以下のコマンドを実行するだけで可能。
```
mkdocs gh-deploy
```
