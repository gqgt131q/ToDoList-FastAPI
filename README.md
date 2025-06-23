ToDo List на FastAPI с SQLite и SQLAlchemy 🐍

Полноценное веб-приложение для управления задачами с бэкендом на FastAPI и фронтендом на HTML/CSS/JS 📝

Описание проэкта ☕

Это простое, но функциональное веб-приложение для управления списком задач, разработанное с использованием:

    Backend: FastAPI (Python) + SQLAlchemy (ORM) + SQLite (база данных)

    Frontend: Чистый HTML/CSS/JavaScript без дополнительных фреймворков

Проект идеально подходит для:

    Изучения работы FastAPI

    Понимания взаимодействия фронтенда и бэкенда

    Практики работы с SQLAlchemy ORM

    Управления личными задачами

🚀 Основные функции

Управление задачами:

    Добавление новых задач

    Отметка задач как выполненных

    Удаление задач

    Фильтрация задач (Все/Активные/Завершенные)

    Статистика по задачам

⚙️ Технологии

Backend:

    Python 3.9+

    FastAPI (веб-фреймворк)

    SQLAlchemy (ORM)

    SQLite (база данных)

    Uvicorn (ASGI-сервер)

Frontend:

    Чистый HTML5

    CSS3 (адаптивный дизайн)

    Vanilla JavaScript (без jQuery)

    AJAX-запросы к API

🛠️ Установка и запуск

Клонировать репозиторий:

    bash

    git clone https://github.com/yourusername/fastapi-todo-list.git
    cd fastapi-todo-list

Создать и активировать виртуальное окружение:

    bash

    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate     # Windows

Установить зависимости:

    bash

    pip install -r requirements.txt

Запустить приложение:

    bash

    uvicorn main:app --reload

Открыть в браузере:

    http://localhost:8000
