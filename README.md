Пример веб сервиса с авторизацией и управлением пользователями
-----------------------------------

Основные использованные технологии: Spring, Hibernate, mySQL, Tomcat, Maven

IDE: IntelliJ IDEA

**Для проверки:**

Для удобства рекомендуется использовать указанное выше ide.
Настройки подключения к базе mySQL в файле '/resources/database.properties'.
Для быстрого заполнения базы данный для проверки выполнить скрипт '/resources/database.sql'.

По условию добавил собранный WAR пакет, но так как настройки бд не вынесены во внешние зависимости, а находятся в'/resources/database.properties', необходимо указать данные подключения и пересобрать пакет.  Поместить в <TOMCAT_HOME>/webapps, после чего зайти на http://localhost:8080/X-Users/ для локального запуска или по адресу внешнего сервера при запуске на удалённом ресурсе.

В связи с ограниченными сроками разработки в три дня проект ещё достаточно сырой и требует доработки. Перечень планируемых улучшений приведён ниже.

**Планируемые улучшения и исправления:**
- Добавить страницу поиска для пользователей, а также отдельный поиск для страницы администрирования.
- Добавить дополнительные роли для пользователей, а также установление роли из панели управления, управление группами.
- Переработать таблицу вывода пользователей, перенести отображение адреса с отдельной страницы на встроенное.
- Добавить Unit тестирование, написать тесты.
- Перенести настройку подключения к бд во внешнюю конфигурацию.
- Написать документацию.

![alt text](https://raw.githubusercontent.com/0xFaulty/X-Users/master/screenshots/ex4.png)
![alt text](https://raw.githubusercontent.com/0xFaulty/X-Users/master/screenshots/ex3.png)
![alt text](https://raw.githubusercontent.com/0xFaulty/X-Users/master/screenshots/ex2.png)
![alt text](https://raw.githubusercontent.com/0xFaulty/X-Users/master/screenshots/ex1.png)

