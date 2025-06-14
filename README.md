# Customer-Scheduling-Management-System-Java-SQL

Welcome to the Customer Scheduling Management System!

This application includes a variety of features that will allow the User to easily maintain an external database of customers and appointments across multiple Time Zones and Languages.

Features Include:

* Create, Read, Update, and Delete functionality for Appointments and Customers within the database.

* Multi-language support that automatically translates UI elements based on the User's language system setting.

* Recognition of the User's time zone based on the User's system settings and automatic time zone conversion for appointment times.

* Login screen to prevent unauthorized User access using basic(no hashing or salting) password protection.

* Creates a text log for all log-in activity. Records User Name, User Language, User Time Zone, Timestamp, and Success/Failure of the attempt.

* Appointment Main screen with a Filterable Table Display for Appointment data.

* Customer Main screen with Table Display for Customer data.

* Report Dashboard that generates four distinct reports for up-to-date, data-driven insights.

* Generate up-to-date Appointment Schedules for Contacts.

* User-friendly UI that displays messages to the User for information, confirmation, error handling, and warnings.

Author: Jeffrey Robert Lynch 
Contact Information(email): jlyn107@wgu.edu

Application Version: Version 1.0
Date: 04/12/2024

IDE Version: Intellij IDEA Community Edition 2023.2
JDK Version: Oracle Open JDK Version 17.0.8
MySQL Connector Version: mysql-connector-java-8.0.26
JavaFX Version: JavaFX 17.0.8


Directions: This application is dependent on an external database. Without a connection to a compatible database, a User will be unable to login to the application because user names and passwords only exist in the external database.

Run the application. At the Log-in Screen, enter a valid user name and password and click the log-in button. If the user name and password are valid, the user will be directed to the Appointment Main Screen.A message will display to 
inform the user whether or not there are appointments scheduled to begin within 15 minutes. 

Upon navigation to Appointment Main, a table of appointments is shown. Radio buttons allow the user to filter a table of appointments by month or week. Appointments can be added, updated, or deleted from this page. From Appointment Main,
the user can navigate to Customer Main, Reports Main, or Exit the application. 

Upon navigation to Customer Main, a table of customers is shown. Customers can be added, updated, or deleted from this page. From Customer Main, the user can navigate to Appointment Main, Reports Main, or Exit the application.

Upon navigation to Reports Main, the user can generate the following reports: Contact Schedule, Type and Month, Contact and Month, Customer and Month. From Reports Main, the user can naviagte to Appointment Main, Customer Main, or Exit 
the application.  

Report Description: This application can generate four different reports from the Reports Main page. First, it can generate a Contact Schedule that provides customer appointments for each contact. Second, it can generate a report that 
provides a count of the total number of customer appointments by type and month. I chose to create a third report that provides a count of customer appointments by contact and month. This allows Users to determine which contacts are most
popular with customers on a monthly basis. This information can be used for performance reviews and contact reward programs. A fourth report provides a count of customer appointments by customer and month. This allows the User to easily 
track the monthly activity of customers. This information can be used to derive business insights or offer rewards and incentives to customers.
