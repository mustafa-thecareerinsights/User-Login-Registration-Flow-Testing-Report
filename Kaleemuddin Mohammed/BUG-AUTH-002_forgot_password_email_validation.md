# Evidence: BUG-AUTH-002

**Module:** Forgot Password  
**Issue:** Invalid email format accepted before reset request.  
**Observed Result:** Email value `abc@` was not blocked immediately.  
**Expected Result:** System should display `Please enter a valid email address`.
