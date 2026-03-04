# Example Flask Site

Учебный проект простого многостраничного сайта на Flask с использованием SQLAlchemy для работы с базой данных.

## Стек технологий
* **Python 3.x**
* **Flask** — веб-фреймворк
* **Flask-SQLAlchemy** — работа с БД (SQLite)
* **Jinja2** — шаблонизация HTML

## Структура проекта
* `app.py` — основной файл приложения и логика маршрутов.
* `constants.py` — конфигурационные данные и константы.
* `templates/` — HTML-шаблоны (используется наследование от `base.html`).
* `static/` — CSS стили и изображения.
* `instance/` — локальная база данных SQLite.

## Как запустить локально

1. **Клонируйте репозиторий:**
   ```bash
   git clone https://github.com/pakvakunchik/Example_Flask_site
   
Создайте и активируйте виртуальное окружение:
python -m venv venv

Установите зависимости:
pip install -r requirements.txt

Запустите приложение:
python app.py

Сайт будет доступен по адресу: http://127.0.0.1:5000

