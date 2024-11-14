#Employee Management System

This Java-based Employee Management System enables users to manage employee records through a user-friendly GUI. Features include adding, removing, updating, and viewing employee details, as well as a login system to restrict access.

#Features

Splash Screen: Displays a brief loading screen when the application starts.
Login: Authenticates users before allowing access to employee management features.
Main Dashboard (main_class): The main control center for navigating the system.
Add Employee (AddEmployee.java): Allows users to input and save new employee details.
Remove Employee (RemoveEmployee.java): Provides functionality to delete employee records from the database.
Update Employee (updateEmployee.java): Enables users to modify existing employee details.
View Employee (View_employee.java): Displays stored employee information in a readable format.

#Files

splash.java: Launches the splash screen.
login.java: Manages user authentication.
main_class.java: Acts as the main dashboard of the application.
AddEmployee.java: Adds new employees to the database.
RemoveEmployee.java: Deletes employee records.
updateEmployee.java: Updates existing employee information.
View_employee.java: Displays employee records.
conn.java: Connects to the MySQL database.

#Installation

1.Clone the repository:

git clone <repository-url>

2.Database Setup:

Create a MySQL database named employeemanagement.
Ensure necessary tables, such as employee, are created.

3.Configure Database Credentials:

In conn.java, replace placeholders with your database details:

connection = DriverManager.getConnection("jdbc:mysql://localhost:3306/employeemanagement", "root", "<your_password>");

4.Compile and Run:

Compile the Java files:

javac -d . *.java

Start the application from splash.java:

java employee.management.system.splash

#Usage

1. Login: Begin by logging in.
2. Main Dashboard: Use the dashboard to navigate features:
Add Employee: Input new employee details.
Remove Employee: Enter the employee ID to delete a record.
Update Employee: Modify details of an existing employee.
View Employee: View a list of all employees.

#Technologies Used

Java Swing for GUI
MySQL for database management
JDBC for database connectivity

#Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

#License

This project is licensed under the MIT License.
