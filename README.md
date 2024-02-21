### Описание проекта:
Проект должен упрощать работу разрабочика приложений одной тематики - api_final_yatube подготавливает json-документы для работы интерфейсов.
Основная директория проекта - yatube_api; в ней описаны настройки проекта и ссылки включающие urls приложений; в проекте есть два приложения api и post; в api прописаны сериализаторы для моделей (Post, Group, Follow, Comment) из приложения post и view-функции;


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/lipkerton/api_final_yatube.git
```

```
cd kittygram
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