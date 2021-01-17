# Day 22
__01/12/2021__

## what are the three types of relationships?

The three types of relationships in mongoDb are 'one to one', 'one to many', and 'many to many'. One to one relationships are the least common of the three, but still get used frequently. They are typically like an author and the authors address. The author only has one address, and the address only has one author. One to many relationships are like a Blog post, where there is one Post, with many many comments but each comment only ever has one post that it is associated with. Then there is the many to many relationsips. These are the most complicated of the three, and I am not sure I completley understand them yet, however they are similar to how genres and books work. One book can have many genres, and one genre can have many books.


## What are the benefits of the traditional LINKING of relationships instead of EMBEDDING?

The Linking of relationships has one major benefit over Embedding them. Linking the data instead of embedding the data helps keep the profile of the information low so that it does not take up as much space as if it was all embedded. It is also easier to return a group of something to a page.


## What are some of the challenges faced when decidinhg how to manage a many-to-many relationship that ultimately drive your decision on how to create it?

The main challenge that I see is studying the data of the relationship and determining how the many to many relationship works. Is it jsut an endless sea of data? Or is there one data set or property that shows up less frequently than another? There are three main strategies when it comes to tackling a many to many relationship: two way embedding, one way embedding and collection embedding. 


## Afternoon Project Link:
https://steffenlarson.github.io/winter20-gregslist-server/


## Reading: Servers with Node/Express => MongoDb Relationships