# MongoDB and Mongoose

## NoSQL vs SQL

**Differences between SQL and NoSQL databases:**

| SQL | NoSQL |
|-----|-------|
| Relational Databases | Non-relational or distributed databases |
| table-based | document-based |
| predefined schema | dynamic schema/unstructured |
| Vertically scalable | Horizontally scalable |
| Uses SQL to read/manipulate data | Use queries on collections of documents |

1. **What kind of data is a good fit for an SQL database?**

    Data that requires complex queries against it.

2. **Give a real world example.**

    MySQL

3. **What kind of data is a good fit a NoSQL database?**

    Data that is not going to be used for complex queries.

4. **Give a real world example.**

    MongoDB

5. **Which type of database is best for hierarchical data storage?**

    A NoSQL database is better for hierarchical data storage because it uses key-value pairs.

6. **Which type of database is best for scalability?**

    SQL databases usually scale vertically, by adding more capacity to the server the database is on, whereas NoSQL databases scale horizontally, by adding more servers the database. This would be situation dependent but a NoSQL database is usually best to scale.

SQL vs NoSQL (Video)

1. **What does SQL stand for?**

    Structured Query Language

2. **What is a relational database?**

    A relational database that assumes data is stored in a particular format and supports SQL.

3. **What type of structure does a relational database work with?**

    A relational database structures data into tables. In these tables, the columns are the fields (attributes) of the data and the rows are the records (item) of the data.

4. **What is a ‘schema’?**

    A schema is a set of requirements defined by fields which specify which and how data is stored in a database. All records in a SQL database have to match the schema.

5. **What is a NoSQL database?**

    A database that does not support SQL.

6. **How does it work?**

    It stores data in documents which are grouped together in collections.

7. **What is inside of a MongoDB database?**

    MongoDB is a NoSQL database and is made up of documents and collections.

8. **Which is more flexible - SQL or MongoDB? and why.**

    A NoSQL database is more flexible because you are not forced to follow a schema for each record stored.

9. **What is the disadvantage of a NoSQL database?**

    Because NoSQL databases does not use relations between collections, NoSQL databases can result in duplicate data between collections.

## Things I want to know more about

- Why can't SQL databases be scaled horizontally?
- How to know which database type to use

## References

- [The Geek Stuff: SQL vs NoSQL Database Differences Explained with few Example DB](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)
- [Academind: SQL vs NoSQL or MySQL vs MongoDB](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)
