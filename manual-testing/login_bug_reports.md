## BUG-SC-01: Login works with empty password

**Severity:** Major  
**Priority:** High  

### Preconditions:
- User is on the Login page  
- A valid username exists in the system  

### Steps to Reproduce:
1. Open login page  
2. Enter valid username  
3. Leave password empty  
4. Click Login  

### Actual Result:
- User is logged in  

### Expected Result:
- Error message should be shown  
- User should not be logged in  



## BUG-SC-02: Missing error message after entering invalid credentials

**Severity:** Major  
**Priority:** Medium  

### Preconditions:
- User is on the Login page  

### Steps to Reproduce:
1. Open login page  
2. Enter invalid username  
3. Enter invalid password  
4. Click Login  

### Actual Result:
- User does not see any error message  

### Expected Result:
- Error message indicating invalid credentials should be displayed  



## BUG-SC-03: UI and localization issues in login error message

**Severity:** Minor  
**Priority:** Medium  

### Preconditions:
- User is on the Login page  
- Application language is set to Ukrainian  

### Steps to Reproduce:
1. Open the login page  
2. Enter an incorrect password  
3. Click Login  

### Actual Result:
- Error message has low contrast (light grey on white background)  
- Error message text is partially cut off  
- Error message is displayed in English  

### Expected Result:
- Error message should be clearly readable  
- Text should be fully visible  
- Message should be displayed in Ukrainian  



## BUG-SC-04: Login button is enabled when required fields are empty

**Severity:** Minor  
**Priority:** Low  

### Preconditions:
- User is on the Login page  

### Steps to Reproduce:
1. Open the Login page  
2. Leave the username field empty  
3. Leave the password field empty  

### Actual Result:
- Login button is enabled and clickable  

### Expected Result:
- Login button should be disabled until all required fields are filled  



## BUG-SC-05: Error message is not cleared after successful login

**Severity:** Minor  
**Priority:** Low  

### Preconditions:
- User is on the Login page  
- User has previously entered invalid credentials  

### Steps to Reproduce:
1. Open the Login page  
2. Enter invalid username and password  
3. Click Login  
4. Observe the error message  
5. Enter valid username and password  
6. Click Login  

### Actual Result:
- User is logged in  
- Previous error message remains visible  

### Expected Result:
- User is logged in successfully  
- Error message should be cleared  
