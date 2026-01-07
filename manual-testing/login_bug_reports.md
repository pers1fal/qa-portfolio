### BUG-SC-01 Login works with empty password
**Severity:** Major 
**Priority:** High

**Steps to Reproduce:** 
1. Open login page
2. Enter valid username
3. Leave password empty
4. Click Login

**Actual Result:**    User is logged in
**Expected Result:**  Error message should be shown

### BUG-SC-02 Missing error message after entering invalid credentials on the Login page
**Severity:** Major  
**Priority:** Medium  

**Steps to Reproduce:**
1. Open login page
2. Enter invalid username
3. Enter invalid password
4. Click Login  

**Actual Result:** User does not see any error message  
**Expected Result:** User should see an error message indicating invalid credentials


### BUG-SC-03 UI and localization issues in login error message
**Severity:** Minor  
**Priority:** Medium  

**Steps to Reproduce:**
1. Open the login page
2. Enter an incorrect password
3. Click "Login"

**Actual Result:**
- Error message text has low contrast (light grey on white background)
- Error message text is partially cut off
- Error message is displayed in English instead of Ukrainian

**Expected Result:**
- Error message should be clearly readable
- Text should be fully visible
- Message should be displayed in Ukrainian
