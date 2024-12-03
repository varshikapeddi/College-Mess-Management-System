# College Mess ManagementSystem
# Project Description
The College Mess Management System is a Java-based application designed to streamline
the management of college mess activities. It features role-specific dashboards for
students, chefs, managers, and college management, with functionalities such as menu
planning, feedback collection, inventory management, and report generation. The project
integrates with a MySQL database and uses JDBC for database connectivity.sque
# Required Software, Libraries, and Versions
1.Java Development Kit (JDK): Version 17 or higher
2.MySQL: Version 8.0 or higher
3.MySQL JDBC Driver: mysql-connector-j-9.1.0.jar
4.Integrated Development Environment (IDE): IntelliJ IDEA (or any other Java IDE)
5.Additional Libraries:
 Standard Java libraries (java.sql, java.io)
 JDBC for MySQL database integration
# Setup Instructions
1. Software Installation
1.Install JDK 17 or higher and set up the environment variables (JAVA_HOME).
2.Install MySQL Server and MySQL Workbench.
3. Download the MySQL JDBC Driver (mysql-connector-j-9.1.0.jar) and add it to the
classpath in IntelliJ IDEA.
2. Database Setup
1.Create a new MySQL database named messmangement.
2.Run the provided SQL scripts to create the required tables (users, feedback, menu,
inventory, staff, dishes, counters, messpopulation).
3.Populate the tables with initial data using the provided SQL insert statements
Steps to Run the Project
# Project Execution
1.Open the project in IntelliJ IDEA.
2.Add the MySQL JDBC Driver to the classpath:
Go to File > Project Structure > Libraries.
Click + and add the mysql-connector-j-9.1.0.jar file.
3.Ensure that your MySQL server is running and your database is set up as described
above.
4. Configure the database connection in the code by updating the connection details:
 command: Connection con = DriverManager.getConnection(
 "jdbc:mysql://localhost:3306/messmangement", "root",
"your_password");
5. Compile the project:
Use IntelliJ's build tools or run the following command in the terminal:
 javac temmain.java
6. Run the project:
In IntelliJ, right-click the Main class and select Run.
Or use the terminal
 java Main
