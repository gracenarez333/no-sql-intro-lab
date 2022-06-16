![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)

# NoSQL Research Lab

## Explainer

Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

## Questions:

1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?

-The term noSQL is increasingly used in big data storage management and real-time web applications, and the term non-relational database is used synonymously.

2. What are some of the common arguments for using a non-relational versus a relational db?

-Relational databases are also the best choice if relationships between entities are important, if the data you are storing needs to be flexible in terms of shape or size, or if it needs to be open to change in future, then a non-relational database is the answer. Non-relational databases offer higher performance and availability.

3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db? 

-Relational databases store data in rows and columns like a spreadsheet while non-relational databases store data don't.

4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?

-MongoDB stores data in JSON format with key and value pairs for each entity whereas SQL Databases stores data as a record in a row of the table.

5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. 

-MongoDB stores data objects in collections and documents instead of the tables and rows used in traditional relational databases, these are made unique for users by using key/value pairs.

6. What is an example situation where a Mongo database makes sense versus a relational db?

-They are more suitable for unstructured big data. Working w/large amount of unstructured/semi-structured data, need the database to scale horizontally, streamline development & avoid overhead, doesn’t require high level of data integrity.

7. What are the benefits of SQL databases? NoSQL Databases?

-If you’re creating a project where the data is predictable, in terms of structure, size, and frequency of access, relational databases are still the best choice. Modern NoSQL databases have been designed for the cloud, making them naturally good for horizontal scaling where a lot of smaller servers can be spun up to handle increased load.

8. Explain the differences between ACID and BASE models.

-The CAP theorem states that it is impossible to achieve both consistency and availability in a partition tolerant distributed system (i.e., a system which continues to work in cases of temporary communication breakdowns). The fundamental difference between ACID and BASE database models is the way they deal with this limitation. The BASE model provides high availability.

9.  What should you consider when deciding between using a relational database or a non-relational database for your project?

-Relational databases store data in rows and columns like a spreadsheet while non-relational databases store data don’t, using a storage model (one of four) that is best suited for the type of data it’s storing. Things to consider; What type of data will you be analyzing? How much data are you dealing with? What kind of resources can you devote to the setup and maintenance of your database? Do you need real-time data?


## Visual Comparisons

### Structure

![](https://media.git.generalassemb.ly/user/16103/files/65db7f00-afd5-11ea-926a-e51b2fd2be08)

### Relationships

![](https://media.git.generalassemb.ly/user/16103/files/5eb47100-afd5-11ea-8cae-0a65c924be4b)

### Use Cases

![](https://media.git.generalassemb.ly/user/16103/files/7f7cc680-afd5-11ea-82c8-10ed74ee2222)

## Additional Readings

Pick an additional reading to go through with a classmate. Reflect on how the
article changes the discussion. What have you learned?

  _**Note:** You do not have to read about the different types of SQL and NoSQL. We will use PostgreSQL and MongoDB in this course._
- [ACID vs. BASE Explained](https://neo4j.com/blog/acid-vs-base-consistency-models-explained/)
- [PostgreSQL Use Cases](https://www.cybertec-postgresql.com/en/postgresql-overview/solutions-who-uses-postgresql/)
- [MongoDB Use Cases](https://www.mongodb.com/use-cases)
- [What the heck are you actually using NoSQL for?](http://highscalability.com/blog/2010/12/6/what-the-heck-are-you-actually-using-nosql-for.html)
- [A co-Relational Model of Data for Large Shared Data Banks](http://queue.acm.org/detail.cfm?id=1961297&repost)
- [A brief history of databases](http://avant.org/media/history-of-databases)
- [NoSQL Databases: An Overview | ThoughtWorks](http://www.thoughtworks.com/insights/blog/nosql-databases-overview)
- [When to choose CouchDB vs RDBMS?](http://stackoverflow.com/a/2731207/402618)
- [CAP Twelve Years Later: How the "Rules" Have Changed](http://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed)
