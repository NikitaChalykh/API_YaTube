# Установка

Клонировать репозиторий и перейти в него в командной строке:

1. git clone 'https://github.com/NikitaChalykh/api_final_yatube.git'

2. cd api_final_yatube

3. Cоздать и активировать виртуальное окружение:
python3 -m venv env

4. source env/bin/activate

5. python3 -m pip install --upgrade pip

6. Установить зависимости из файла requirements.txt:
    pip install -r requirements.txt

7. Выполнить миграции:
    python3 manage.py migrate

8. Запустить проект:
    python3 manage.py runserver
