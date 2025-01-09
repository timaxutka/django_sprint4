# Django Sprint 4

## Описание
Django Sprint 4 - это проект на Django, созданный для демонстрации различных аспектов разработки веб-приложений, включая администрирование, формы, модели и тестирование.

## Установка
Для установки и запуска проекта выполните следующие шаги:

1. Клонируйте репозиторий:
    ```bash
    git clone https://github.com/timaxutka/django_sprint4
    ```
2. Перейдите в директорию проекта:
    ```bash
    cd django_sprint4-main
    ```
3. Создайте виртуальное окружение:
    ```bash
    python -m venv venv
    ```
4. Активируйте виртуальное окружение:
    - Для Windows:
        ```bash
        venv\Scripts\activate
        ```
    - Для macOS и Linux:
        ```bash
        source venv/bin/activate
        ```
5. Установите необходимые зависимости:
    ```bash
    pip install -r requirements.txt
    ```

## Запуск
Для запуска сервера разработки выполните команду:
```bash
python blogicum/manage.py runserver
```

Тестирование
Проект содержит набор тестов, которые можно запустить с помощью pytest. Для этого выполните:
```bash
pytest
```

Структура проекта
```bash
.gitignore - файл, содержащий список файлов и директорий, игнорируемых Git.
LICENSE - файл с лицензией проекта.
README.md - этот файл с описанием проекта.
db.json - база данных в формате JSON.
pytest.ini - конфигурационный файл для pytest.
requirements.txt - список зависимостей проекта.
setup.cfg - конфигурационный файл для настройки проекта.
blogicum/ - основная директория проекта:
manage.py - управляющий файл Django.
blog/ - приложение блога:
__init__.py - инициализационный файл приложения.
admin.py - файл с настройками админки.
apps.py - файл конфигурации приложения.
forms.py - файл с формами.
mixins.py - файл с миксинами.
models.py - файл с моделями.
urls.py - файл с маршрутами.
utils.py - файл с утилитами.
views.py - файл с представлениями.
migrations/ - директория с миграциями:
0001_initial.py - первая миграция.
0002_auto_20240321_2132.py - миграция.
0003_auto_20240322_1944.py - миграция.
0004_auto_20240403_1451.py - миграция.
0005_alter_comment_post.py - миграция.
0006_alter_comment_author.py - миграция.
__init__.py - инициализационный файл пакета миграций.
tests/ - директория с тестами:
__init__.py - инициализационный файл пакета тестов.
adapters/ - адаптеры для тестирования:
comment.py - адаптер для комментариев.
model_adapter.py - адаптер моделей.
post.py - адаптер для постов.
student_adapter.py - адаптер студентов.
user.py - адаптер для пользователей.
fixtures/ - директория с фикстурами:
categories.py - фикстуры для категорий.
comments.py - фикстуры для комментариев.
locations.py - фикстуры для местоположений.
posts.py - фикстуры для постов.
types.py - фикстуры для типов.
form/ - директория с тестами форм:
base_form_tester.py - базовый тестер форм.
base_tester.py - базовый тестер.
delete_tester.py - тестер удаления.
find_urls.py - тестер поиска URL.
comment/ - тесты для форм комментариев:
create_form_tester.py - тестер создания формы.
delete_tester.py - тестер удаления.
edit_form_tester.py - тестер редактирования формы.
find_urls.py - тестер поиска URL.
post/ - тесты для форм постов:
create_form_tester.py - тестер создания формы.
delete_tester.py - тестер удаления.
edit_form_tester.py - тестер редактирования формы.
find_urls.py - тестер поиска URL.
form_tester.py - тестер формы.
user/ - тесты для форм пользователей:
edit_form_tester.py - тестер редактирования формы.
```
