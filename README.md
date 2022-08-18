# Приложение "Цитаты"

_______________________________________

### Описание:
Простое API приложение, позволяющее добавлять цитаты. Редактировать и удалять цитаты доступно только пользователем с правами модератора. Так же есть возможность ставить рейтинг цитатам.

_______________________________________________________

Для запуска проекта установите python версии 3.10

После клонирования перейдите в склонированную папку и выполните следующие команды:

Создайте виртуальное окружение командой
```bash
python -m venv venv
```

Активируйте виртуальное окружение командой
```bash
source venv/bin/activate
или
venv\Scripts\activate
```

Установите зависимости командой

```bash
pip install -r requirements.txt
```

Примените миграции командой
```bash
./manage.py migrate
```

Загрузите фикстуры командой
```bash
./manage.py loaddata fixtures/auth.json
./manage.py loaddata fixtures/dump.json
```

Чтобы запустить сервер выполните:

```bash
./manage.py runserver
```

Для доступа в панель администратора перейдите по ссылке http://localhost:8000/admin

Профиль админа:
*Логин - admin*
*Пароль - admin*

