# Проект YaMDb

Проект YaMDb собирает отзывы пользователей на произведения. Сами произведения в YaMDb не хранятся, здесь нельзя посмотреть фильм или послушать музыку.
Произведения делятся на категории («Книги», «Фильмы» и т.д.) и жанры («Хоррор», «Детектив» и т.д.). Реализована возможность оставления отзывов и коментариев к ним.

Доступ к проекту черезе API (на основе Django REST Framework).

*Когда вы запустите проект, по адресу  [http://127.0.0.1:8000/redoc/] будет доступна документация*


**Как запустить проект**:
- Клонировать репозиторий и перейти в него в командной строке:

git clone git@github.com:FruityBang/API-YaMDb-last.git

cd api_yamdb

- Cоздать и активировать виртуальное окружение:

python -m venv venv

source venv/Scripts/activate (Windows) source venv/bin/activate (Linux)

- Установить зависимости из файла requirements.txt:

python -m pip install --upgrade pip

pip install -r requirements.txt

- Выполнить миграции: cd yatube/

python manage.py migrate

- Запустить проект:

python manage.py runserver
