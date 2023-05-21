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
Keywords are reserved words that have predefined meanings in SQL. They are part of the SQL language and serve specific purposes within SQL statements. SQL keywords include SELECT, FROM, WHERE, INSERT, UPDATE, DELETE, JOIN, and GROUP BY. Parameters, also known as placeholders or bind variables, are used to pass dynamic values into SQL statements. In most SQL database systems, parameters are represented by placeholders, often using a question mark (?) or a named parameter syntax. So, the main distinction between keywords and parameters is that keywords are predefined language elements that define the structure and behavior of the SQL statement, whereas parameters are placeholders for values that can be substituted at runtime to make the query more flexible and reusable.

**Define normalization within the context of schemas and data.**
Columns are assigned to tables in such a way that each business fact is stored only once, or in other words, a table should not contain duplicate data.

**Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.**
One-to-one: A record in one table is related to one record in another table. One-to-many: A record in one table is related to many records in another table. Many-to-many: Multiple records in one table are related to multiple records in another table.
