# Zada4i
Приложение для планирования своих задач.

## Стек технологий
- Python 3.9
- Django 3.2.3
- Django REST Api 3.12.4
- React 

## Как запустить проект в тестовом режиме.
- Клонировать проект на жесткий диск.
### Backend
(Windows)
- В папке /backend создать виртуальное окружение: $ python -m venv venv
- Активировать виртуальное окружение: $ source venv/Scripts/Activate
(Linux)
- В папке /backend создать виртуальное окружение: $ python3 -m venv venv
- Активировать виртуальное окружение: $ source source venv/bin/activate
Далее
- Установить зависимости: $ pip install -r requirements.py
- Выполнить миграции БД: $ python manage.py migrate
- Для доступа в админ-панель создайте супер-пользователя: $ python manage.py createsuperuser
- Запустить проект: $ python manage.py runserver
  Админ-панель будет доступен по адресу: http://127.0.0.1:8000/admin/
  API будет доступно по адресу: http://127.0.0.1:8000/api/
### Frontend
- Установить Node.js® https://nodejs.org/en/download
- Находясь в директории проекта, установить зависимости: $ npm i
- Запустить проект: $ npm run start
  Фронт будет доступен по адресу: http://localhost:3000
