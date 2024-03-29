# Информационные системы и технологии
Репозиторий курса СГН3 Информационные системы и технологии

- #### Образ виртуальной машины Linux [Ubuntu 22.04](https://github.com/iu5git/Standards/blob/main/Linux/Linux.md) для выполнения заданий курса
- #### [Видеозаписи лекций](https://youtube.com/playlist?list=PLLELLTvDgUQ9cpB1XzSuZ0mNSBkbjVNJ_) в YouTube

### Модуль 1. Веб-приложения. Лекции

* **Лекция 1. Введение в Web**

[Основы Web: HTML, URI, кратко HTTP. CSS, кратко JavaScript. Основы работы браузера. DOM](https://github.com/iu5git/JavaScript/blob/main/lectures/lec1.pdf)

* **Лекция 2. Основы JavaScript**

[операторы, функции, коллекции, классы](https://github.com/iu5git/JavaScript/blob/main/lectures/lec2.pdf)

* **Лекция 3. История Web, трехуровневая модель приложений, Шаблонизация, Django**

[История Web, трехуровневая модель приложений, Шаблонизация, Django](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_1_Web.pdf)

* **Лекция 4. Протокол HTTP**

[Протокол HTTP](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_4_HTTP.pdf)

* **Лекция 5. База данных PostgreSQL. Админка Django и ORM**

[Базы данных, ER, PostgreSQL. ORM. Админка Django. Курсоры](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_2_Databases_ORM.pdf)

* **Лекция 6. Методология Agile. Диаграммы UML**

[Методология Agile, состав команды. Диаграммы UML](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_3_Agile_UML_Git.pdf)


### Модуль 2. Одностраничные приложения (SPA). Лекции

* **Лекция 7. Веб-сервис. Swagger. Микросервисы**

[Веб-сервис. Swagger. Микросервисы](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_5_Web_Service.pdf)

* **Лекция 8. Модель SPA. Фронтенд**

[npm, HTTP, модель клиент-сервер, spa, кратко express, фронтенд](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_7_React_Introduction.pdf)

* **Лекция 9. Запросы AJAX**

[AJAX. JSON/XML, XmlHttpRequest, Cors](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_10_Ajax.pdf)

* **Лекция 10. Асинхронный JavaScript**

[Event Loop, промисы, async/await, fetch](https://github.com/iu5git/JavaScript/blob/main/lectures/lec5.pdf)

* **Лекция 11. Web реального времени**

[HTTP/2, Polling, WebSocket](https://github.com/iu5git/JavaScript/blob/main/lectures/lec7.pdf)

* **Лекция 12. Авторизация. Сессии. Куки**

[Авторизация, куки, токены, хранилище сессий. Ограничение прав на части приложения](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_8_Authorization.pdf)

* **Лекция 13. JWT. SSO**

[JWT. SSO](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_9_jwt.pdf)

### Модуль 1. Веб-приложения
У каждого своя предметная область на 3-7 лабораторные работы: бронирование отелей, билетов в театр/кинотеатр, онлайн-магазин

Основной вариант лаб по беку - это Django. Но есть ещё варианты на `Go`, `Java`, `C#` и `Node.js`

При защите необходимо продемонстрировать работу приложения, UML диаграмму, репозиторий github с кодом и ответить на вопросы.

#### Лабораторная работа 1

Создание калькулятора: верстка на HTML, CSS. LiveServer. Добавить кнопки по варианту.

Контрольные вопросы: HTML, CSS

* [Методические указания](https://github.com/iu5git/JavaScript/blob/main/tutorials/lab1/README.md)

#### Лабораторная работа 2

Создание калькулятора: функции на JS. По вариантам реализовать различные функции калькулятора: log, sin, накопление итога и тд

Контрольные вопросы: JavaScript, HTTP

* [Методические указания](https://github.com/iu5git/JavaScript/blob/main/tutorials/lab2/README.md)

#### Лабораторная работа №3
Базовая шаблонизация в Django для словаря. Создание базового интерфейса для просмотра списка (отели, товары, рейсы и тд) с ссылками и частью полей (цена, город) и при переходе по ссылке другая страница с более подробной информацией о товаре (описание, картинка и тд). 

В приложении должны быть использованы стили, для каждого элемента списка подгружается свое изображение. 

Добавить поле input для ограничения количества записей, отображаемых на странице (по умолчанию отображать все).

На выбор `Django`, `Go`, `Spring`, `Node.js`

Контрольные вопросы: MVC, Django, шаблонизация, HTTP, Web, HTML

* [Методические указания Django](https://github.com/iu5git/web-2022/blob/main/tutorials/lab1-py/lab1_tutorial.md)
* [Методические указания Golang](https://github.com/iu5git/web-2022/blob/main/tutorials/lab1-go/README.md)

#### Лабораторная работа №4
Создание базы данных `PostgreSQL`/`MySQL` (`SQLite` использовать нельзя), подключение к шаблонизатору. Создание админки.

Для карточек таблицы услуг добавить кнопку удаления услуги с помощью выполнения SQL запроса.

ER диаграмма: таблицы, связи, столбцы, типы столбцов и их длина, первичные, вторичные ключи

Контрольные вопросы: ORM, SQL, модель и миграции

* [Методические указания PostgreSQL](https://github.com/iu5git/web-2022/blob/main/tutorials/lab2-db/README.md)
* [Методические указания Django](https://github.com/iu5git/web-2022/blob/main/tutorials/lab2-py/lab2_tutorial.md)
* [Методические указания Golang](https://github.com/iu5git/web-2022/blob/main/tutorials/lab2-go/README.md)

### Модуль 2. Одностраничные приложения (SPA)

#### Лабораторная работа №5
Создание веб-сервиса для получения/редактирования данных из вашей БД. Требуется разработать методы для основных (минимум трех) таблиц вашего приложения. Проверка в swagger/postman. 

Добавить метод для подсчета суммы (количества) покупок/бронирований за определенную дату через обращение к методам модели.

Диаграмма компонентов+классов: компонент сервиса, интерфейс, структура модели по классам

Контрольные вопросы: веб-сервис, микросервисы, REST, RPC

* [Методические указания DRF](https://github.com/iu5git/web-2022/blob/main/tutorials/lab3-py/lab3_tutorial.md)
* [Методические указания Golang](https://github.com/iu5git/web-2022/blob/main/tutorials/lab3-go/README.md)

#### Лабораторная работа 6
Создание проекта через npm, сервер express. Верстка интерфейса с карточками, данные через mock объекты.

Deployment диаграмма: узлы фронтенда, веб-сервиса, базы данных, web-сервера со статикой

Контрольные вопросы: npm

* [Методические указания](https://github.com/iu5git/JavaScript/blob/main/tutorials/lab3/README.md)

#### Лабораторная работа 7
Продолжение Лабораторной работы 6: подключение фронтенда к разработанному в 5 лабораторной API. Cors, запросы XHR или fetch

Sequence диаграмма: получение `HTML` страницы, `AJAX` запросы

Контрольные вопросы: AJAX, json, XmlHttpRequest/fetch

* [Методические указания](https://github.com/iu5git/JavaScript/blob/main/tutorials/lab4/README.md)