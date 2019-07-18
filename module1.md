# MongoDB
It is based on javascript and uses Mozilla's SpiderMonkey Javascript engine.

__*There are two common type of database present :*__
- __Relational Database OR SQL Database__

    - In SQL Database data is stored in different tables and those tables have different schema.
      data stored in the table have relations such as one to one ,one to many and many to one or many to many.
      And in order to retrive some data we perfom join operations/requests that combines data from different table.
    - __Examples :__
        -     MySQl.
        -     Oracal Database.

![](images/s1.png)
    

- __Document Database OR NoSQl Databse__
    - In this the data is stored in different documents and each document is independent from other.
      And it is not mandatory for documents to have same schema for the database.
      for example some documents in database may have field called `marks` but other documents in the database may not have same
      field.
      All information related to the document is stored in one document,in one place.
      No need to use join operations. And the documents in database can be edited independent from others you can insert
      new documents and delete documents and so on.
     - __Examples :__
        -     NOSQl.
        -     MongoDB.
    
![](images/s2.png)

## MongoDB Structure

Each MongoDB database consists of databases. There are default databases that are created after

each installation of the MongoDB. And they are called for example admin and local. Each database consists of

the collections and each collection consists of the documents.

Usually documents are grouped into the same collection by common fields.

Let's suppose that you want to create e-commerce web application. And you'll create a database called "e-commerce store".

And you will probably create such collections as "products", "productCategories", "shoppingCart",

"customers" and so on.

Again schema is flexible and it is not mandatory to have same set of fields in the documents in the same collection.

That is the structure of each MongoDB database.


