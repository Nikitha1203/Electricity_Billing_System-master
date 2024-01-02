# Electricity_Billing_System-master

Secure User Authentication:

Users can create personal logins for enhanced security, ensuring authorized access to the system.
Customer Management:

Add Customer functionality allows users to input and manage customer details efficiently.
Billing Operations:

Users can calculate, pay electricity bills, and generate detailed invoices through a user-friendly interface.
Database Connectivity:

Utilizes JDBC for seamless integration between the Java application and MySQL database.
Employs a structured class setup, including Splash Screen, Login Screen, Main System, Add Customer, Pay Bill, Generate Bill, Show Details, Last Bill, and Connection Setup (JDBC - MySQL) for a cohesive user experience.
Database Structure (MySQL):

Login Table: Stores user login credentials (UserName, Password).
Bill Table: Records electricity consumption details (MeterNumber, Units, Month, Amount).
Emp Table: Contains customer information (Name, MeterNumber, Address, State, City, Email, Phone).
Tax Table: Stores additional billing information (MeterLocation, MeterType, PhaseCode, BillType, Days, MeterRent, MCB_Rent, ServiceRent, GST).
Screenshots:

Login
Main Page
Add Customer
Calculate Bill
Details
Generate Bill
Implementation Details:

Development Environment: Created using IntelliJ IDEA.
Class Structure: Comprises 9 classes working in tandem for a seamless user experience.
JDBC Integration: Facilitates efficient communication between the Java application and MySQL tables.