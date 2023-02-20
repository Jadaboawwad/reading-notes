## 1. Introduction to database design

        in this part we will discuss the following points

* What do we mean with terms like schema, model and entity ?
* What is postgresql and what is postgres session ?

<br/>

                           The beginning of Part One

### 1.1: What do we mean with terms like schema, model and entity ?



- Schema : we can define it by the following terms.
    - close to implementation details.
    - tells us how the entity looks in database.
    - define fields and relationships.
    - its a blueprint of entity.

- Entity : we can define it by the following terms.
    - instance of storde item in database.
    - created with schema.
    - defined by a row in a database tabel.
    - each field of the enity defined by a table column.
    - relationships between entities defined by identifires.
    - It can be one of four things [People, things, events, locations]

- Model : we can define it by the following terms.
    - abstract perspictive on schema.
    - offers conceptual framework on available models and it used as inteface to connect an application to database.
    - Usually implemented by ORM.

### 1.2: What is postgresql and what is postgres session ?

- postgresql is : an object relational database managment system.
- postgresql session is : the session consist of server process and user's client where it can be defined with the following terms.

    - server process 
        - manage the db files.
        - accept connection from client applications.
        - perform database actions.
        - server can handle multiple connections.

    - user client 
        - front end application wants to perform action.
        - could be web server or database managment tool.
        - could be on several host.
        - the communication happens throw tcp/ip protocol.
        
<br/>

    
                               The End of Part One



## 2. SQL Terminologies : 

        in this part we will discuss the following points

* What are the SQL keys ?
* Model a table defining SQL keys in ?

<br/>

                           The beginning of Part Tow

### 2.1: What are the SQL keys ?

 - Key : uniquely identifre for tabel row and it could be one or more columns.

 - Super key : 
     - set of one or more than one key
     - identify record uniquely in dataset.
     - includes fileds which contain unique values.

 - Candidate key : 
     - set of one or more than one key
     - subset of super keys 
     - identify record uniquely in dataset.
     - it can be multiple in a table.
     - includes fileds which are required.
     - All Candidate keys are super but not vers -versa.

 - Primary key : 
     - set of one or more than one key
     - identify record uniquely in dataset.
     - it can consist of one or more fields depend on how candidate key is constructed.
     - it have to be unique and not nullable.
     - the table only contains one primary key.

 - Alternate key : 
     - it is a candidate key which is not a primary key.
     - contains of set of fileds.
     - identify record uniquely in dataset.

 - Composite Key : 
     - a candidate key consist of one or more fields.

 - Unique key : 
     - combination of one or more fields.
     - Accept only one null vlaue.
     - Accept no duplicate values.

 - Foreigen key :
     - a field which is a primary key in its perent tabel but included ass filed in host tabel.
     - we can say it's as a primary key in onother table 
     - accept non unique and null.

### 2.2: Model a table defining SQL keys in ?

![SQL Keys Model](https://jehadabuawwad.github.io/reading-notes/images/backend/day-4/SQL-Keys-model.png)


<br/>

    
                               The End of Part Tow

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
