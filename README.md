
 

## 1. Введение

Данное руководство построено на примере
[Tech Differences](https://techdifferences.com/difference-between-mysql-and-postgresql.html "Tech Differences"), [Node Postgres ](https://node-postgres.com/ "Node Postgres ") и [Get started postgresqltutorial](http://www.postgresqltutorial.com/postgresql-select/ "Get started postgresqltutorial")
 

## 2. Обзор
### Разница между MySQL и PostgreSQL 

#### Definition of MySQL

Определение MySQL MySQL - это система управления реляционными базами данных с открытым исходным кодом. 

Имя MySQL - это сочетание имени дочери соучредителя Майкла Видениуса «My» и SQL - аббревиатуры для языка структурированных запросов.

MySQL является продуктом корпорации Oracle. MySQL поддерживает много стандарта SQL. 

Что касается операционной системы, то MySQL поддерживается практически всеми операционными системами, такими как Windows, Mac OS X, Linux, BSD, UNIX, z / OS, Symbian, AmigaOS.

Система баз данных MySQL используется в сети для добавления, доступа и управления данными в Интернете.

В MySQL инструмент phpMyAdmin отвечает за предоставление графического интерфейса и интерфейса SQL. 

MySQL не предлагает опцию резервного копирования, но использует Mysqldump и инструмент XtraBackup для резервного копирования. 

MySQL предлагает временные таблицы, но не обеспечивает материализованное представление. Поскольку MySQL является только управлением реляционной базой данных, он не предоставляет объект предметной области.



#### Definition of PostgreSQL

PostgreSQL - это система управления объектно-реляционными базами данных с открытым исходным кодом. 

Группа глобального развития разрабатывает PostgreSQL. Он использует множество стандартов SQL. 

PostgreSQL полностью совместим с ACID. Поддержка внешнего ключа, триггеры и объединение доступны в PostgreSQL. 

PostgreSQL поддерживается операционными системами Windows, Mac OS X, Linux и BSD, но не операционными системами UNIX, z / OS, Symbian, AmigaOS. 

Язык программирования PostgreSQL очень расширяем. 

PostgreSQL использует инструмент pgAdmin для обеспечения графического интерфейса и интерфейса SQL. 

PostgresSQL предлагает возможность онлайн резервного копирования. Он предоставляет временные таблицы, а также материализованное представление. и это также обеспечивает объект предметной области.

## 3. Создание и подключение базы данных
### PostgreSQL Tutorial 

PSQL Shell (psql)
1. Введите информацию об учетной записи для входа на сервер базы данных PostgreSQL. Вы можете использовать значение по умолчанию, предоставляемое psql, нажав клавишу Enter.

       Server [localhost]:
       Database [postgres]:
       Port [5432]:
       Username [postgres]:
       Password for user postgres:

2. Введите следующую инструкцию CREATE DATABASE, чтобы создать новую базу данных admindb.

       CREATE DATABASE admindb;


Выделите отдельные строки с помощью оператора [DISTINCT](http://www.postgresqltutorial.com/postgresql-select-distinct/ "DISTINCT")

Сортировать строки с помощью предложения [ORDER BY](http://www.postgresqltutorial.com/postgresql-order-by/ "ORDER BY")
 
Фильтрация строк с использованием предложения [WHERE](http://www.postgresqltutorial.com/postgresql-where/ "WHERE")

Выберите подмножество строк в таблице, используя предложение [LIMIT](http://www.postgresqltutorial.com/postgresql-limit/ "LIMIT") и [FETCH](http://www.postgresqltutorial.com/postgresql-fetch/ "FETCH")


 Группируйте строки в группы с помощью предложения [GROUP BY](http://www.postgresqltutorial.com/postgresql-order-by/ "GROUP BY")
 
 Фильтруйте группы с помощью предложения [HAVING](http://www.postgresqltutorial.com/postgresql-having/"HAVING")
  
 Объединяйте с другими таблицами, используя соединения, такие как [JOINS](http://www.postgresqltutorial.com/postgresql-joins/ "JOINS")  

Выполните операции установки, используя [UNION](http://www.postgresqltutorial.com/postgresql-union/ "UNION"), [INTERSECT](http://www.postgresqltutorial.com/postgresql-intersect/ "INTERSECT") и [EXCEPT](http://www.postgresqltutorial.com/postgresql-tutorial/postgresql-except/  "EXCEPT")

