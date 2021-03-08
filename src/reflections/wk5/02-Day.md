Read Servers with Node/Express > MongoDb Relationships and answer the following questions

What are the three types of relationships?
One to One
One to Many
Many to Many

What are the benefits of the traditional linking of relationships instead of Embedding

Linking relationships make it easier to sort; for example the comments from the blog, without having to retrieve all of the "blog" as well as the "comments". Linking has an additional benifit of being expandible without the limitaions embedding can create.


What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?

Much of the difficulty is based on the number of relationship connections objects have to each other. The thrid collection embedding way solves this problem by seperating the objects with two foriegn keys, making it easier to manage each relationship.


 https://amgorder.github.io/greglist_node/