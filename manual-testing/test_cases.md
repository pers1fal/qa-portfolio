Test Cases - Login Functionaluty

This documet contain test-cases for Login functionality.The test-casws are written to demonstrate QA thinking at Trainee / Junior level

Test-Case Format

  TC ID - Unique identifire 
  Title - Short scenario name  
  Priority - Business importance
  Severity - Impact in case of failure 
  Preconditions - Conditions before execution
  Expected Result - Expected system behavior



TC-01: Login wirh valid credentials

Type: Positive

TC ID: TC-01
Title: Login with valid credentials
Priority: High
Severity: Critical

Preconditions:
  User is on the login page
  A valid user account exists in the system

Steps:
1.Open the Login page
2.Enter a valid username
3.Enter a valid password
4.Click the Login button

Expected Result:
  User is successfully logged in
  User ir redicted to rhe post-login page
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
1.Open login page
2.Enter a valid username
3.Enter a valid password
4.Press the Enter key on the keyboard

Expected Results:
  User is successfully logged in
  User is redirected to the post-login page


  
TC-03: Login with invalid password

Type: Negative

TC ID: TC-03
Title: Login with invalid password
Priority:High
Severity: Major

Preconditions:
  User is on the Login page
  A valid username exists in the system

Steps:
1.Open the Login page
2.Enter the valid username
3.Enter the invalid password
4.Click the Login buttom

Expected Results:
  User in not logged in
  An error massage is dispalyed indicating invalid credentials
  User remeins on the Login page



TC-04: Login with empty password

Type: Negative

TC ID: TC-04
Title: Login with empty password
Priority:High
Severity:Major

Preconditions:
  User in on Login page
  A valid username exists in the system

Steps:
1.Open the Login page
2.Enter the valid username
3.Leave the password field empty
4.Click the Login buttom

Expexted Results:
  User is not logged in
  Validation or error massage is dispalyed
  User remains on the Login page



TC-05: Login with empty username

Type: Negative

TC ID: TC-05
Title:Login with empty username
Priority: Medium
Severity: Major

Preconditions:
  User is on the Login page

Steps:
1.Open the Login page
2.Leave the username field empty
3.Enter the valid password
4.Click the Login buttom

Expected Results:
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
1.Open the Login page
2.Leave the username field empty
3.Leave the password field empty
4.Click the Login button

Expected Result:
  User is not logged in
  Validation or error messages are displayed
  User remains on the Login page



Automation Coverage

TC-01: Login with valid credentials – Automated

TC-02: Login with invalid password – Automated

TC-03 – TC-05: Covered by manual testing











  
  
