API YaTube 
=====

Описание проекта
----------
API сервис для [проекта социальной сети Yatube](https://github.com/NikitaChalykh/YaTube). 

Реализован REST API CRUD для основных моделей проекта, для аутентификации примненяется JWT-токен. 
В проекте реализованы пермишены, фильтрации, сортировки и поиск по запросам клиентов, реализована пагинация ответов от API, установлено ограничение количества запросов к API. 

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
```bash
git clone 'https://github.com/NikitaChalykh/API_YaTube.git'

cd API_YaTube
```
2. Cоздать и активировать виртуальное окружение:
```bash
python3 -m venv env

source env/bin/activate
```
3. Установить зависимости из файла requirements.txt:
```bash
python3 -m pip install --upgrade pip

pip install -r requirements.txt
```
4. Выполнить миграции:
```bash
cd api_final_yatube

python3 manage.py migrate
```
5. Запустить проект (в режиме сервера Django):
```bash
python3 manage.py runserver
```
Документация к проекту
----------
Документация для API [доступна по ссылке](http://localhost:8000/redoc/) после установки приложения.

