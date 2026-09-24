# Login Test Cases

| Test Case ID | Test Case | Steps | Test Data | Expected Result | Priority | Status |
|---|---|---|---|---|---|---|
| TC_LOGIN_001 | Valid login | Enter valid email/password and login | Registered credentials | User should log in successfully | High | Not Run |
| TC_LOGIN_002 | Invalid password | Enter valid email and wrong password | Wrong password | Login should fail with appropriate message | High | Not Run |
| TC_LOGIN_003 | Unknown email | Enter unregistered email | Unknown email | Login should fail safely | High | Not Run |
| TC_LOGIN_004 | Blank email | Submit with email blank | Blank email | Email validation should appear | Medium | Not Run |
| TC_LOGIN_005 | Blank password | Submit with password blank | Blank password | Password validation should appear | Medium | Not Run |
| TC_LOGIN_006 | Password masking | Type password | Test@123 | Password should be masked | Low | Not Run |
| TC_LOGIN_007 | Forgot password | Open forgotten-password flow | Registered email | Password recovery should start | High | Not Run |
| TC_LOGIN_008 | Invalid recovery email | Submit unknown email | unknown@example.com | Appropriate response should appear | Medium | Not Run |
| TC_LOGIN_009 | Logout | Login and click logout | Valid account | Session should be terminated | High | Not Run |
| TC_LOGIN_010 | Back after logout | Logout and press browser Back | Protected page | Protected page should not remain accessible as active session | High | Not Run |
| TC_LOGIN_011 | Session persistence | Refresh account page while logged in | Valid session | User should remain logged in according to configuration | Medium | Not Run |
| TC_LOGIN_012 | Case variation | Use email with case variation | USER@EXAMPLE.COM | Behavior should follow email-handling rules | Low | Not Run |
| TC_LOGIN_013 | Remember-me | Use remember option if available | Valid credentials | Remember behavior should match configuration | Medium | Not Run |
| TC_LOGIN_014 | Special input | Use unexpected characters in credentials | ' OR '1'='1 | Input should be safely handled | Critical | Not Run |
| TC_LOGIN_015 | Multiple failed attempts | Perform repeated invalid logins | Invalid credentials | Behavior should match configured security controls | Medium | Not Run |
