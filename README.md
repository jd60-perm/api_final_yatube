# API для Yatube

### Описание проекта:

Учебный проект. API для мини социальной сети Yatube - публикация постов, с возможностью размещения картинок, комментариев к постам и подписки на авторов.
Проект еализован на фреймворке Django и встроенной в него БД sqlite с применением библиотеки Django REST framework.


### Системные требования: 

python 3.7


### Как запустить проект:

Клонировать репозиторий и перейти его директорию:

```
git clone https://github.com/jd60-perm/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
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
python yatube_api/manage.py runserver
```

![example workflow](https://github.com/jd60-perm/api_final_yatube/actions/workflows/main.yml/badge.svg)