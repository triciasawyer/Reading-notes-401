# Reading notes class 4

## nosql vs sql

**What type of database is the best fit for the complex query intensive environment?**
SQL databases

**What type of database is the best fit for hierarchical data storage?**
NoSQL databases

**Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.**
SQL databases are vertically scalable in most situations. That means you can increase the load work on a single server by adding more capacities. NoSQL databases are horizontally scalable so, it can handle higher traffic via a process called sharding, which adds more servers to your NoSQL database.

## sql modeling techniques

**Among data tables, what is a one-to-many relationship and how do we “relate” them?**
When each entry in one table may be linked to one or more records in the other table, this is known as a one-to-many relationship. This is the most common type of relationship found in DBMS

**Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.**

**Explain the difference between a primary and foreign key.**
A primary key generally focuses on the uniqueness of the table. It assures the value in the specific column is unique. A foreign key is generally used to build a relationship between the two tables. The table allows only one primary key.

## sql vs nosql

**How do we treat keywords and parameters differently in SQL syntax?**

**Define normalization within the context of schemas and data.**

**Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.**
