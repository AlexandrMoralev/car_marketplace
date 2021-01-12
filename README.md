[![Build Status](https://travis-ci.com/AlexandrMoralev/car_marketplace.svg?branch=main)](https://travis-ci.com/AlexandrMoralev/car_marketplace)
[![codecov](https://codecov.io/gh/AlexandrMoralev/car_marketplace/branch/main/graph/badge.svg?token=YL9EFXAF07)](https://codecov.io/gh/AlexandrMoralev/car_marketplace)

## Web приложение - площадка продажи авто.
Портал для размещения объявлений.
Для незарегистрированных пользователей доступен просмотр активных объявлений и поиск. 
Зарегистрированный пользователь имеет возможность добавлять и редактировать, а также просматривать актуальные и закрытые объявления.

#### Технологии и инструменты:

* **Server side**: Java 11, Tomcat 8.5, Servlet api 4.0, Hibernate 5, Apache FileUpload, Jackson, Junit 5, Stream api   
* **Client side**: Javascript es5, Jquery 3.1, Ajax, Bootstrap 4, HTML, CSS

* **Tools**: Maven, Checkstyle
* **CI/CD**:  Travis ci, Jacoco, Codecov
* **DB**: Postgresql 42.2.5, h2database 1.4.200

#### Скриншоты приложения:

* Основная страница. Доступна всем пользователям.
 Реализован поиск объявлений по заданным параметрам:
![](/screenshots/main-page-filters.png)

* Таблица с объявлениями,
 отображаются только активные объявления, отсортированные по дате добавления. Фото в объявлении отображаются в режиме "карусель":
![](/screenshots/main-page-items.png)

* Страница регистрации и аутентификации. Для доступа в аккаунт и добавления объявлений на портал.
![](/screenshots/login-page.png)

* Аккаунт зарегистрированного пользователя. Доступен просмотр и редактирование активных и неактивных объявлений.
![](/screenshots/account-page.png)

* Страница добавления нового объявления.
![](/screenshots/create-item-page.png)


