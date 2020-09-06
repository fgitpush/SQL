# SQL

> Click :star: if you like the project. Pull Request are highly appreciated.

### Table of Contents

| No. | Questions |
| --- | --------- |
|1  | [SELECT](#why-laravel) |
|2  | [UPDATE](#why-laravel) |
|3  | [DELETE](#why-laravel) |
|4  | [INSERT](#why-laravel) |
|5  | [JOIN](#why-laravel) |
|6  | [UNION](#why-laravel) |
|7  | [SELECT DISTINCT](#why-laravel) |
|8  | [WHERE](#why-laravel) |
|9  | [AND](#why-laravel) |
|10  | [OR](#why-laravel) |
|11 | [NOT](#why-laravel) |
|12  | [SELECT TOP](#why-laravel) |
|13  | [MIN](#why-laravel) |
|14  | [MAX](#why-laravel) |
|15  | [COUNT](#why-laravel) |
|16  | [AVG](#why-laravel) |
|17  | [SUM](#why-laravel) |
|18  | [LIKE](#why-laravel) |
|19  | [Wildcards](#why-laravel) |
|20  | [In](#why-laravel) |
|21  | [Between](#why-laravel) |
|22  | [Alias](#why-laravel) |
|23  | [Inner Join](#why-laravel) |
|24  | [Left Join](#why-laravel) |
|25  | [Right Join](#why-laravel) |
|26  | [Full Join](#why-laravel) |
|27  | [Self Join](#why-laravel) |
|28  | [Group By](#why-laravel) |
|29  | [Having](#why-laravel) |
|30  | [Exists](#why-laravel) |
|31  | [All](#why-laravel) |
|32  | [Any](#why-laravel) |
|33  | [SELECT INTO](#why-laravel) |
|34  | [INSERT INTO SELECT](#why-laravel) |
|35  | [NULL FUNCTIONS](#why-laravel) |
|36  | [STORED PROCEDURES](#why-laravel) |
|37  | [COMMENTS](#why-laravel) |
|38  | [OPERATIONS](#why-laravel) |
|39  | [SQL Create DB](#why-laravel) |
|40  | [SQL Drop DB](#why-laravel) |
|41  | [SQL Backup DB](#why-laravel) |
|42  | [SQL Create Table](#why-laravel) |
|43  | [SQL Drop Table](#why-laravel) |
|44  | [SQL Alter Table](#why-laravel) |
|45  | [SQL Constraints](#why-laravel) |
|46  | [SQL Not Null](#why-laravel) |
|47  | [SQL Unique](#why-laravel) |
|48  | [SQL Primary Key](#why-laravel) |
|49  | [SQL Foreign Key](#why-laravel) |
|50  | [SQL Check](#why-laravel) |
|51  | [SQL Default](#why-laravel) |
|52  | [SQL Index](#why-laravel) |
|53  | [SQL Auto Increment](#why-laravel) |
|54  | [SQL Dates](#why-laravel) |
|55  | [SQL Views](#why-laravel) |
|56  | [SQL Injection](#why-laravel) |
|57  | [SQL Hosting](#why-laravel) |
|58  | [SQL Data Types](#why-laravel) |
|59  | [What is a Database?](#why-laravel) |
|60  | [What is a Relational Database?](#php-inheritance) |
|61  | [What is RDBMS?](#what-is-dependency-manager) |
|62  | [Introduction to SQL](#what-is-api-php) |
|63  | [Naming Conventions](#what-is-channels-php) |
|64 | [Data Integrity](#what-is-console-php) |
|65  | [Database Terms](#what-is-controller) |
|66  | [Atomic Values](#what-are-views) |
|67  | [Relationships](#what-is-a-model) |
|68  | [One-to-One Relationships](#what-is-request-response) |
|69  | [One-to-Many Relationships](#what-are-migrations) |
|70  | [Many-to-Many Relationships](#what-are-seeders) |
|71  | [Designing One-to-One Relationships](#what-are-service-providers) |
|72  | [Designing One-to-Many Relationships](#what-is-middleware) |
|73 | [Parent Tables and Child Tables](#what-is-orm) |
|74 | [Designing Many-to-Many Relationships](#what-is-eloquent) |
|75 | [Introduction to Keys](#what-is-query-builder)
|76 | [Primary Key Index](#what-are-facades) |
|77 | [Look up Table](#what-is-repository-pattern) |
|78 | [Superkey and Candidate Key](#What-is-Authentication-using-Passport-CSRF-XSRF) |
|79 | [Primary Key and Alternate Key](#what-is-unit-testing) |
|80 | [Surrogate Key and Natural Key](#what-is-caching) |
|81 | [Should I use Surrogate Keys or Natural Keys?](#how-to-setup-emails) |
|82 | [Foreign Key](#what-are-queues) |
|83 | [NOT NULL Foreign Key](#what-are-jobs)
|84 | [Foreign Key Constraints](#what-are-advanced-eloquent-and-query-builder) |
|85 | [Simple Key, Composite Key, Compound Key](#which-is-error-management) |
|86 | [Review and Key Points....HA GET IT? KEY points](#how-to-create-an-api) |
|87 | [Introduction to Entity Relationship Modeling](#what-are-events) |
|88 | [Cardinality](#what-are-listeners) |
|89 | [Modality](#what-are-payments-and-cashier) |
|90 | [Introduction to Database Normalization](#what-is-test-driven-development) |
|91 | [1NF (First Normal Form of Database Normalization)](#what-is-package-development) |
|92 | [2NF (Second Normal Form of Database Normalization)](#what-are-laravel-scout-search-and-algolia) |
|93 | [3NF (Third Normal Form of Database Normalization)](#what-is-socialite-auth) |
|94 | [Indexes (Clustered, Nonclustered, Composite Index)](#what-is-vue-js) |
|95 | [Data Types](#How-to-connect-Laravel-with-other-SQL-databases) |
|96 | [Introduction to Joins](#How-to-connect-Laravel-with-non-SQL-databases) |
|97 | [Inner Join](#what-is-lumen) |
|98 | [Inner Join on 3 Tables](#what-is-redis) |
|99 | [Introduction to Outer Joins](#what-is-memcache) |
|100 | [Right Outer Join](#What-is-Horizontal-scaling) |
|101 | [JOIN with NOT NULL Columns](#What-is-Vertical-scaling) |
|102 | [Outer Join Across 3 Tables](#What--Single-Page-Application-in-Laravel) |
|103 | [Alias](#What-are-Microservices-in-Laravel) |
|104 | [ Self Join](#what-is-CSRF-and-JWT-token) |

1. ### What is a Database

It is a structured way of storing data.


 **[⬆ Back to Top](#table-of-contents)**
    
2. ### What is a Relational Database?

It has tables i.e rows and columns. You can create relations i.e joins and unions. 
 
  **[⬆ Back to Top](#table-of-contents)**
  
3. ### What is RDBMS?

The key difference is that RDBMS (relational database management system) applications store data in a tabular form, while DBMS applications store data as files.
 
  **[⬆ Back to Top](#table-of-contents)**
    
 4. Introduction to SQL
``` 
SELECT
UPDATE
DELETE
INSERT
TABLE
JOIN
UNION
Aggregate functions
SELECT DISTINCT
WHERE
AND
OR
NOT
SELECT TOP
MIN
MAX
COUNT
AVG
SUM
LIKE
Wildcards
In
Between
Alias
Inner Join
Left Join
Right Join
Full Join
Self Join
Group By
Having
Exists
All
Any
SELECT INTO
INSERT INTO SELECT
CASE
NULL FUNCTIONS
STORED PROCEDURES
COMMENTS
OPERATIONS
SQL Create DB
SQL Drop DB
SQL Backup DB
SQL Create Table
SQL Drop Table
SQL Alter Table
SQL Constraints
SQL Not Null
SQL Unique
SQL Primary Key
SQL Foreign Key
SQL Check
SQL Default
SQL Index
SQL Auto Increment
SQL Dates
SQL Views
SQL Injection
SQL Hosting
SQL Data Types
```
