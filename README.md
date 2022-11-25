# BankProject
The project uses Java within an IDE  to create, read, update existing data within MoneyBank’s database on My SQL. 
## **Purpose**

The overall purpose of this project was to design two portals (customer & administrator) portals for the client MoneyBank which allows both users to perform a series of functionalities within MoneyBank’s existing data base.

This solution of this project was to address MoneyBank’s phase of digitalisation for both customer’s and administrators which can be imported to both app & web based applications.

## **What does the project do?**

The project uses Java Programming language within an integrated development environment (Eclipse) to create, read, update existing data within MoneyBank’s database on My SQL. This connection takes place through JDBC (Java Database Connectivity).

The project allows two different types of users to perform a series of functions within Money Bank database. Please read below what the project allows each user to do:

### User 1: A customer can…

- **Withdraw cash or cheque from existing MoneyBank account stored within the transaction details table within MoneyBank’s database.
- **Deposit cash or cheque into existing MoneyBank account stored within the transaction details table within MoneyBank’s database.
- **Apply for a loan through MoneyBank’s loan eligibility checker

### User 2: An administrator can…

- **Access the admin system through authentication (username & password protection)
- **Add a new customer to MoneyBank’s customer table within MoneyBank’s database.
- **View an existing customer stored within MoneyBank’s Customer table within MoneyBank’s database.
- **Add accounts to MoneyBank’s accounts table within MoneyBank’s database.
- **View accounts to MoneyBank’s accounts table within MoneyBank’s database.
- **Add branch to MoneyBank’s Branch table within MoneyBank’s database.
- **View branch within MoneyBank’s Branch table within MoneyBank’s database.
- **View loans within MoneyBank’s loan table within MoneyBank’s database.
- **View transaction details within MoneyBanks transaction details table.

# Design & flow of the system

The design of the project has taken a creational design pattern utilising multiple classes and object creation within the main method. The project has 3 classes - a main class , admin class and user class. The main method instantiates both the admin and user class through the creation of objects  utilising the new keyword. The creation of the new objects within the main method allows the main method to call the methods within both the admin and user classes.

To enable JDBC connection, the admin and user classes imported the java SQL package utilising **import java.sql.***.

The flow of the system was designed for the user presenting clear options for both types of users to access the multiple functionalities. The project successfully imported scanner to generate user input to determine the flow of the code.
