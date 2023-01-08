# Yatube
Социальная сеть с возможностью создания, редактирования и комментирования постов.
Также доступна возможность подписки на автора. Функционал API описан [здесь](yatube_api/static/redoc.yaml).

## Как запустить проект:

1. Клонировать репозиторий и перейти в него в командной строке:

    `git clone https://github.com/vellic0ncent/YatubeSocialNetAPI.git`
    
    `cd yatube_api`

2. Cоздать и активировать виртуальное окружение:

    `python3 -m venv env`

    `source env/bin/activate`

3. Установить зависимости из файла requirements.txt:

    `python3 -m pip install --upgrade pip`

    `pip install -r requirements.txt`

4. Выполнить миграции:

    `python3 manage.py migrate`

5. Запустить проект:

    `python3 manage.py runserver`
