# Bug Report 3 — Incorrect Error Message on Invalid Email

**ID:** BUG003  
**Title:** Login shows wrong error message for invalid email format  
**Environment:** Chrome 120, Windows 10  
**Severity:** Low  
**Priority:** Low  

### Steps to Reproduce
1. Go to login page  
2. Enter `test@.com` in the email field  
3. Enter any password  
4. Click Login  

### Expected Result
Error message: “Please enter a valid email address.”  

### Actual Result
Error message shown: “User not found.”  

### Status
New
