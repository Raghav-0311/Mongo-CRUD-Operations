# MongoDB CRUD Operations.

## What is MongoDB ?
MongoDB is a popular **``open-source``**, **``NoSQL``** **(Not Only Structured Query Language)** **``database management system (DBMS)``** that provides **high performance**, **scalability**, and **flexibility** for handling large amount of unstructured or semi-structured data.
<br>
MongoDB is classified as a NoSQL database because it does not rely on the traditional relational database model with tables, rows, and columns. instead, it uses a document model, where data is stored in flexible, self-contained documents.
<br>
In MongoDB data is stored in a **``BSON``** **(Binary JavaScript Object Notation)** format.
<br>
BSON documents can contain a variety of datatypes, incuding strings, numbers, boolean values, arrays and even nested documents.

---

![MongoDB](https://media.geeksforgeeks.org/wp-content/uploads/20200219180521/MongoDB-database-colection.png)

---

### Collection :-
- Collection is a group of MongoDB documents.
- It is equivalent to RDBMS Table.
- A collection exists within a single database.
- Collections do not enforce a schema.
- Documents within a collection can have different fields.
- Typically, all documents in a collection are of similar or related purpose.

---

### Document :-
- A document is a set of key-value pairs.
- Documents have dynamic schema.
- Dynamic Schema means that documents in the same collection do not need to have the same set of fields or structure, and common fields in a collection's documents may hold different types of data.

---

### Field :-
- Fields exists within documents.
- A document is a self-contained unit of data that consists of a set of key-value pairs.
- Each key represents a field, and its corresponding value represents the data stored in that field.

---

![MongoDB-CDF](https://studio3t.com/wp-content/uploads/2022/04/hierachy.png)

---
## NoSQL (MongoDB) **``VS``** SQL (MySQL / RDBMS)

---

![MongoDB-CDF](https://jutesenthil.files.wordpress.com/2018/03/dif_be_mongo_mysql.png)

---

## Key Features of MongoDB :-

---
- **``High Scalability``** - MongoDB can horizontally scale across multiple servers and handle large amount of data by **Sharding** (a process of distributing data across multiple machines).
- **``Flexible Data Model``** - With its document-oriented approach, MongoDB allows developers to work with flexible schemas. Documents within a collection can have varying structures, allowing for easy modifications and evolving data modles.
- **``Rich Query Language``** - MongoDB provides a powerful query language that supports a wide range of operations, including filtering, sorting, aggregation, and geospatial queries. It also supports indexing for optimizing query performance.
- **``High Availability``** - MongoDB offers built-in replication and automatic failover to ensure data availability and fault tolerance. It can maintain multiple copies of data across different servers, enabling continuous operations even in the event of hardware failures.
- **``Distributed Transaction``** - Starting from version 4.0, MongoDB introduced multi-document ACID transections, allowing developers to perform atomic, consistent, isolated, and durable operations across multiple documents and collections.
- **``Comprehensive Ecosystem``** - MongoDB provides a rich ecosystem of tools integrations, including drivers for various programming languages, connectors for popular data integration platforms, and support for cloud-based deployments.

---