# Описание

Проект создавался чтобы улучшить знания Django REST Framework

# Авторы проекта

[Mikhail](https://github.com/tooMike)

## Установка

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/tooMike/infra_sprint1
```

```
cd infra_sprint1
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/bin/activate
```

Перейти в папку backend

```
cd backend
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

## Основные технические требования

Python==3.9

