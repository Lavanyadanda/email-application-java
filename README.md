# email-application-java
Description
The Email Application is a simple Java program that generates and manages email accounts for new employees in a company. It allows users to:
Generate an email address based on their name and department.
Generate a random password.
Set an alternate email address.
Change the password.
Modify the mailbox capacity.
**Features**

Generates an email based on the user's first name, last name, and department.
Randomly generates a secure password.
Allows users to set an alternate email.
Provides options to change the password and mailbox capacity.
Displays user information including email, mailbox capacity, and alternate email.

**How to Run**

**Prerequisites**

Java Development Kit (JDK) installed (JDK 8 or later).

A terminal or command prompt to run the program.
**Code Structure**

EmailApplication.java - Contains the main method and controls the flow of execution.

Email.java - Contains the logic for email generation, password management, and user settings.

**User Input**

When running the application, the user will be prompted to:

Enter their first and last name.
Choose a department (Sales, Development, Accounting, or None).
Set an alternate email.
Update the mailbox capacity.
Change the password.
**Example Output**
Welcome!
Enter first name: John
Enter last name: Doe
Enter department code (1 for Sales, 2 for Development, 3 for Accounting, 0 for none): 2

Your new email account has been created!
Email: john.doe@dev.company.com
Password: A1B@C3D4!
Mailbox Capacity: 500MB

Do you want to change the password? (y/n)

