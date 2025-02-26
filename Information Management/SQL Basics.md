#### SQL Data Types
1. **Numeric Data Types**
	- *INT*: Used to store integers (whole numbers).
	- *SMALLINT*: Used for smaller integers (range: -32,768 to 32,767).
	- *BIGINT*: Used to store very large integers.
	- *DECIMAL*(p, s): Stores fixed-point numbers.
		- Example: `DECIMAL(10, 2)` stores up to 10 digits with 2 after the decimal.
	- *NUMERIC*(p, s): Same as DECIMAL.
		- Example: `NUMERIC(10, 2)`
	- *FLOAT*: Stores floating-point numbers.
	- *REAL*: Stores single-precision floating-point numbers.

2. **Character Data Types**
    - *CHAR(n)*: Fixed-length string (n characters).
        - Example: `CHAR(10)`
    - *VARCHAR(n)*: Variable-length string with a maximum of n characters.
        - Example: `VARCHAR(255)`
    - *TEXT*: Used for large text strings (no fixed length).
        - Example: `TEXT`

3. **Date and Time Data Types**
	- *DATE*: Stores date values (YYYY-MM-DD).
	- *TIME*: Stores time values (HH:MM:SS).
	- *DATETIME*: Stores both date and time values.
	- *TIMESTAMP*: Similar to DATETIME, but often used to track changes.
	- *YEAR*: Stores a year in a four-digit format (YYYY).

4. **Boolean Data Type**
    - *BOOLEAN*: Stores TRUE or FALSE.

5. **Binary Data Types**
    - *BINARY(n)*: Fixed-length binary data.
        - Example: `BINARY(16)`
    - *VARBINARY(n)*: Variable-length binary data.
        - Example: `VARBINARY(255)`
    - *BLOB*: Used for large binary objects like images or files.
        - Example: `BLOB`

6. **Other Data Types**
    - *ENUM*: Used to store predefined values.
        - Example: `ENUM('small', 'medium', 'large')`
    - *JSON*: Used for JSON data.

#### Creating Databases
**Syntax:**

```sql
CREATE DATABASE database_name;
```

**Example:**

```sql
CREATE DATABASE SchoolDB;
```

**Notes:**

- After creating the database, you need to switch to it using USE database_name; in most SQL databases.
- You can check if a database exists using:

```sql
SHOW DATABASES;
```

**Drop a Database:**

```sql
DROP DATABASE database_name;
```

**Example:**

```sql
DROP DATABASE SchoolDB;
```

#### Creating Tables
**Syntax**:

```sql
CREATE TABLE table_name (
    column_name data_type constraints,
    column_name data_type constraints,
);
```

**Example**:

```sql
CREATE TABLE Students (
    StudentID INT PRIMARY KEY,
    FirstName VARCHAR(50),
    LastName VARCHAR(50),
    BirthDate DATE,
    Email VARCHAR(100)
);
```

**Common Constraints**:
- *PRIMARY KEY*: Uniquely identifies each record in the table.
- *NOT NULL*: Ensures the column cannot have a NULL value.
- *UNIQUE*: Ensures all values in a column are unique.
- *DEFAULT*: Sets a default value for a column if no value is provided.
- *CHECK*: Ensures the value in the column meets a specific condition.

**Example with Constraints**:

```sql
CREATE TABLE Employees (
    EmployeeID INT PRIMARY KEY,
    FirstName VARCHAR(100) NOT NULL,
    LastName VARCHAR(100) NOT NULL,
    HireDate DATE,
    Salary DECIMAL(10, 2) CHECK (Salary > 0)
);
```

#### Altering Tables:

**Adding a Column:**

```sql
ALTER TABLE table_name ADD column_name data_type;
```

**Dropping a Column:**

```sql
ALTER TABLE table_name DROP COLUMN column_name;
```

**Modifying a Column:**

```sql
ALTER TABLE table_name MODIFY column_name new_data_type;
```

**Dropping a Table:**

```sql
DROP TABLE table_name;
```