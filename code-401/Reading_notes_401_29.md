# Room 

## A) Save data in a local database using Room

### The main reason to use room is to save data localy, room library provides an abstraction layer over SQLite to allow fluent database access while harnessing the full power of SQLite.

### Room provides the following benefits:

* #### Compile-time verification of SQL queries.

* #### Convenience annotations that minimize repetitive and error-prone boilerplate code.

* #### Streamlined database migration paths.

#### So with this benefit we can use Room instead of using the SQLite APIs directly.

### Primary components there are three major components in Room:

* #### The database class that holds the database.

* #### Data entities that represent tables in your app's database.

* #### Data access objects (DAOs) that provide  update, insert, and delete methods in the database.

## B) Defining data using Room entities

### When we add `entity` annotation  before the class we mean by that we need to add this class in our database as a table and each instance of an entity represents a row of data in the corresponding table.

* #### Anatomy of an entity : when we  define each Room entity as a class that is annotated with @Entity. A Room entity includes fields for each column in the corresponding table in the database, including one or more columns that comprise the primary key.

* ####  Define a primary key : each entity must have primary key that uniquely identifies each row in the corresponding database table.

* #### Ignore fields: by defult room create column for each field in the entity if we want to ignore field we need to add `ignore` annotation.

## C) Define relationships between objects

### We are using relations to do a reference between tabels 

* ####  Create embedded objects : In order to represent an object that you'd like to decompose into its subfields within a table we need to use  `Embedded` annotation

* #### Define relationships between tabels : 1. One-to-One relation 2. One-to-many relation 3. many-to-many relation  4. nested  relation.

## D) Accessing data using Room DAOs

* #### Anatomy of a DAO : first to start using DAO you need to add `Dao` annotation  for the interface than you can start use DAO methods and there is two method for DAO  which is :

    ##### 1.Convenience methods that let you insert, update, and delete rows in your database without writing any SQL code.

    ##### 2. Query methods that let you write your own SQL query to interact with the database.