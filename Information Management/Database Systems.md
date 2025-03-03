#### What is DBMS?
**Database Management System (DBMS)** 
- are software for storing and retrieving users' data while considering appropriate security measures.
- it provides an interface to perform various operations 
##### DBMS allows users to do the following:
- **Data Definition** - *creation, modification, removal* of definition of the organization of data
- **Data Updation** - *insertion, modification, deletion* of actual data
- **Data Retrieval** - *retrieve data to be used* by applications
- **User Administration** - *registering and monitoring users*, maintain data integrity, enforcing security, etc...

##### Characteristics of DBMS

- Uses a digital repository established on a server to store and manage the information
- can provide a clear and logical view of the process that manipulates data
- contains automatic backup and recovery procedures
- contains ACID properties which maintain data in a healthy state in case of failure
- can reduce the complex relationship between data 
- is used to support manipulation and processing of data
- is used to provide security of data
- can view the database from different viewpoints according to requirements of user

##### Advantages of DBMS 
- **Controls database redundancy**
	- it can control data redundancy because it stores all the data in one single database file
- **Data sharing**
	- authorized users of an organization can share data among multiple users
- **Easy Maintenance**
	- can be easily maintainable due to the centralized nature of the database system.
- **Reduce Time** 
	- it reduces development time and maintenance need 
- **Backup** 
	- it provides backup and recovery subsystems which create automatic backup of data from hardware and software failures 
- **Multiple User Interface** 
	- it provides different types of user interfaces like GUIs and APIs (Application Program Interfaces)

##### Disadvantages of DBMS
- **Cost of Hardware and Software**
	- it requires a high speed of data processor and large memory
- **Size**
	- it occupies a large space of disks and large memory to run them efficiently
- **Complexity**
	- database system creates additional complexity and requirements
- **Higher impact of failure**

##### Users in a DBMS Environment

| Component Name              | Task                                                                                |
| --------------------------- | ----------------------------------------------------------------------------------- |
| **Application Programmers** | write programs in various programming languages to interact with databases          |
| **Database Administrators** | responsible for managing the entire DBMS system. Also known as DBA (Database Admin) |
| **End-Users**               | interact with the database management system                                        |
##### Application of DBMS

| Sector                | Use of DBMS                                                                          |
| --------------------- | ------------------------------------------------------------------------------------ |
| **Banking**           | customer information, account activities, payments, etc.                             |
| **Airlines**          | reservations and schedule information                                                |
| **Universities**      | student information, course registrations, colleges and grades                       |
| **Telecommunication** | help keep call records, monthly bills, maintaining balances, etc                     |
| **Finance**           | storing information about stock, sales, purchases of financial instruments           |
| **Sales**             | storing customer, product, and sales information                                     |
| **Manufacturing**     | management of supply chain and for tracking production of items                      |
| **HR Management**     | information about employees, salaries, payroll, deduction, generating paychecks, etc |

--- 
#### Types of Databases
##### According to Number or Users
- **Single User Database** - *only a single user can access* the database (ex. Personal Computers)
- **Multi-user Database** - *two or more than two users accessing simultaneously* (ex. Databases of banks, insurance agencies, supermarkets, etc)
##### According to Classification by Location
- **[[Centralized Database]]** - data located at *single site*
- **[[Distributed Database]]** - data distributed *across different sites of an organization* connected via communication links
- **[[Cloud Database]]** - *created and maintained using cloud data services* that provide defined performance measures
##### According to Data Types
- **General Purpose Database** - aim to *meet the needs of as many applications as possible*
- **Discipline Specific or Special Purpose Database** - *functions are limited to what it is required* to handle
- **Operational Database or Online** - designed to *support a company's day to day* operations
---
#### Analytical Databases
- stores and manages big data, including business, market, and customer data for business intelligence analysis
- are specially optimized for faster queries and scalability
- designed to quickly analyze massive amounts of data 
- 1000 times faster than an operational database for demanding analytical workloads
##### Examples of Analytical Databases
- **Market data** - historical price and volume data for financial markets
- **Transactional data** - historical transaction that can include purchasing patterns for improved marketing
- **Sensor data** - data from sensors that monitor situations like weather
- **Natural Language data** - study of social media posts for research purposes
- **Process data** - study of processes to better understand logistics and find bottlenecks
- **Machine data** - software and hardware-generated data from products to improve efficiency

##### Difference Between Analytical and Operational Database 
**Analytical Database**
- also known as *OLAP (OnLine Analytical Processing)*
- is used for fast processing of massive amounts of data with few or no filters 
**Operational Database**
- also known as *OLTP (OnLine Transaction Processing)*
- is used for looking up single rows of information for quick updates
##### Benefits
- **Columnar data storage** - column-based design which allows for fast analysis
- **Efficient data compression** - columnar design allows efficient version of data compression
- **Distributed workloads** - data is stored on a cluster of servers called *nodes*