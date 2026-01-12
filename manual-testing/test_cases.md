 Test Cases – Login Functionality

This document contains test cases for Login functionality. The test cases are written to demonstrate QA thinking at Trainee / Junior level.

 Test Case Format

TC ID – Unique identifier

Title – Short scenario name

Priority – Business importance

Severity – Impact in case of failure

Preconditions – Conditions before execution

Steps – Execution steps

Expected Result – Expected system behavior

TC-01: Login with valid credentials

Type: Positive

TC ID: TC-01
Title: Login with valid credentials
Priority: High
Severity: Critical

Preconditions:

User is on the Login page

A valid user account exists in the system

Steps:

Open the Login page

Enter a valid username

Enter a valid password

Click the Login button

Expected Result:

User is successfully logged in

User is redirected to the post-login page

A successful login message or user dashboard is displayed

TC-02: Login using Enter key with valid credentials

Type: Positive

TC ID: TC-02
Title: Login using Enter key with valid credentials
Priority: Medium
Severity: Major

Preconditions:

User is on the Login page

A valid user account exists in the system

Steps:

Open the Login page

Enter a valid username

Enter a valid password

Press the Enter key on the keyboard

Expected Result:

User is successfully logged in

User is redirected to the post-login page

TC-03: Login with invalid password

Type: Negative

TC ID: TC-03
Title: Login with invalid password
Priority: High
Severity: Major

Preconditions:

User is on the Login page

A valid username exists in the system

Steps:

Open the Login page

Enter a valid username

Enter an invalid password

Click the Login button

Expected Result:

User is not logged in

An error message is displayed indicating invalid credentials

User remains on the Login page

TC-04: Login with empty password

Type: Negative

TC ID: TC-04
Title: Login with empty password
Priority: High
Severity: Major

Preconditions:

User is on the Login page

A valid username exists in the system

Steps:

Open the Login page

Enter a valid username

Leave the password field empty

Click the Login button

Expected Result:

User is not logged in

Validation or error message is displayed

User remains on the Login page

TC-05: Login with empty username

Type: Negative

TC ID: TC-05
Title: Login with empty username
Priority: Medium
Severity: Major

Preconditions:

User is on the Login page

Steps:

Open the Login page

Leave the username field empty

Enter a valid password

Click the Login button

Expected Result:

User is not logged in

Validation or error message is displayed

User remains on the Login page

TC-05: Login with empty username and password

Type: Negative

TC ID: TC-05
Title: Login with empty username and password
Priority: Medium
Severity: Major

Preconditions:

User is on the Login page

Steps:

Open the Login page

Leave the username field empty

Leave the password field empty

Click the Login button

Expected Result:

User is not logged in

Validation or error messages are displayed

User remains on the Login page







  
  
