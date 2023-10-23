## api_yamdb
### Описание проекта
Проект, основанный на Django REST API, позволяет получать информацию в формате JSON о произведениях, фильтрации по жанру или категории. Авторизованные пользователи могут оценивать, оставлять отзывы и комментарии к отзывам.

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Gustcat/api_yamdb.git
```

```
cd api_yamdb
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

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

### Авторы
Alex Alekhov https://github.com/inrag3
Ekaterina Gustova https://github.com/Gustcat
Кирилл Антонов https://github.com/Kirill-Antonov91
