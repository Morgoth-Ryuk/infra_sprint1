# infra_sprint1
Приложение для публикации котиков.

Клонировать репозиторий и перейти в него в командной строке:

git clone git@github.com:Morgoth-Ryuk/infra_sprint1.git

cd infra_sprint1

Cоздать и активировать виртуальное окружение:

python3 -m venv env

Если у вас Linux/macOS

source env/bin/activate

Если у вас windows

source env/scripts/activate

python3 -m pip install --upgrade pip

Установить зависимости из файла requirements.txt:

pip install -r requirements.txt

Выполнить миграции:

python3 manage.py migrate

Запустить проект:

python3 manage.py runserver
