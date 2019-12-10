# Databases - Exercise #1

## MySQL: Create a users database with a users table

Login to MySQL: `mysql -u root -p`

The table users should have the following fields:

* ID Primary Key which increases automatically
* email with max 20 characters. Nulls not allowed
* password with max 40 characters
* firstname and lastname with max 20 characters. Null allowed
* isAdmin, Boolean field with a default value of 0


## MongoDB: Create a users database with a users collection

Login to MongoDB: `mongo`

Due that MongoDB is schemaless you do not need to specify any columns. Create a database and a collection.

Hint: By selecting an "empty" database "users" and creating a collection "users" inside, the database will be created automatically.
