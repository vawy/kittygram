### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:vawy/kittygram.git
```

```
cd kittygram
```
#### Backend

Cоздать и активировать виртуальное окружение:

```
cd kittygram_backend
python -m venv env
```

* Linux/macOS

    ```
    source env/bin/activate
    ```

* Windows

    ```
    source env/scripts/activate
    ```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

#### Frontend

```
cd kittygram_frontend
```

Установить зависимости:

```
npm i
```

Запустить проект:

```
npm run start
```
