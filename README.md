MongoDB CRUD Operations

📌 Project Overview

This project demonstrates the basic CRUD operations in MongoDB. It covers database and collection creation, inserting documents, reading data, updating documents, deleting documents, and using MongoDB query operators.

A real-world Library System use case is also included to understand how MongoDB can be used in practical applications.

🎯 Objectives

Understand MongoDB basics

Create databases and collections

Insert single and multiple documents

Retrieve and filter documents

Update single and multiple documents

Delete documents

Practice MongoDB query operators

Apply CRUD operations to a real-world use case

🛠️ Technologies Used

MongoDB

MongoDB Shell

Command Prompt (CMD)

📚 Tasks Covered

1. Database & Collection Setup

Created a database named studentDB and a collection named students.

2. Insert Operations

Inserted a single student document

Inserted multiple student documents

Used fields such as:

Name

Age

Course

Status

3. Read Operations

Fetched all documents

Filtered students based on their course

Example:

db.students.find({ course: "MERN Stack" })

4. Update Operations

Updated a single student's status

Updated multiple students at once

5. Delete Operations

Deleted a single document based on a condition

Practiced deleting all documents from the collection

6. Query Operators

Practiced the following MongoDB operators:

$gt - Greater than

$lt - Less than

$in - Match multiple values

$and - Match multiple conditions

$or - Match either condition

$exists - Check whether a field exists

7. Real-World Use Case

Created a Library System using a books collection.

The Library System demonstrates:

Adding books

Searching books by category

Updating book availability

Example:

db.books.find({ category: "Programming" })

📂 Database Structure

Student Database

studentDB
└── students
    ├── name
    ├── age
    ├── course
    └── status

Library Database

libraryDB
└── books
    ├── title
    ├── author
    ├── category
    ├── price
    └── available


🎓 Learning Outcome

By completing this project, I gained practical knowledge of MongoDB CRUD operations, query operators, database and collection management, and applying MongoDB concepts to a real-world Library System.

## AUTHOR

Sourav Kumar K
👨‍💻 Author

Sourav Kumar K
