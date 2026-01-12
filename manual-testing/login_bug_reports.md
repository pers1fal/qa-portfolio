BUG-SC-01 Login works with empty password

Severity: Major
Priority: High

Preconditions:

User is on the Login page

A valid username exists in the system

Steps to Reproduce:

Open login page

Enter valid username

Leave password empty

Click Login

Actual Result: User is logged in
Expected Result: Error message should be shown and user should not be logged in

BUG-SC-02 Missing error message after entering invalid credentials

Severity: Major
Priority: Medium

Preconditions:

User is on the Login page

Steps to Reproduce:

Open login page

Enter invalid username

Enter invalid password

Click Login

Actual Result: User does not see any error message
Expected Result: User should see an error message indicating invalid credentials

BUG-SC-03 UI and localization issues in login error message

Severity: Minor
Priority: Medium

Preconditions:

User is on the Login page

Application language is set to Ukrainian

Steps to Reproduce:

Open the login page

Enter an incorrect password

Click Login

Actual Result:

Error message text has low contrast (light grey on white background)

Error message text is partially cut off

Error message is displayed in English instead of Ukrainian

Expected Result:

Error message should be clearly readable

Text should be fully visible

Message should be displayed in Ukrainian

BUG-SC-04 Login button is enabled when required fields are empty

Severity: Minor
Priority: Low

Preconditions:

User is on the Login page

Steps to Reproduce:

Open the Login page

Leave the username field empty

Leave the password field empty

Actual Result: Login button is enabled and clickable
Expected Result: Login button should be disabled until all required fields are filled

BUG-SC-05 Error message is not cleared after successful login

Severity: Minor
Priority: Low

Preconditions:

User is on the Login page

User has previously entered invalid credentials

Steps to Reproduce:

Open the Login page

Enter invalid username and password

Click Login

Observe the error message

Enter valid username and password

Click Login

Actual Result: User is logged in, but previous error message remains visible
Expected Result: User is successfully logged in and the error message should be cleared
