# Test Data

## Account Data

| Field | Valid Example | Invalid Example |
|---|---|---|
| First Name | Hardik | 123@@ |
| Last Name | Tester | 456@@ |
| Email | unique.test@example.com | abc@ |
| Telephone | 9876543210 | abc123 |
| Password | Test@12345 | 123 |
| Confirm Password | Test@12345 | Test@123 |

## Product Data
- Search keyword: MacBook
- Partial keyword: Mac
- No-result keyword: ZZZ-NO-PRODUCT
- Valid quantity: 1, 2
- Invalid quantity: 0, -1, abc
- Large quantity: 999999

## Address Data
Use test-only address information. Never use real customer/payment information in a public GitHub repository.

## Security Test Strings
- `' OR '1'='1`
- `<script>alert(1)</script>`

These are for basic input-validation checks only. Do not perform destructive security testing against the demo site.
