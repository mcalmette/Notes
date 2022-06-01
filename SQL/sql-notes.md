# What is SQL?

Structured Query Language is a standard language for relational databae management systems

Used to query, insert, update, and modify data

Statements are made up of descriptive words.
SQL is a non-procedural language:
- Cannot write complete applications
- Simple, but powerful


### How is it used?

- Write Data, add data to a table
- Update Data, insert new data
- Read Data


DBA - Database Administrator
- manages/governs entire database
- gives permissions to users
- determines access to data
- manages and creates tables
- uses SQL to query and retrieve data


How do data scientists use SQL?
- retrieve data
- may create their own table or test environment
- combine multiple sources together
- write complex queries for analysis


Each database management system has its own dialect.
SQL can translate - you will tweak based on the dialect your DBMS uses

Exs: MySQL, SQLite, PostgreSQL, Apache Open Office Base, Sybase ASE, Microsoft SQL Server.


## Data Models - Thinking about your Data

Think before you code - What is the problem you are trying to solve?

Database - a container to store the data
Tables - a structured list of data or a specific type

What is Data Modeling?
- organize and structures information into multiple, related tables
- can represent a business process or show relationships between business processes
- should closely represent real world


Types of Data Models
- Models for prediction built by data scientists
- Data model as data tables represented and organized in a database


Benefits of relational data models
- allows you to retrieve and update data
- allows you to easily write queries against is
- simplifies the connections between the data
- allows you to write data to it

NoSQL - Not Only SQL
- A mechanism for storage and retrieval of unstructured data modeled by means other than tabular relations in relational databases



### Relational vs. Transactional Data Models

Relational Model - database design that shows the relationships between the different tables, used to optimize data. Allows for easy querying and data manipulation

Transactional Model - more operational database, used to store specific info and may not be good for analysis. This data may be needed to move over to a relational database



## Data Model Building Blocks
- Entity: Person, place, thing, din
- Attribute: characteristic of an entity
- Relationship: describes association among entities


One-to-many: customer to invoices
Many-to-many: student to classes
One-to-one: manager to store


ER Model / Diagrams
- show relationships
- business process
- visual
- show links(primary keys)


Primary Key - a column whose values uniquely identify every row in a table

Foreign Key - one or more columns that can be used together to identify a singe row in a table


Diagrams: 
Chen Notation, Crow's Foot Notation, UML Class Diagram Notation 


## Retrieving Data with SELECT
Need to specify two prices of information to use a SELECT statement: what you want and where you want to select it from

















