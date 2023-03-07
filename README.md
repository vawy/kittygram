## Описание

Kittygram - это сервис, где пользователь может выкладывать Котиков с их достижениями, 
изменять информацию о них и удалять. 

#### Что могут делать неавторизованные пользователи
- Создать аккаунт.
- Просматривать котиков на главной.
- Просматривать отдельных котиков.

#### Что могут делать авторизованные пользователи
- Входить в систему под своим логином и паролем.
- Выходить из системы (разлогиниваться).
- Создавать/редактировать/удалять собственных котиков.
- Просматривать котиков на главной.
- Просматривать отдельные страницы котиков.
- Добавлять достижения котиков.

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
