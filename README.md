## 仮想環境作成
$ python3 -m venv .venv
### または
$ python -m venv .venv

## 仮想環境起動
[Linux]
$ source .venv/bin/activate

[Windows]
$ .venv/Scripts/activate

## 仮想環境無効化
$ deactivate

## 仮想環境のコピー
### ライブラリの出力
$ pip freeze > requirements.txt
### ライブラリをまとめてインストール
$ pip install -r requirements.txt
