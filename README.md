# Django-tutorial

このプロジェクトはDjangoを使用して構築されたWebアプリケーションです。  
以下の手順でセットアップし、ローカル環境で開発サーバーを起動できます。
https://docs.djangoproject.com/ja/5.1/intro/tutorial01/

## **環境要件**
- Python 3.10.x
- Django
- 仮想環境（推奨: `venv`）

## **セットアップ手順**

```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```

install
```bash
pip install -r requirements.txt
```

webServer
```bash
python3 manage.py runserver
```

Shell
```bash
python manage.py shell_plus
```