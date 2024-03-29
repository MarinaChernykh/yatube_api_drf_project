# Проект API для Yatube

## Описание
Проект **API для Yatube** содержит реализацию работы API для социальной сети Yatube.

Социальная сеть Yatube представляет собой пространство, где пользователи могут публиковать текстовые записи и фотографии, 
комментировать свои и чужжие записи, а также подписываться на интересных им авторов, чтобы следить за их публикациями.

Через API также реализованы механизмы регистрации и авторизации пользователей, 
а также контроль прав доступа к тем или иным операциям над записями.

## Технологии
- Python 3.7
- Django 3.2
- DjangoRestFramework 3.12
- SQLite

## Как запустить проект

1. Клонировать репозиторий на локальный компьютер
```
git clone https://github.com/MarinaChernykh/yatube_api_drf_project.git
```
2. Создать и активировать виртуальное окружение: 
```
python -m venv venv
source venv/bin/activate
```
3. Установить зависимости из файла requirements.txt:
```
python -m pip install --upgrade pip
pip install -r requirements.txt
```

4. Перейти в папку yatube_api и выполнить миграции:
```
cd yatube_api/
python manage.py migrate
```
5. Запустить проект:
```
python manage.py runserver
```

## Документация и примеры запросов к API
Запустив проект, вы сможете ознакомиться с детальной документацией по API Yatube, представленной в формате Redoc, по адресу:
<http://127.0.0.1:8000/redoc/>

## Автор
Марина Черных
