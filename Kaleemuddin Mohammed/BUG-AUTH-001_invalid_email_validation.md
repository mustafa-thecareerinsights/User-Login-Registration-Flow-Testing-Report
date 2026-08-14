# Evidence: BUG-AUTH-001

**Module:** Registration  
**Issue:** Invalid email format accepted during registration.  
**Observed Result:** Email value `user@test` was accepted in one validation scenario.  
**Expected Result:** Invalid email format should be rejected with a clear validation message.
