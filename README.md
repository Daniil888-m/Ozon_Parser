Система парсинга товаров с маркетплейса Озон

Данное веб-приложение предназначено для автоматического извлечения и отображения информации о товарах с маркетплейса Озон. Оно позволяет пользователям эффективно собирать данные о ценах и описаниях товаров, а также управлять этими данными через удобный интерфейс.

## Основные функции:

-   Парсинг товаров: Программа извлекает название, цену, описание и ссылки на товары с маркетплейса Озон, используя библиотеки Requests и BeautifulSoup.
-   Хранение данных: Сохранение полученной информации в локальной базе данных MySQL для последующего доступа и анализа.
-   Веб-интерфейс: Все данные отображаются на веб-странице в виде карточек товаров, что обеспечивает пользователям удобный доступ к информации о каждом товаре.
-   Изменение цен: Пользователи могут отслеживать процентное изменение цен товаров по сравнению с первоначальными значениями.
-   Управление товарами: Реализованы функции добавления и удаления карточек товаров через веб-интерфейс.

## Технические характеристики:

-   Программное обеспечение разработано на основе фреймворка Django и использует MySQL в качестве базы данных.
-   Кроссбраузерная совместимость с современными версиями браузеров (Chrome, Firefox).
-   Устойчивое функционирование при парсинге большого числа ссылок с обработкой возможных ошибок.

## Этапы разработки:

1. Создание структуры базы данных и интеграция с Django.
2. Разработка парсера для сбора данных с маркетплейса Озон.
3. Проектирование и внедрение веб-интерфейса для управления товарами.
4. Тестирование всех компонентов приложения и исправление возможных ошибок.
5. Развертывание и запуск системы на сервере.

## Установка:

Код предоставлен в виде исходного кода и инсталлятора для установки на сервер. Ожидается использование системы контроля версий, такой как GitHub, для хранения и управления кодом проекта.

## Экономический эффект:

Представленная система упрощает процесс мониторинга цен и автоматизирует сбор информации, что значительно экономит время пользователей и повышает эффективность их работы с данными о товарах.
