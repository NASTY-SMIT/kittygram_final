## _Kittygram — социальная сеть для обмена фотографиями любимых питомцев._
##_Это полностью рабочий проект, который состоит из бэкенд-приложения на Django и фронтенд-приложения на React._
### Как запустить backend проект: 
 
Клонировать репозиторий и перейти в него в командной строке: 
 
``` 
git clone https://github.com/yandex-praktikum/kittygram_backend.git 
``` 
 
``` 
cd kittygram_backend 
``` 
 
Cоздать и активировать виртуальное окружение: 
 
``` 
python3 -m venv env 
``` 
 
* Если у вас Linux/macOS 
 
    ``` 
    source env/bin/activate 
    ``` 
 
* Если у вас windows 
 
    ``` 
    source env/scripts/activate 
    ``` 
 
``` 
python3 -m pip install --upgrade pip 
``` 
 
Установить зависимости из файла requirements.txt: 
 
``` 
pip install -r requirements.txt 
``` 
 
Выполнить миграции: 
 
``` 
python3 manage.py migrate 
``` 
 
Запустить проект: 
 
``` 
python3 manage.py runserver 
```

## Для заполнения файла переменных окружения .env вам понадобится следовать следующим шагам:

- Создайте файл с названием .env в корневой папке вашего проекта.
-  Откройте файл .env в текстовом редакторе.
- Добавьте переменные окружения в формате KEY=VALUE. Каждая переменная должна быть указана на отдельной строке. Например:
```sh
   POSTGRES_DB=mydatabase
   POSTGRES_USER=myuser
   POSTGRES_PASSWORD=mypassword
   DB_NAME=mydatabase
   DB_HOST=localhost
   DB_PORT=5432
   SECRET_KEY=mysecretkey
   DEBUG=True
   ALLOWED_HOSTS=localhost,127.0.0.1
   TIME_ZONE=Europe/Moscow
   USE_TZ=True
```
(Замените mydatabase, myuser, mypassword, localhost, 5432, mysecretkey, True, localhost,127.0.0.1, Europe/Moscow и True на соответствующие значения для вашего окружения.)
- Сохраните файл .env.

Автор: Shmidt Anastasia
