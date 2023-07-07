# infra_sprint1
Проект Kittygram Test Social Network

### Описание проекта:

Проект представляет собой тестовую модель социальной сети Kittigram
и состоит из двух основных частей: frontend сайта, написанный на javascript,
и бэкэнд сайта, написанный на python.

Функционал социальной сети позволяет регистрировать новых пользователей,
загружать и удалять картинки котов, указывать год рождения кота, цвет кота
и список его достижений (если они имеются).

### Автор проекта:

Антон Лопатин, Python-разработчик

### Стэк, используемый в проекте:

Javascript ES6, CSS 3.0, Python 3.11, Django 3.2.3, Django Rest Framework 3.12.4, Simple JWT 4.8.0, Djoser 2.1.0, Pillow 9.0.0, 
Gunicorn 20.1.0, Idna 3.4, Requests 2.31.0, SQL Parse 0.4.4, Typing Extensions 4.6.3, Webcolors 1.11.1,
Cryptography 41.0.1, Oauthlib 3.2.2 

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:FireFynjy/infra_sprint1.git
```

```
cd infra_sprint1
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Установить зависимости для frontend-приложения и запустить его:

```
npm i

npm run start
```

Запустить backend проекта:

```
python3 manage.py runserver 0:8000
```
