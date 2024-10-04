
# Star Project

Это веб-приложение на основе Django для судостроительного завода "Звёздочка" в Северодвинске.

## Содержание
- [Обзор проекта](#обзор-проекта)
- [Установка](#установка)
- [Использование](#использование)
- [Функциональные возможности](#функциональные-возможности)

## Обзор проекта
Проект предназначен для управления и отображения информации о заводе "Звёздочка". Включает в себя различные модули и функциональные возможности для улучшения работы и взаимодействия сотрудников.

## Установка
1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/DyakArt/star.git
   ```
2. Перейдите в директорию проекта:
   ```bash
   cd star
   ```
3. Создайте и активируйте виртуальное окружение:
   ```bash
   python -m venv venv
   source venv/bin/activate   # для Windows: venv\Scripts\activate
   ```
4. Установите зависимости:
   ```bash
   pip install -r requirements.txt
   ```
5. Выполните миграции базы данных:
   ```bash
   python manage.py migrate
   ```
6. Запустите сервер разработки:
   ```bash
   python manage.py runserver
   ```

## Использование
После запуска сервера разработки, откройте веб-браузер и перейдите по адресу `http://127.0.0.1:8000/`, чтобы получить доступ к приложению.

## Функциональные возможности
- **Документация**: Раздел для документации и информации о заводе.
- **Вакансии**: Модуль для управления вакансиями и подачи заявок на работу.
- **Главная страница**: Основная информация и новости завода.
- **Административная панель**: Для управления контентом и пользователями (доступно только администраторам).
