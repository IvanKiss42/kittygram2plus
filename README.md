## :exclamation:  Это промежуточная стадия разработки проекта https://github.com/IvanKiss42/kittygram_final  

:smile_cat: Kittygram - блог о домашних питомцах всех расцветок и нравов. Пользователи могут создавать страницы своих питомцев с текстовым описанием, изображением и списком достижений.  

:computer: Стек технологий: Python, Django, REST API, JWT  

В данной версии были добавлены: пагинация для страниц типа list, возможность фильтровать и сортировать список выдачи на этих страницах.   Данная версия предполагает только локальное использования и локальную проверку работы Django моделей, API и JWT токена для этого:  

Cоздайте и активируйте виртуальное окружение:

```bash
python -m venv venv
source venv/Scripts/activate
```

Установите зависимости из файла requirements.txt:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Выполните миграции:

```bash
python manage.py migrate
```

Запустить проект:
```bash
python manage.py runserver
```