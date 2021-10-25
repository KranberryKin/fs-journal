**What are the three categories of data types? How are they different?**

There is a int, string and enum as the 3 data types in C#.

**What are the Value-type data types? What differences do you notice from JavaScript?**

int is Number in javascript. String is the same in c# and js. And Enum is the same in js and c#.

**In your own words how do Reference types get stored in memory? How does this differ from Value types?**

When storing memory into MySQL, there is no bool, there is only tinyint where it's a 0 or 1. instead of string there are VARCHAR in the strage database. You'd have to manage how big you'd want this data

**What is a List in C#?**

A List in c# is simular to receiving an array on objects in javascript.

**What List methods seem like you might use them often? Why?**

I use List methods often to retreive all of one data from table. 

**How would you retrieve an item from a list? What method could you use?**

There is a function you can run with the sql statement where you can iterate over each item in the list. potentially populating the objects as you go.

**In a SQL table, what is the difference between information in a row and information in a column?**

When there is an error for the row, it itself invloves the entire object. unless is is an error with the column, then it's a property on the object which is missing. 

**Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.**

CREATE TABLE characters IF NOT EXISTS(
  id int NOT NULL AUTO_INCREMENT PRIMARY KEY COMMENT 'primary key',
  name VARCHAR(255) NOT NULL COMMENT 'name',
  age VARCHAR(255) NOT NULL COMMENT 'age',
  description VARCHAR(255) NOT NULL COMMENT "description"
)

**What is the difference between the following statements.**



**What is an Enum, and what are some use cases for them?**

An Enum is a Specifide string or value that can be set for a property. like if it is a model for a car, there is only sslect models avaliable. 

**How can you modify an Enum?**

An Enum normally has a select amount of options to choose from, So you can see what properties are acceptable and change it to one taht is optional.

**How have you used Enums in your afternoon lab projects this far?(if you have not yet, give an example of how you could)**

