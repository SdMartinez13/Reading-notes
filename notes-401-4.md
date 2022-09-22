# Data Modeling

## Readings

[nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

1. What type of database is the best fit for the complex query intensive environment?

    * **For complex queries: SQL databases are good fit for the complex query intensive environment whereas NoSQL databases are not good fit for complex queries. On a high-level, NoSQL don’t have standard interfaces to perform complex queries, and the queries themselves in NoSQL are not as powerful as SQL query language.**

2. What type of database is the best fit for hierarchical data storage?

    * **For the type of data to be stored: SQL databases are not best fit for hierarchical data storage. But, NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data. NoSQL database are highly preferred for large data set (i.e for big data). Hbase is an example for this purpose.**

3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

    * **SQL databases are table based databases, NoSQL databases are document based databases**

[sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

1. Among data tables, what is a one-to-many relationship and how do we “relate” them?

    * **an entry in one table can be related to more than one entry in another/there can be none or one to many**

2. Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.

    * **create a diagram**

3. Explain the difference between a primary and foreign key.

    * **primary keys uniquely identify each row in a table, Foreign Key is a column or set of columns which match a primary key in another table**

## Videos

[sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

1. How do we treat keywords and parameters differently in SQL syntax?

    * **keywords are words that have a defined meaning and Parameters are used in data exchange over databases**

2. Define normalization within the context of schemas and data.

    * **Normalization is the process to eliminate data redundancy and enhance data integrity in the table**

3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

    * **one to one- one record of the first table will be linked to zero or one record of another table/one to many-A single record from one table can be linked to zero or more rows in another table/many to many-lets you relate each row in one table to many rows in another table and vice versa**

## Bookmark and Review

[sequelize api](https://sequelize.org/docs/v6/)

## Things I want to know more about

* I'd jsut like to see examples or SQL and NoSQL in use.  Building and using them in a live instruction.
