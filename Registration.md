# Registration Test Cases

| Test Case ID | Test Case | Steps | Test Data | Expected Result | Priority | Status |
|---|---|---|---|---|---|---|
| TC_REG_001 | Valid registration | Enter valid unique account data and submit | Unique valid user data | Account should be created successfully | High | Not Run |
| TC_REG_002 | Empty first name | Leave first name blank and submit | Blank first name | Required-field validation should appear | Medium | Not Run |
| TC_REG_003 | Empty last name | Leave last name blank and submit | Blank last name | Required-field validation should appear | Medium | Not Run |
| TC_REG_004 | Invalid email | Enter invalid email format | abc@ | Email validation should appear | High | Not Run |
| TC_REG_005 | Duplicate email | Register using an existing email | Existing email | Duplicate-account message should appear | High | Not Run |
| TC_REG_006 | Password mismatch | Enter different password and confirmation | Test@123 / Test@124 | Mismatch validation should appear | High | Not Run |
| TC_REG_007 | Short password | Enter password below allowed length | 123 | Password validation should appear | High | Not Run |
| TC_REG_008 | Invalid telephone | Enter alphabetic telephone value | abc123 | Telephone validation should appear | Medium | Not Run |
| TC_REG_009 | Invalid name characters | Enter unsupported special characters/numbers | John123 | Input should be validated according to requirements | Medium | Not Run |
| TC_REG_010 | Privacy policy unchecked | Submit without accepting required policy | Policy unchecked | Registration should not proceed | High | Not Run |
| TC_REG_011 | Valid boundary name | Use boundary-length valid name | Boundary-length value | Value within allowed range should be accepted | Medium | Not Run |
| TC_REG_012 | Exceed name boundary | Use value beyond allowed length | Over-limit value | System should reject or constrain input | Medium | Not Run |
| TC_REG_013 | Password visibility | Toggle password visibility if available | Test@123 | Visibility changes without altering value | Low | Not Run |
| TC_REG_014 | Successful redirect | Complete valid registration | Unique valid data | User should reach configured success/account page | High | Not Run |
| TC_REG_015 | Form retention | Trigger validation and inspect entered valid fields | Valid + one invalid field | Valid entered values should be retained where supported | Low | Not Run |
