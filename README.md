# python-template

これはテンプレート用のレポジトリです。

## setup

以下のようにタイプしてPythonをプロジェクトに合わせたものに変更し、必要なパッケージをインストールしてください。

```bash
pyenv local
poetry install
```

## configure

パッケージを追加する際は以下のようなコマンドを打ってください。

`{{pacckage_name}}`の部分を追加したいパッケージ名に変更してください。

```bash
poetry add {{package_name}}
```

## run

ライブラリを実行する際は以下のコードを打って下さい。

```bash
poetry run python main.py
```
