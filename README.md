# Sprint_6_
# Проект по автоматизации тестирования Яндекс.Самокат
# Структура проекта:

# Корневая директория проекта
PythonProject13
├── .venv  # Виртуальное окружение
│   ├── bin
│   ├── lib
│   └── pyvenv.cfg
├── locators  # Локаторы элементов
│   ├── main_page_locators.py
│   └── order_page_locators.py
├── pages  # Страницы приложения
│   ├── __init__.py
│   ├── base_page.py
│   ├── main_page.py
│   └── order_page.py
├── tests  # Тесты
│   ├── conftest.py
│   ├── test_logo_click.py
│   ├── test_main_page.py
│   └── test_order_page.py
├── .gitignore  # Игнорировать файлы
├── data.py  # Данные для тестов
├── main.py  # Основной файл
└── README.md  # Описание проекта