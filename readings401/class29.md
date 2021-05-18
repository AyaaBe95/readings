# Rooms

## Save data in a local database using Room
- It persistences library provides an abstraction layer over SQLite to allow fluent database access while harnessing the full power of SQLite. 

### benefits of room:
- Compile-time verification of SQL queries.
- Convenience annotations that minimize repetitive and error-prone boilerplate code.
- Streamlined database migration paths.


![scanner](https://gorillalogic.com/wp-content/uploads/2019/12/RoomDB_Transparent.png)

### Primary components:
-  database class
-  Data entities
-  Data access objects (DAOs)

## Defining data using Room entities
-  Entities  represent the objects that you want to store.
-  Each entity corresponds to a table in the associated Room database.
-  Each instance of an entity represents a row of data in the corresponding table.

### Anatomy of an entity:
- It is annotated with @Entity
-  A Room entity includes fields for each column in the corresponding table in the database.

## Define relationships between objects:
- A one-to-one relationship between two entities is a relationship where each instance of the parent entity corresponds to exactly one instance of the child entity, and vice-versa.
- A one-to-many relationship between two entities is a relationship where each instance of the parent entity corresponds to zero or more instances of the child entity.
- A many-to-many relationship between two entities is a relationship where each instance of the parent entity corresponds to zero or more instances of the child entity, and vice-versa.

## Accessing data using Room DAOs:
- you interact with the stored data by defining data access objects, or DAOs. 
- Each DAO includes methods that offer abstract access to  app's database. 
- At compile time, Room automatically generates implementations of the DAOs that you define.
