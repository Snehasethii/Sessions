# NoSQL Databases
The term NoSQL or "Not Only SQL" is typically used for non-relational databases.NoSQL databases are used for handling big data and real-time applications. NoSQL databases store relationship data also but not likewise other relational databases.

There are multiple types of NoSQL databases based on their data models like document databases, key-value databases, Column-oriented databases, and graph databases.

## Types of NoSQL Databases
### <strong>Key-Value Databases </strong> stores data as in the collection of key/value pairs. key-value pair must be unique and values can be integer, string, booleans, arrays, or any other complex data types such as JSON, BLOB(Binary Large Objects). These Key-value pairs are just like a dictionary / a map object but which is stored in a determined way and managed by the database management system. Examples of key-value databases are Redis, Riak, Oracle NoSQL.

### <strong>Operations performed on a Key-value database:

1. <em>Retrieve: </em>
A value associated with a given key can be retrieved using ``get(key)`` operation.
2. <em>Delete:</em>
A value associated with a given key can be deleted using ``delete(key)`` operation.
3. <em>Update: </em> A value associated with a given key can be updated or replaced using ``put(key,value)`` operation.

### <strong>Document Databases</strong> stores data similar to key-value database management system but in document database management system values contains structured or semi-structured data. This structured/ semi-structured data is called a document and the document can be as in JSON or XML format. Document management system uses powerful queries and a variety of data types it used for general purpose. Document databases are used for blogging platforms, real-time analytics, and e-commerce applications. Examples of Document databases are MongoDB, CouchDB, etc.

``Student.details()
{
   _id= "12fie4",
   NAME="harry potter",
   ADD="Hogwarts"
}``

``{
   _id= "12fie5",
   NAME="Hermione",
   ADD="Hogwarts"
}``

 ><em>As shown in the above code the data is stored in JSON format. Document oriented database stores several collections of information. Here the record for id 12fie4 is a document that is in JSON format.</em>

### Advantages:
1. These databases are easier to write and read than traditional SQL databases.
2. It provides the facility of scaling out large data horizontally. So users can increase the database without acquiring any hardware.
3. It uses a flexible schema that can accommodate different types of documents.
 



### <strong>Column-oriented databases.</strong> stores data in cells grouped in columns of data rather than as rows of data. It uses the concept of keyspace which contains column families that contain rows and each row contains columns in which data is stored. In the column-oriented database, the primary key is data mapped from rows while in a row-oriented database primary key is a row, in order to retrieve data you will get full row data but in the column-oriented database you can directly access that particular column data.

### <strong>Graph Databases </strong> organizes data in the form of a <strong><em>graph</em></strong>. A graph database contains a collection of edges and nodes. Nodes store the information about entities like things, places, and people, and edges stores the information about the relationship between two entities. Graph databases allow us to apply graph theory to our data in an efficient manner like for finding minimal routes between nodes. Examples of Graph databases are Neo4j,OrientDB,ArangoDB.Graph databases are used for solving Many to Many problems or where the relationship between entities is more important.

## Advantages of NoSQL over SQL
1. Easy to insert or update to Schemas.
2. Handle large data volumes at high speed with the horizontally scale-out feature.
3. Store structured, unstructured, or semi-structured data.

### Resources
https://www.mongodb.com/nosql-explained
https://www.markdownguide.org/basic-syntax/#code
