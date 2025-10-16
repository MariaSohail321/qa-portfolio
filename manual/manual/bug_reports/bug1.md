# Bug Report 1 — Login Accepts Empty Password

**ID:** BUG001  
**Title:** Login page accepts blank password field  
**Environment:** Chrome 120, Windows 10  
**Severity:** High  
**Priority:** Medium  

### Steps to Reproduce
1. Open the login page  
2. Enter a valid username  
3. Leave the password field empty  
4. Click the “Login” button  

### Expected Result
System should show an error message “Password cannot be empty.”  

### Actual Result
Login request is sent, and the page reloads with no message.  

### Status
New
