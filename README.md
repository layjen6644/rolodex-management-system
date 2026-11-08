# Project Name: Rolodex Management System

## Project Description
The Rolodex Management System is a Java-based console application designed to help users organize and manage their contacts. The application allows users to add, view, search, update, and delete contact records. Contacts are organized into three categories: Friend, Family, and Business. The application uses SQLite for persistent data storage, allowing contact information to be stored when the program ends. 

## Project Tasks
- **Task 1: Set up the development environment**
- Set up Visual Studio Code for Java development
- Add the SQLite JDBC driver to the project
- Create a GitHub repository
- **Task 2: Design the application**
- Identify the purpose and functionality of the application
- Determine how users will interact with the application
- Plan the classes, methods, and relationships between the classes to build the application
- **Task 3: Develop the contact class and implement object-oriented programming concepts**
- Create an abstract Contact superclass to store shared contact information
- Implement Business, Family, and Friend subclasses using inheritance
- Create constructors, getters/setters, and methods for managing contact information
- Use abstraction, inheritance, and polymorphism to organize contacts
- Create a RolodexOperations interface
- Use composition to connect the Rolodex class with the database operations class
- **Task 4: Develop the user interface**
- Create a console-based menu for the user to interact with the application
- Create options to view, search, add, update, and delete contacts
- Receive and validate user input
- Display contact information
- **Task 5: Connect to a database and implement CRUD functionality**
- Create a SQLite database to store contact information
- Establish a database connection using JDBC
- Create a contacts table
- Use SQL statements and prepared statements to interact with the database
- Use CRUD operations to add, retrieve, search, update, and delete contacts from the database
- Prevent duplicate contact entries
- **Task 6: Test the application**
- Test each menu option and database operation
- Verify contact information is save and retrieved
- Identify and correct errors
- **Task 7: Deploy the application**
- Create project documentation and README file
  
## Project Skills Learned
- Java programming and application development
- Object-oriented programming concepts and principles
- Interitance, abstraction, polymoprhism, and composition
- Creating and using interfaces
- Using constructors, getters/seters, and access specifiers
- Working with a SQLite database
- Writing SQL statements and using CRUD operations
- Writing documentation

## Language Used
- Java: Used to develops the application and implement object-oriented concepts
- SQL: Used to create the database table and perform database operations
- SQLite: Used for persistent data storage
- JDBC: Used to establish a connection between the Java application and  SQLite

## Development Process Used
- Iterative development: This application was developed in stages
- Object-oriented design: classes and interfaces were used to improve code organization and maintenance
- Testing and debugging: Features were tested throughout the development process to identify and correct errors and to create a user-friendly flow during user interaction
  
## Notes
- VS Code can be used to open the project
- SQLite JDBC driver is included in the lib folder
- Run App.java file to start the application
- The application will create a SQLite database file if one isn't created already, but one should be included in this project
- The Contacts table will be created automatically when the application starts
  
## Link to Project
https://github.com/layjen6644/rolodex-contact-manager
## License
This project was created as part of an assignment at ECPI for educational purposes. No license was required.
