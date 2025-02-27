### Challenge: Library Management System

#### Step 1: Create the Database

Create a database named `library_db`.

#### Step 2: Create the Tables

Create the following tables:

1. **Authors Table**
    
    - `id` (Primary Key, Integer, Auto Increment)
    - `first_name` (Varchar, 100)
    - `last_name` (Varchar, 100)
    - `birth_year` (Integer)
2. **Books Table**
    
    - `id` (Primary Key, Integer, Auto Increment)
    - `title` (Varchar, 255)
    - `author_id` (Foreign Key, references the `id` in the `Authors` table)
    - `publication_year` (Integer)
    - `genre` (Varchar, 100)
3. **Users Table**
    
    - `id` (Primary Key, Integer, Auto Increment)
    - `first_name` (Varchar, 100)
    - `last_name` (Varchar, 100)
    - `email` (Varchar, 150)
    - `join_date` (Date)
4. **Loans Table**
    
    - `id` (Primary Key, Integer, Auto Increment)
    - `book_id` (Foreign Key, references the `id` in the `Books` table)
    - `user_id` (Foreign Key, references the `id` in the `Users` table)
    - `loan_date` (Date)
    - `return_date` (Date, can be NULL if not returned yet)

#### Step 3: Insert Some Sample Data

1. Insert at least 3 authors.
2. Insert at least 5 books (make sure to associate books with authors).
3. Insert at least 4 users.
4. Insert at least 3 loans (associate books with users and specify loan dates).

#### Step 4: Queries

After setting up the database and inserting data, perform the following queries:

1. **Get a list of all books and their authors**.
2. **Get the list of books that were published after 2000**.
3. **Find all users who borrowed books (i.e., have records in the loans table)**.
4. **List all books currently borrowed (i.e., where `return_date` is NULL)**.
5. **Count how many books each author has written**.
6. **Find the users who have borrowed more than two books**.
7. **Get the total number of books loaned out in a specific year** (you can choose a year to focus on).