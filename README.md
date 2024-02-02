# Taski
Приложение для планирования своих задач.
Цель проекта - отработка практической части курса по взаимодействию по API, использованию ClassBasedViews

Используется backend на Django и frontend на NodeJS

## Запуск backend

Склонируйте проект, создате и активируйте виртуальное окуржение, установите зависимости
```
git clone git@github.com:den-sad/taski.git
cd taski

python3 -m venv .venv
source .venv/bin/activate

pip install --upgrade pip
pip install -r requirements.txt
```

Примените миграции и запустите backend

```
python3 ./backend/manage.py migrate
python3 ./backend/manage.py runserver
```

## Запуск frontend

Установите Node.js, используя дистрибутивы и инструкции с официального сайта проекта.

Установите зависимости

```
cd ./frontend
npm i 
```

Заустите frontend

```
npm run start 
```

Адрес для подключения - http://localhost:3000