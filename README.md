# Blogicum

## Технологии:
* Python 3.12.3
* Django 6.0.5

## Описание проекта

Небольшая социальная сеть для публикации личных дневников. Данные для социальной сети располагаются списком в файле views.py.

## Как запустить проект:

* Клонировать репозиторий и перейти в него в командной строке:

        git clone https://github.com/Artemiadze/Blogicum.git
        cd Blogicum

* Cоздать и активировать виртуальное окружение:

        python -m venv venv
        source venv/Scripts/activate

* Установить зависимости из файла requirements.txt:

        python -m pip install --upgrade pip
        pip install -r requirements.txt

* Запустить проект:

        python manage.py runserver

* Перейти на локальный сервер:

        http://127.0.0.1:8000/