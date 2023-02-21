# Student Database (MongoDB)

### ⚫ Find the student name who scored maximum scores in all (exam, quiz and homework)?
This query will find the student name who scored the maximum total score across all categories.

### ⚫ Find students who scored below average in the exam and pass mark is 40%?
This query will find the students who scored below the average score in the exam, and whose overall score is above the pass mark of 40%.

### ⚫ Find students who scored below pass mark and assigned them as fail, and above pass mark as pass in all the categories.
This query will classify the students who scored below the pass mark in any category as "fail", and the students who scored above the pass mark in all categories as "pass".

### ⚫ Find the total and average of the exam, quiz and homework and store them in a separate collection.
This query will calculate the total and average score for each category (exam, quiz, and homework), and store them in a separate collection.

### ⚫ Create a new collection which consists of students who scored below average and above 40% in all the categories.
This query will create a new collection consisting of the students who scored below average in all categories, but whose overall score is above 40%.

### ⚫ Create a new collection which consists of students who scored below the fail mark in all the categories.
This query will create a new collection consisting of the students who scored below the fail mark in all categories.

### ⚫ Create a new collection which consists of students who scored above pass mark in all the categories.
This query will create a new collection consisting of the students who scored above the pass mark in all categories.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------


# Telephone Directory CRUD Operation using MongoDB and Python
### This is a simple project that demonstrates how to perform CRUD operations on a telephone directory using MongoDB and Python.

## Getting Started
⚫ Clone the repository to your local machine.

⚫ Install the required Python modules by running pip install -r requirements.txt in your terminal.

⚫ Start MongoDB server by running mongod command in your terminal.

⚫ Run the app.py file to start the application.

⚫ You will be prompted to select one of the following operations:

            ▪︎ Create a new record
            
            ▪︎ Retrieve records
            
            ▪︎ Update a record
            
            ▪︎ Delete a record
            
            
⚫Follow the instructions on the screen to perform the selected operation.

## Implementation Details
### The project uses the PyMongo library to connect to the MongoDB server and perform CRUD operations on a telephone directory. Here are the key implementation details:

⚫ A MongoClient instance is created to connect to the MongoDB server.

⚫ A new database is created using attribute style on the MongoClient instance. The database is assigned to a variable named db.

⚫ A collection named telephone_directory is created in the database.

⚫ To create a new record, the insert_one() method is used to insert a document into the collection.

⚫ To retrieve records, the find() method is used to find all documents in the collection that match the specified query.

⚫ To update a record, the update_one() method is used to update the specified document with new values.

⚫ To delete a record, the delete_one() method is used to delete the specified document from the collection.

## Conclusion

#### This project demonstrates how to perform CRUD operations on a telephone directory using MongoDB and Python. You can use this as a starting point for your own projects that involve working with MongoDB in Python. If you have any questions or suggestions, feel free to reach out to me.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
