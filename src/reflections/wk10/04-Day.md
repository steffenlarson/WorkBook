# Day 49
__02/18/2021__

## In a SQL table, what is the difference between information in a row and information in a column?

The information in a row inside of a SQL table is a whole 'object'. It is all of the specific data that is tied to a single instance of whatever the table is keeping track of. The columns specify what all of the properties are for every single instance of that type.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int Id.

CREATE TABLE characters(
  name VARCHAR(255) NOT NULL,
  age VARCHAR(255),
  description VARCHAR(255),
  Id int NOT NULL AUTO INCREMENTING
);

This is how you would create that table.


## What is the difference between the following statement:
##   DELETE FROM table_name;
##   DROP TABLE table_name;

DELETE FROM will target a specific part or property of a table. The DROP TABLE will delete the whole table. DO NOT DELETE THE WHOLE TABLE. Clear it instead.


## Afternoon Project Link:

https://steffenlarson.github.io/burgershop/


## Reading: Dotnet WebAPI's: Welcome to SQL