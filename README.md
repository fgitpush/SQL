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
|103 | [What is the difference between SQL and MySQL?](#What-are-Microservices-in-Laravel) |
|104 | [What are the different subsets of SQL?](#what-is-CSRF-and-JWT-token) |
|105 | [What do you mean by DBMS? What are its different types?](#what-is-CSRF-and-JWT-token) |
|106 | [What do you mean by table and field in SQL?](#what-is-CSRF-and-JWT-token) |
|107 | [What are joins in SQL?](#what-is-CSRF-and-JWT-token) |
|108 | [What is the difference between CHAR and VARCHAR2 datatype in SQL?](#what-is-CSRF-and-JWT-token) |
|109 | [What is the Primary key?](#what-is-CSRF-and-JWT-token) |
|110 | [What are Constraints?](#what-is-CSRF-and-JWT-token) |
|111 | [What is the difference between DELETE and TRUNCATE statements?](#what-is-CSRF-and-JWT-token) |
|112 | [What is a Unique key?](#what-is-CSRF-and-JWT-token) |
|113 | [How to break many:many relationship in 2 SQL tables?](#what-is-CSRF-and-JWT-token) |
|114 | [SQL query to remove duplicate records](#what-is-CSRF-and-JWT-token) |
|115 | [SQL query to count the occurrences of character 'R' in a string](#what-is-CSRF-and-JWT-token) |
|116 | [What is Use of Partial View](#what-is-CSRF-and-JWT-token) |
|117 | [Can you write SQL SPs?](#what-is-CSRF-and-JWT-token) |
|118 | [How will you find out a third retweet using SQL - considering the database of twitter?](#what-is-CSRF-and-JWT-token) |
|119 | [Find the second largest salary from the employee's table](#what-is-CSRF-and-JWT-token) |
|120 | [SQL query consisting sets theory.](#what-is-CSRF-and-JWT-token) |
|121 | [plsql](#what-is-CSRF-and-JWT-token) |
|122 | [SDLC](#what-is-CSRF-and-JWT-token) |
|123 | [Microstrategy Schema Designing](#what-is-CSRF-and-JWT-token) |
|124 | [Redshift](#what-is-CSRF-and-JWT-token) |
|125 | [Write an SQL querry to determine the third highest salary?](#what-is-CSRF-and-JWT-token) |
|126 | [Transactions](#what-is-CSRF-and-JWT-token) |
|127 | [ACID property](#what-is-CSRF-and-JWT-token) |
|128 | [Data Warehouse](#what-is-CSRF-and-JWT-token) |
|129 | [stored procedures vs functions](#what-is-CSRF-and-JWT-token) |
|130 | [Business Intelligence](#what-is-CSRF-and-JWT-token) |
|131 | [Trigger](#what-is-CSRF-and-JWT-token) |
|132 | [Multirow functions](#what-is-CSRF-and-JWT-token) |
|133 | [find top 10 employee by using DENSE RANK](#what-is-CSRF-and-JWT-token) |
|134 | [Write a procedure to store all the data from a table to a collection table.](#what-is-CSRF-and-JWT-token) |
|135 | [What are Aggregate functions](#what-is-CSRF-and-JWT-token) |
|136 | [What is lazy writer.?](#what-is-CSRF-and-JWT-token) |
|137 | [Calculate the no of exp of the employees from the joining date from table?](#what-is-CSRF-and-JWT-token) |
|138 | [how to find out 1st highest salary](#what-is-CSRF-and-JWT-token) |
|139 | [How will you retrieve the crashed database?](#what-is-CSRF-and-JWT-token) |
|140 | [Out of n records the query to pickup 3 to 8 records from a table?](#what-is-CSRF-and-JWT-token) |
|141 | [what are the recovery models?](#what-is-CSRF-and-JWT-token) |
|142 | [Materialized Views](#what-is-CSRF-and-JWT-token) |
|143 | [Whether once can drop an MV, if yes then what will happen to its table](#what-is-CSRF-and-JWT-token) |
|144 | [Types of MV](#what-is-CSRF-and-JWT-token) |
|145 | [Grants and Privileges](#what-is-CSRF-and-JWT-token) |
|146 | [Synonyms](#what-is-CSRF-and-JWT-token) |
|147 | [Autonomous Transactions](#what-is-CSRF-and-JWT-token) |
|148 | [Parallel Hints](#what-is-CSRF-and-JWT-token) |
|149 | [Benefits of Packages](#what-is-CSRF-and-JWT-token) |
|150 | [Performance Tuning](#what-is-CSRF-and-JWT-token) |
|151 | [how many types of subqueries](#what-is-CSRF-and-JWT-token) |
|152 | [cursor](#what-is-CSRF-and-JWT-token) |
|153 | [Group function ](#what-is-CSRF-and-JWT-token) |
|154 | [Difference between where and having](#what-is-CSRF-and-JWT-token) |
|156 | [If there is a table with a primary key would it be possible to create a clustered index on the table?](#what-is-CSRF-and-JWT-token) |
|157 | [OLTP](#what-is-CSRF-and-JWT-token) |
|158 | [OLAP](#what-is-CSRF-and-JWT-token) |
|159 | [SSIS troubleshooting](#what-is-CSRF-and-JWT-token) |
|160 | [Types of backup on SQL](#what-is-CSRF-and-JWT-token) |
|161 | [how to load unstructured data in oracle tables?](#what-is-CSRF-and-JWT-token) |
|162 | [what are all the DDL command ?](#what-is-CSRF-and-JWT-token) |
|163 | [set operators](#what-is-CSRF-and-JWT-token) |
|164 | [Find out the currently running task inside SSIS.](#what-is-CSRF-and-JWT-token) |
|165 | [Explain differences between primary key and unique key](#what-is-CSRF-and-JWT-token) |
|| [Joins (inner, outer, left, right)](#)|
|| Unions and unions all|(#)|
|| Stored procedures
||Functions (scalar and table-valued)
|| Triggers
|| Data manipulation language (DML)
|| Data definition language (DDL)
|| Data control language (DCL)
|| Transactions and concurrency control
|| ACID (Atomicity, Consistency, Isolation, Durability) properties
|| Logical and physical database design
|| Entity-relationship modeling
|| Normalization techniques (1NF, 2NF, 3NF)
|| Data integrity constraints (primary keys, foreign keys, unique constraints)
|| Referential integrity
|| Query optimization
|| Query execution plans
|| Query hints and optimizer directives
|| Index optimization and covering indexes
|| EXPLAIN statement and query profiling
|| Partitioning and sharding
|| Replication and high availability
|| Load balancing and clustering
|| Failover and disaster recovery
|| Backup and restore strategies
|| User authentication and authorization
|| Access control and privileges
|| Encryption and data security
|| Auditing and logging
|| Performance tuning tools (EXPLAIN, SHOW STATUS, etc.)
|| Connection pooling
|| Locking and deadlock detection
|| Query caching and result caching
|| Full-text search
|| Spatial data and GIS applications
|| Performance monitoring and troubleshooting
|| Performance optimization techniques (query rewriting, denormalization, etc.)
|| Data warehousing and OLAP (Online Analytical Processing)
|| Database schema versioning and migration
|| Advanced backup and recovery strategies (point-in-time recovery, incremental backups)
|| Database compression and storage optimization
|| Query rewriting and query hints|
|| Database monitoring and alerting|
|| Database auditing and compliance|
|| Database replication conflict resolution|
|| Advanced locking and isolation levels|
|| Advanced MySQL configuration and optimization settings|
|| Views|
|| Triggers|
|| Computed Columns|
|| Stored Procedures|
|| User Defined Functions|
|| Transaction|
|| Ranking Functions|
|| Aggregate Functions|
|| Prebuilt non-aggregate functions|
|| XML to SQL parsing|
|| Partitions|
|| Dynamic Queries|
|| Joins|
|| Database normalization|
|| Indexing strategies|
|| Subqueries|



why jda
how many type of ALWAYSON IN SQL
Azure Migration
How will you construct the database for 1000 users and what its size?
collection
SQL Loader
Merge statement
Differ bw view nd alias name
PIVOT table
DML and DDL command
Types of joints in sql server
bitmap index
case
analytical functions
What is the output of SUM(NULL)?
indexing
partitioning
How to optimize query ?
Basic questions like rank, dense rank union and collection concepts
How would you reset a sequence in Oracle
Write query to retrive the salary and the employee name from the table employee and salary table.
what is private and public specifier related to package
SQL Tuning and Replication
Normalization
floor and ceil functions
constraints
how to restore master database.
What is truncate in sql?
Find Cumulative sum
how to resolve deadlock in mysql
.net page lifecycle,MPFL,firewalls,sql proc,UDF,Delegates,Authenticatuion ,authorization
basic SQL query for first 5 record in list
Types of SQL statement
Explain SDLC Explain normalisation? Sub queries?
Write a query to find Second highest salary from employee table? and many more.....
delete row 3 with primary key ... add row 3 again but it should come exactly at the place of previously deleted 3
Apti reasoning
What is a default constraint? Explain with an example.
What do you understand by a Character Manipulation function?
high availibility planing
sidaster
how to tune database
Difference between rank and dense rank
SQL Server , Service packs , cluster , alwayson, nirroring
about clustering.
Replication
what is difference between cluster and non cluster index
SQL - HOW TO DELETE DUPLICATE RECORDS BY KEEPING ONE ROW IN MAIN TABLE
DIFFERENCE BETWEEN MERGE AND UNION ALL TRANSFORMATIONS?
what is cross join
concept of DWH
Abt sql, joins, delete, drop, Truncate, unique n primary key foreign, some queries, abt database, cursor, trigger procedure, functions.
what is recursive stored procedure and syntax?
differnce between drop and truncate
Explain oops concepts with Real time example? What is normalization?
sql loader. How to truncate partition. error in extenal table. some scenario based external table and partition. and some query
Indexing and partitioning strategies
does deadlock occur in SQL 
why hexaware
join,transaction,lock,block,deadlock
Quries , Remove duplicates with different functionalities , quest based on analytical functions , rank , desk rank , first , last ,grouping
log shipping, mirroring, clustering, Always on
SQL Replication questions, Question on HADR like Mirroring , logshipping and Always On. SQL performance related question
Normalization and its types.Trigger and its types.diff bet Procedure and Function.Constraints.Use of Primary key and Foreign key.some Real time example for above concepts
How to create a compound trigger?
basics of SQL, SQL performances,SSIR,SSRS,SQL Quries
WHAT IS CHECKPOINT AND WHAT ARE CONFIG OPTIONS AVAILABLE?
What is referential integrity
SQL: joins, constraints, clauses, identity column
Overview of Azure data factory and it's use.
Plsql - collections, bulk collect SQL -truncate function with dates, logical sql queries Data base modeling Performance tuning
Same questions, queries asked in each round
what are views

what is index

SQL Joins, Aggregation functions, substring, sql queries based on the interviewer's conditions, Java oops concepts, Normalisation- removing redundancy, small puzzles

What different are the Constraints used on Table Columns in SQL?

questions on join,types of join,view,unique key, some basic question query was lyk, write a query to display 3rd highest salary of employee


Difference between a view and materialized view? Can we modify a view? if any view is modifiable? Difference between PLSQL table and Varray? Have you ever used utl_file package? Write a program to bulk insert into a table using FORALL ? Find the 2nd highest salary of an employee? Difference between procedure and function


high availability concepts



Difference between truncate and delete write query to get third maximum salary. write query to get all employee belonging to sales department having salary > 20000. what is view ? what is trigger?

sql joins, constraints, normalization etc


Difference between Procedures and Functions?


WHAT ARE DIFF JOINS IN SQL? & EXPLAIN CARTISIAN JOIN.

Olap vs oltp

what is difference between union and union all?

can primary key have null value?


types of SDLC

types of SDLC

Clustered and Non-clustered indexes.

Difference between ASM and ADDR report























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
