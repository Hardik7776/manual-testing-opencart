# Checkout Test Cases

| Test Case ID | Test Case | Steps | Test Data | Expected Result | Priority | Status |
|---|---|---|---|---|---|---|
| TC_CHECKOUT_001 | Checkout access | Proceed from cart | Cart with item | Checkout should open | High | Not Run |
| TC_CHECKOUT_002 | Guest checkout | Proceed as guest where enabled | Guest user | Checkout should follow configuration | High | Not Run |
| TC_CHECKOUT_003 | Billing required fields | Leave mandatory billing field blank | Missing field | Validation should appear | High | Not Run |
| TC_CHECKOUT_004 | Invalid email | Enter invalid checkout email | abc@ | Email validation should appear | High | Not Run |
| TC_CHECKOUT_005 | Postcode validation | Enter invalid postcode | Invalid postcode | Validation should follow configured rules | Medium | Not Run |
| TC_CHECKOUT_006 | Shipping address | Enter valid shipping address | Valid address | Address should be accepted | High | Not Run |
| TC_CHECKOUT_007 | Different shipping address | Use different shipping and billing addresses | Two valid addresses | Correct addresses should be retained | Medium | Not Run |
| TC_CHECKOUT_008 | Shipping method | Select available shipping method | Configured method | Selection should be retained | High | Not Run |
| TC_CHECKOUT_009 | Payment method | Select available payment method | Configured method | Selection should be retained | High | Not Run |
| TC_CHECKOUT_010 | No payment | Continue without required payment | No method | Checkout should block progression | High | Not Run |
| TC_CHECKOUT_011 | Terms unchecked | Attempt order without terms | Unchecked | Order should not be submitted | High | Not Run |
| TC_CHECKOUT_012 | Review order | Review before submit | Valid checkout data | Products, quantities and totals should be correct | High | Not Run |
| TC_CHECKOUT_013 | Total consistency | Compare cart and checkout totals | Known total | Applicable totals should match | High | Not Run |
| TC_CHECKOUT_014 | Place order | Submit valid order | Valid checkout data | Order should be created successfully | Critical | Not Run |
| TC_CHECKOUT_015 | Duplicate click | Click place order repeatedly | Valid checkout data | Duplicate order creation should be prevented | Critical | Not Run |
| TC_CHECKOUT_016 | Payment failure | Use failed payment response where available | Test failure | Order should not be marked paid | Critical | Not Run |
| TC_CHECKOUT_017 | Payment cancel | Cancel payment where available | Cancelled transaction | User should return with correct status | High | Not Run |
| TC_CHECKOUT_018 | Back navigation | Navigate backward during checkout | Valid data | Previously entered data should persist where supported | Medium | Not Run |
| TC_CHECKOUT_019 | Order confirmation | Complete order and inspect confirmation | Successful order | Confirmation should show order information | High | Not Run |
| TC_CHECKOUT_020 | Confirmation email | Complete order and check email if configured | Successful order | Confirmation email should be generated if enabled | Medium | Not Run |
