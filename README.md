# Описание

Проект «API для Yatube». Проект создан в учебных целях в рамках курса "Python бэкенд-разработчик" от Яндекс.Практикум.

# Установка

1. Клонировать репозиторий и перейти в него в командной строке:
```
git clone 'https://github.com/NikitaChalykh/api_final_yatube.git'
```
```
cd api_final_yatube
```
2. Cоздать и активировать виртуальное окружение:
```
python3 -m venv env
```
```
source env/bin/activate
```
3. Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
```
```
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
# Документация

Документация для API Yatube доступна по адресу:
```
"http://127.0.0.1:8000/redoc/"
```