## 1. Introduction to Object relational mapping

        in this part we will discuss the following points

- What is ORM ?
- How the model can be defined in sequlize ?
- How the model can be renamed in sequlize ?
- What is the model syncronization ?
- What are the field options that can be set in sequelize

<br/>

                           The beginning of Part One

### 1.1: What is ORM ?

- The ORM : the idea of being able to write queries using object orinted paradigm of any language.
- Most popular ORM service are : Knex.js and Sequelize.js
- it used for tranforming information from database to javascript application without SQL statments.
- mimic the actual databse so a developer can operate with a programming language.

### 1.2: How the model can be defined in sequlize ?

- the model in sequlize is abstact perspictive of table in database, so it can be a class in sequlize.
- can be defined erither by sequlize define method or by extending Model class.

### 1.3: How the model can be renamed in sequlize ?

- does'nt have to be the name of the table.
- it's a sigular name.
- tables have plurarl names.

### 1.4: What is the model syncronization ?

- a defined model telss sequlize few things about the table in database.
- checking if the table is existed then if it existed there is another check for differnce in construction and finally there is syncronization process start.
- It performs automatically SQL querise to database.
- It has many types :
  - Sync with creating table if it not exists : with Model.sync()
  - Sync with droping the table first : with Model.sync({force : true})
  - Sync with creating table and make it mathced : with Model.sync({alter : true})
  - Sync all models at ounce : with Sequlize.sync({force :true})
- All sync process must be in staging and not production mode.


### 1.5: What are the field options that can be set in sequelize ?

 - Allow Null : if the value of this filed is not provided it set to null.
 - Type : set the value of a type to string, number or boolean.
 - Unique : does not allow multiple values to be defined.
 - Primary Key : set the field to be a primary key.
 - Auto Increment : create auto increment values for the filed for each entity item to be added to the table.
 - Field : a custom column name to be set.
 - References : reference to antother tabele where we set the {model : target model , key : target key }.
 - Comment : a briefe description of the column content.


<br/>

                               The End of Part One


# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)

