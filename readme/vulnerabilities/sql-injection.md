# SQL injection

SQL-инъекция (SQLi) — это уязвимость веб-безопасности, которая позволяет злоумышленнику вмешиваться в запросы, которые приложение делает к своей базе данных.

Обычно это позволяет злоумышленнику просматривать данные, которые он обычно не может получить. Это могут быть данные, принадлежащие другим пользователям, или любые другие данные, к которым может получить доступ само приложение.

В некоторых ситуациях злоумышленник может эскалировать атаку путем внедрения SQL-кода, чтобы скомпрометировать базовый сервер или другую внутреннюю инфраструктуру, или выполнить атаку типа «отказ в обслуживании».

### Каковы последствия успешной атаки SQL-инъекцией? <a href="#what-is-the-impact-of-a-successful-sql-injection-attack" id="what-is-the-impact-of-a-successful-sql-injection-attack"></a>

Успешная атака с внедрением SQL-кода может привести к несанкционированному доступу к конфиденциальным данным, таким как пароли, данные кредитной карты или личная информация пользователя.

### Примеры SQL-инъекций <a href="#sql-injection-examples" id="sql-injection-examples"></a>

#### [Retrieving hidden data](https://portswigger.net/web-security/sql-injection#retrieving-hidden-data) - Получение скрытых данных, где вы можете изменить запрос SQL, чтобы получить дополнительные результаты.

#### [Subverting application logic](https://portswigger.net/web-security/sql-injection#subverting-application-logic) - Подрыв логики приложения, когда вы можете изменить запрос, чтобы он мешал логике приложения.

#### [UNION attacks](https://portswigger.net/web-security/sql-injection/union-attacks) - Атаки UNION, когда вы можете получить данные из разных таблиц базы данных.

#### [Examining the database](https://portswigger.net/web-security/sql-injection/examining-the-database) - Изучение базы данных, откуда можно извлечь информацию о версии и структуре базы данных.

#### [Blind SQL injection](https://portswigger.net/web-security/sql-injection/blind) - "Слепая" SQL инъекция, при которой результаты запроса, которым вы управляете, не возвращаются в ответах приложения.
