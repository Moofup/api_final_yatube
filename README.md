# API к проекту Yatube

## Описание

API для использования социальной сети Yatube. 
Реализован следующий функционал: 
Подписка на пользователей, поиск всех подписчиков по полю
Просмотр, содание, редактирование и удаление постов
Просмотр тематических групп
Добавление, чтение, редактирование и удаление комментариев 

## Стек 
Python3, Django 2.2 LTS, Django REST framework, SQLite3, Simple-JWT

### Установка

Клонируйте репозиторий:

`$ git clone https://github.com/Moofup/api_final_yatube.git`

Создайте виртуальное окружение:

`$ python -m venv venv`

Устанавите зависимости:

`$ pip install -r requirements.txt`

Примените миграции:

`$ python manage.py migrate`

Запустите локальный django-сервер:

`$ python manage.py runserver`

