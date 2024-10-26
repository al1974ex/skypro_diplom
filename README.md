# skypro_diplom
Дипломная работа. Архитектура фреймворка
Проект По автоматизации тестирвоания API и UI тестирования на python для сервиса Бронирования туров
[Сервис "Fun & sun"] (https://fstravel.com/) дает возможность искать и бронировать туры, отели, покупать авиабилеты. В процессе работы составлено 5 UI и 5 API тестов, и сформирован отчет Allure о результатах прохождения автотестов.

Зависимости:
-selenium, -requests, -pytest, -allure

Шаги:
Создать удаленный репозиторий в github (https://github.com/annagenerozova/skypro_-diploma)
Установить зависимости
запустить тесты с указанием пути к директории результатов тестирования pytest --alluredir allure-result
Сформировать отчет --allure serve allure-result
Структура
requirements.txt - файл с зависимостями
test*: -test_ui.py - UI тесты -test_api.py -API тесты
MainPage.py - файл с методами для UI тестирования
