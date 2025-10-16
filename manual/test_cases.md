# Test Cases – Login Page (Demo Web App)

| Test Case ID | Test Scenario | Steps to Execute | Expected Result | Status |
|---------------|---------------|------------------|------------------|---------|
| TC001 | Verify login with valid credentials | 1. Open login page<br>2. Enter valid username and password<br>3. Click Login | User should be redirected to dashboard | Pass |
| TC002 | Verify error message for invalid password | 1. Open login page<br>2. Enter valid username and invalid password<br>3. Click Login | “Invalid credentials” error should appear | Pass |
| TC003 | Verify login button disabled when fields empty | 1. Open login page<br>2. Leave username and password blank<br>3. Check login button | Login button should be disabled | Pass |
| TC004 | Verify password field masked | 1. Open login page<br>2. Type password<br>3. Observe password field | Entered text should be hidden (••••) | Pass |
| TC005 | Verify “Remember Me” checkbox functionality | 1. Select “Remember Me”<br>2. Login<br>3. Close browser and reopen site | User should stay logged in | Pending |
