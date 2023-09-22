# Readings: Data Modeling

## nosql vs sql

## What type of database is the best fit for the complex query intensive environment?

In a simple, query-intensive environment, a relational database (RDBMS) like PostgreSQL or MySQL is often a solid choice. RDBMS systems are known for their ability to handle complex queries efficiently and maintain data consistency. However, the suitability of the database also depends on factors like data volume and the specific requirements of your application.

## What type of database is the best fit for hierarchical data storage?

For hierarchical data storage, a Document Database is often the best fit. MongoDB, for example, is a popular choice for storing data with hierarchical structures. These databases allow you to represent and query hierarchical data efficiently using flexible, nested document structures.

## Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

**SQL Database (e.g., MySQL):**

* Think of it like a single, large bookshelf.
* When you need more space, you have to make the bookshelf taller (vertical scaling), but there's a limit to how tall it can get.
* It's like stacking more books on top of each other.

**NoSQL Database (e.g., MongoDB):**

* Imagine having lots of small bookshelves, each holding a few books.
* When you need more space, you just add more small bookshelves (horizontal scaling), and you can keep adding as many as you want.
* It's like having many bookshelves side by side, and you can keep adding more shelves easily.

In simple terms, SQL databases are like one big bookshelf, and NoSQL databases are like lots of small bookshelves that you can keep adding next to each other.

## sql modeling techniques

## Among data tables, what is a one-to-many relationship and how do we “relate” them?

1. **One Side** (e.g., Parent Table):

* Think of it as a group or category.
* It can have multiple items or records associated with it.
* For example, think of a "Classroom" table with multiple classrooms.

2. **Many Side** (e.g., Child Table):

* Think of it as individual members or details related to the group.
* Each item or record here belongs to one group from the "One Side."
* For example, think of a "Student" table where each student belongs to one classroom.

**How to Relate Them:**

* To relate them, you usually add a special column (like a number or ID) in the "Many Side" table. This column points to or tells you which group (record) it belongs to on the "One Side."
* This way, you can connect each individual item (like a student) to its corresponding group (like a classroom).

It's a bit like having a list of classes (one side) and a list of students (many side), and each student's list includes the name of the class they belong to. This helps organize and link data together in a database.

## Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.

Prior to designing your relational database, it might be useful to create a diagram of the database tables and their relationships.

## Explain the difference between a primary and foreign key.

**Primary Key:**

* It's like a special ID card for each person at a party.
* Each person's ID card is unique and helps identify them.
* It ensures that no two people have the same ID card.

**Foreign Key:**

* It's like a note on your ID card that tells you which group or table you belong to at the party.
* Many people might have the same note because they belong to the same group.
* It helps connect people to their respective groups or tables.

## sql vs nosql

## How do we treat keywords and parameters differently in SQL syntax?

**Keywords in SQL:**

* Keywords are like command words in a recipe.
* They tell the database what action to perform, like "select" to pick ingredients or "from" to specify where to find them.
* Keywords are part of the SQL language and have specific meanings.

**Parameters in SQL:**

* Parameters are like blank spaces in a recipe where you can fill in different ingredients.
* They are used to pass values into SQL queries, like putting different ingredients into a recipe.
* Parameters make queries flexible and safe, helping prevent mistakes or security issues.

## Define normalization within the context of schemas and data.

**Normalization** in databases is like tidying up your closet.

* You organize your clothes so that each item has its place.
* It reduces clutter and makes it easier to find what you need.
* Similarly, normalization organizes data to reduce messiness and make it efficient to use in a database.

## Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

**One-to-One Relationship:**

* It's like one key fitting into only one lock, no other key works.
*Each thing is uniquely connected to another thing.

**One-to-Many Relationship:**

* Imagine one thing having many connections to other things.
* Like one person being a parent to multiple children.

**Many-to-Many Relationship:**

* Think of a big group where everyone can be friends with many others.
* Lots of connections between lots of things, like in a big social network.
