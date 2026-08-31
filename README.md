# cat-charity-2


## О проекте
Веб-сервис благотворительного фонда поддержки котиков на FastAPI. Проект позволяет управлять благотворительными проектами и пожертвованиями через REST API. Также настроена работа с пользователями

## Стек технологий
* Python
* FastAPI/FastAPIUsers
* SQLAlchemy
* Alembic
* SQLite

## Как запустить
Клонировать репозиторий и перейти в него:

```bash
git clone https://github.com/Abubakr2703/cat-charity-2.git
cd cat-charity-2
```

Создать и активировать виртуальное окружение:

```bash
python3 -m venv venv
source venv/bin/activate
```

Установить зависимости:

```bash
pip install -r requirements.txt
```

Применить миграции:

```bash
alembic upgrade head
```

Запустить сервер:

```bash
uvicorn app.main:app --reload
```

После запуска API, документация будет доступна по адресу:

[Swagger](http://127.0.0.1:8000/docs)
[ReDoc](http://127.0.0.1:8000/redoc)