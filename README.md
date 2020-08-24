# SQL

> Click :star: if you like the project. Pull Request are highly appreciated.

### Table of Contents

| No. | Questions |
| --- | --------- |
|1  | [What is a Database?](#why-laravel) |
|2  | [What is a Relational Database?](#php-inheritance) |
|3  | [RDBMS](#what-is-dependency-manager) |
|4  | [Introduction to SQL](#what-is-api-php) |
|5  | [Naming Conventions](#what-is-channels-php) |
|6  | [Data Integrity](#what-is-console-php) |
|7  | [Database Terms](#what-is-controller) |
|8  | [Atomic Values](#what-are-views) |
|9  | [Relationships](#what-is-a-model) |
|10  | [One-to-One Relationships](#what-is-request-response) |
|11  | [One-to-Many Relationships](#what-are-migrations) |
|12  | [Many-to-Many Relationships](#what-are-seeders) |
|13  | [Designing One-to-One Relationships](#what-are-service-providers) |
|14  | [Designing One-to-Many Relationships](#what-is-middleware) |
|15 | [Parent Tables and Child Tables](#what-is-orm) |
|16 | [Designing Many-to-Many Relationships](#what-is-eloquent) |
|17 | [Introduction to Keys](#what-is-query-builder)
|18 | [Primary Key Index](#what-are-facades) |
|19 | [Look up Table](#what-is-repository-pattern) |
|20 | [Superkey and Candidate Key](#What-is-Authentication-using-Passport-CSRF-XSRF) |
|21 | [Primary Key and Alternate Key](#what-is-unit-testing) |
|22 | [Surrogate Key and Natural Key](#what-is-caching) |
|23 | [Should I use Surrogate Keys or Natural Keys?](#how-to-setup-emails) |
|24 | [Foreign Key](#what-are-queues) |
|25 | [NOT NULL Foreign Key](#what-are-jobs)
|26 | [Foreign Key Constraints](#what-are-advanced-eloquent-and-query-builder) |
|27 | [Simple Key, Composite Key, Compound Key](#which-is-error-management) |
|28 | [Review and Key Points....HA GET IT? KEY points](#how-to-create-an-api) |
|29 | [Introduction to Entity Relationship Modeling](#what-are-events) |
|30 | [Cardinality](#what-are-listeners) |
|31 | [Modality](#what-are-payments-and-cashier) |
|32 | [Introduction to Database Normalization](#what-is-test-driven-development) |
|33 | [1NF (First Normal Form of Database Normalization)](#what-is-package-development) |
|34 | [2NF (Second Normal Form of Database Normalization)](#what-are-laravel-scout-search-and-algolia) |
|35 | [3NF (Third Normal Form of Database Normalization)](#what-is-socialite-auth) |
|36 | [Indexes (Clustered, Nonclustered, Composite Index)](#what-is-vue-js) |
|37 | [Data Types](#How-to-connect-Laravel-with-other-SQL-databases) |
|38 | [Introduction to Joins](#How-to-connect-Laravel-with-non-SQL-databases) |
|39 | [Inner Join](#what-is-lumen) |
|40 | [Inner Join on 3 Tables](#what-is-redis) |
|41 | [Introduction to Outer Joins](#what-is-memcache) |
|42 | [Right Outer Join](#What-is-Horizontal-scaling) |
|43 | [JOIN with NOT NULL Columns](#What-is-Vertical-scaling) |
|44 | [Outer Join Across 3 Tables](#What--Single-Page-Application-in-Laravel) |
|45 | [Alias](#What-are-Microservices-in-Laravel) |
|46 | [ Self Join](#what-is-CSRF-and-JWT-token) |

1. ### What are the pros of using Laravel?

 A. Most demanded PHP framework.
 B. Great documentation.
 C. MVC based.
 D. ORM for DB.
 E. Blade templating engine


 **[⬆ Back to Top](#table-of-contents)**
    
2. ### What is inheritance in PHP?

When a class inherits another class. It uses extends.
 ```
 <!DOCTYPE html>
 <html>
 <body>

 <?php
 class Fruit {
   public $name;
   public $color;
   public function __construct($name, $color) {
     $this->name = $name;
     $this->color = $color; 
   }
   public function intro() {
     echo "The fruit is {$this->name} and the color is {$this->color}."; 
   }
 }

 // Strawberry is inherited from Fruit
 class Strawberry extends Fruit {
   public function message() {
     echo "Am I a fruit or a berry? "; 
   }
 }

 $strawberry = new Strawberry("Strawberry", "red");
 $strawberry->message();
 $strawberry->intro();
 ?>

 </body>
 </html>
 ```
  **[⬆ Back to Top](#table-of-contents)**
    
