API YaTube
=====

Описание проекта
----------
API сервис для проекта социальной сети Yatube. Для аутентификации применен JWT-токен, реализован API CRUD для основных моделей проекта. Реализованы пермишены, фильтрация, сортировки и поиск по запросам клиентов, установлено ограничение количества запросов от клиентов. В проекте есть пагинация ответов от API.

Системные требования
----------
* Python 3.6+
* Works on Linux, Windows, macOS, BSD

Стек технологий
----------
* Python 3.6
* Django 2.2 
* Django Rest Framework
* Simple-JWT
* SQLite3

Установка проекта из репозитория
----------

1. Клонировать репозиторий и перейти в него в командной строке:
```
git clone 'https://github.com/NikitaChalykh/API_YaTube.git'

cd API_YaTube
```
2. Cоздать и активировать виртуальное окружение:
```
python3 -m venv env

source env/bin/activate
```
3. Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip

pip install -r requirements.txt
```
4. Выполнить миграции:
```
python3 manage.py migrate
```
5. Запустить проект:
```
python3 manage.py runserver
```
Документация к проекту
----------
Документация для API Yatube доступна по адресу: ```/redoc/```
