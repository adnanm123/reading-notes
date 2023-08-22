# nosql vs sql

## Fill in the chart below with five differences between SQL and NoSQL databases:

| SQL                                                                                                                 | NoSQL                                                                                                                                  |
|---------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| SQL databases are primarily called as Relational Databases (RDBMS)                                                  | NoSQL database are primarily called as non-relational or distributed database                                                          |
| SQL databases are table based databases                                                                             | NoSQL databases are document based, key-value pairs, graph databases or wide-column stores                                             |
| SQL databases have predefined schema                                                                                | NoSQL databases have dynamic schema for unstructured data                                                                              |
| SQL databases uses SQL ( structured query language ) for defining and manipulating the data, which is very powerful | NoSQL database, queries are focused on collection of documents. Sometimes it is also called as UnQL (Unstructured Query Language)      |
| SQL databases are not best fit for hierarchical data storage                                                        | NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data |

## What kind of data is a good fit for an SQL database?

SQL databases are good for organized data like tables with rows and columns. Examples include customer info, orders, time-stamped data, and business records. They're not great for unorganized data like images or text documents.

## Give a real world example of a SQL database

Imagine a library's computer system. An SQL database is good for keeping track of books, borrowers, and loans. It's like having organized lists for books, people, and when they borrowed items. But if you wanted to store random scribbles or drawings, that wouldn't fit well in this type of database.

## What kind of data is a good fit a NoSQL database?

NoSQL databases are good for messy data like social media posts, images, logs, or data that doesn't fit neatly into tables. If you have lots of different types of information, changing data formats, or need to handle big data, NoSQL databases are a good choice. They're like a big storage box for all kinds of stuff, while SQL databases are like organized shelves.

## Give a real world example of a NoSQL database

Imagine you're running a website where people share photos, videos, and comments. A NoSQL database would be a good choice because it can handle all these different types of content without needing strict rules. It's like having a big bag to throw in your stuff, instead of organizing everything on shelves. This way, as more people join and share, the database can still keep up without getting messy.

## Which type of database is best for hierarchical data storage?

A NoSQL database, specifically a document-oriented database or a graph database, is best suited for hierarchical data storage. These databases are designed to handle data with complex relationships and structures, making them ideal for scenarios where data is organized in a hierarchy, such as in trees or graphs.

## Which type of database is best for scalability?

NoSQL databases are best for scaling up when you need to handle lots of data and many users. They're like adding more lanes to a highway to fit more cars. These databases are built to handle big loads and keep your app running smoothly as it gets busier.

## sql vs nosql (Video)

## What does SQL stand for?

SQL stands for "Structured Query Language." It's a special language used to manage and interact with relational databases.

## What is a relational database?

A relational database is a type of database that organizes data into structured tables with rows and columns. These tables are related to each other based on common fields, allowing you to store and retrieve data in a structured and efficient manner. The relationships between tables enable you to query and manipulate data using the principles of relational algebra.

## What type of structure does a relational database work with?

A relational database works with a structured format called tables. Each table consists of rows and columns. Rows represent individual records, while columns represent different attributes or properties of those records. The structured format allows you to store and organize data in a consistent and organized way, making it easy to retrieve and manipulate information.

## What is a ‘schema’?

A schema in a database is like a blueprint or plan that defines how the data should be structured and organized. It specifies the tables, columns, data types, relationships, and constraints for the database. It's like creating a template for how information should be stored and related to each other, ensuring consistency and helping to manage the data effectively.

## What is a NoSQL database?

A NoSQL database is a flexible way to store lots of different types of data. It doesn't need a fixed structure, so it's like a digital box where you can put all sorts of things without worrying too much about how they're organized.

## How does it work?

A NoSQL database stores data in a flexible way, like putting items in a bag without worrying about their shape. It can handle different types of data easily, making it like a versatile storage box for various things.

## What is inside of a MongoDB database?

Inside a MongoDB database, you'll find collections of documents. Each document is like a record and can have different fields or attributes. These documents are organized in collections, which are similar to tables in relational databases. MongoDB is a type of NoSQL database, and its flexibility allows you to store data in a more natural and dynamic way, making it suitable for various applications and data structures.

## Which is more flexible - SQL or MongoDB? and why

MongoDB is more flexible because it's like a digital box where you can put all sorts of items without worrying about their shape. It doesn't need a fixed plan, unlike SQL which is more like a grid where items must fit into specific cells.

## What is the disadvantage of a NoSQL database?

A downside of NoSQL databases is that they can struggle with complex queries and relationships between data. Also, some of them might not be as good at keeping data super safe and reliable as traditional databases. So, while they're flexible, they might not fit every situation perfectly.
