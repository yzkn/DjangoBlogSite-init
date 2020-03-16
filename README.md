# [DjangoBlogSite](https://github.com/kjmczk/DjangoBlogSite)

---

## Clone

```ps
git clone https://github.com/kjmczk/DjangoBlogSite
```

## Pipfile

以下を削除

```py
[requires]

python_version = "3.6"
```

## pipenv

```ps
$ py -m pip install pipenv
$ py -m pipenv install
$ pipenv shell
```

## マイグレーション(SQLite)

```ps
$ py manage.py migrate
$ py manage.py createsuperuser
```

```
ユーザー名 (leave blank to use 'y'):
メールアドレス: y@example.net
Password: ********
Password (again): ********
このパスワードは一般的すぎます。
Bypass password validation and create user anyway? [y/N]: y
Superuser created successfully.
```

## サーバー起動

```ps
$ py manage.py runserver
```

> Django version 3.0.4, using settings 'dbsite.settings'
>
> Starting development server at http://127.0.0.1:8000/

管理画面にアクセスする場合は[/admin](http://127.0.0.1:8000/)にアクセス
