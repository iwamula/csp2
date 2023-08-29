# CSP2

Pythonの学習用

## 環境構築

### 使用する Python のバージョン

python >= 3.11

## 使用するツール

- [venv](https://docs.python.org/ja/3/library/venv.html)
    - pipによるパッケージ管理をプロジェクトごとに分けるツール(Python公式モジュール)
- [Flake8](https://flake8.pycqa.org/en/latest/)
    - Pythonのソースが規約に沿っているか静的に解析するLinter
- [Black](https://github.com/psf/black)
    - Pythonのソースを見やすく整形するコードフォーマッター
- [isort](https://pycqa.github.io/isort/)
    - import文の順序を整形するコードフォーマッター
- [autoflake](https://github.com/PyCQA/autoflake)
    - 未使用のインポート文を削除するコードフォーマッター

## 開始準備

```
python -m venv .venv
pip install -r requirements.txt
```
