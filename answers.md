Components of a DBMS (Database Management System)

Database Engine:

Responsible for storing, retrieving, and updating data in the database.
Ensures data consistency and integrity during transactions.

Data Definition Subsystem:

Handles defining and modifying the database schema, including tables, indexes, and constraints.
Uses DDL (Data Definition Language) commands like CREATE, ALTER, and DROP.

Data Manipulation Subsystem:

Provides tools to insert, update, delete, and query data.
Uses DML (Data Manipulation Language) commands like SELECT, INSERT, UPDATE, and DELETE.

Data Security and Integrity Subsystem:

It ensures user authentication, access control, and encryption of data.
Constraints such as primary keys and foreign keys ensure the accuracy and consistency of data.
Data Recovery and Backup Subsystem:

It performs backup and recovery processes in order to prevent data from being lost or corrupted.

User Access Tools:

User interfaces made up of query tools, report generators, and dashboards interface with the database. What is a Relational Database?
In a relational database, data is stored in tables (relations) made up of rows and columns. It follows a structured schema with relationships established amongst the tables using keys to ensure consistency.

Examples of Relational Databases:
MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server
Classifications of SQL

Data Definition Language (DDL):

Defines the structure of the database.
Examples: CREATE, ALTER, DROP.
Data Manipulation Language (DML):

Handles the manipulation of data within tables.
Examples: SELECT, INSERT, UPDATE, DELETE.
Data Control Language (DCL):

Controls the permissions and access control.
Examples: GRANT, REVOKE.
Differences Between Primary Key and Foreign Key
Primary Key	Foreign Key
Unique identification of each record in a table.
Relationship between two tables can be established.
Cannot hold NULL values.
NULL values can be held depending on permission.
Defined in one single table.
It refers to another table's primary key.
What is an Entity-Relationship Diagram?
An ERD is a diagrammatic way of representing the entities, such as tables, concerned with a database and the relationships among them. It helps at the time of designing the database because it showcases how data is interrelated on aspects of primary keys, foreign keys, attributes, and cardinality.

Advantages of Relational Databases
Data Integrity: Ensures consistency and accuracy of data.
Ease of Use: SQL is used for querying and managing data.
Scalability: Handles datasets that are large with ease.
Data Security: Allows authentication and authorization.
Normalization: Discards data redundancy and increases efficiency.
Four Kinds of Data Types Used in Tables
Integer: It stores whole numbers, example - INT, BIGINT.
Character/String: Stores text, for example - CHAR, VARCHAR, TEXT.
Date/Time: It stores dates and times, for example - DATE, DATETIME.
Floating Point: It stores decimal numbers, example - FLOAT, DOUBLE.
Objective of Database Management System (DBMS)
Data Storage and Retrieval: To store and retrieve data efficiently.
Data Integrity and Security: Accuracy in data and disallow unauthorized access.
Data Sharing: Multiple users and applications share the same data simultaneously. Backup and Recovery: Protection against loss of data and restoration of data. Data Abstraction: The interaction with complex data structures is simplified by using layers of abstraction.