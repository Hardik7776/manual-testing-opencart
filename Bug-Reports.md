# Bug Reports

## Important
The examples below are **sample defect-report formats** for the portfolio. They should not be presented as confirmed live defects unless you reproduce them on the current demo environment.

---

## BUG-001 — Sample: Invalid input validation

**Title:** Invalid email format is accepted during registration

**Module:** Registration  
**Severity:** Medium  
**Priority:** High  
**Environment:** Chrome / Windows  
**Precondition:** Registration page is accessible.

### Steps
1. Open Registration.
2. Enter valid values in all mandatory fields.
3. Enter `abc@` in the email field.
4. Submit the form.

### Expected
A clear email-format validation message should be displayed and registration should be blocked.

### Actual
To be verified during execution.

### Status
Needs Reproduction

---

## BUG-002 — Sample: Cart total calculation

**Title:** Cart grand total does not match item subtotal and applicable charges

**Module:** Shopping Cart  
**Severity:** High  
**Priority:** High

### Steps
1. Add a product to cart.
2. Change quantity.
3. Review subtotal, tax, shipping and grand total.

### Expected
Grand total should equal the applicable subtotal plus/minus configured charges and discounts.

### Actual
To be verified during execution.

### Status
Needs Reproduction

---

## BUG-003 — Sample: Checkout duplicate submission

**Title:** Multiple rapid clicks on Place Order may create duplicate submissions

**Module:** Checkout  
**Severity:** Critical  
**Priority:** Critical

### Steps
1. Complete checkout with valid data.
2. Rapidly click Place Order multiple times.
3. Inspect resulting order records.

### Expected
The application should prevent duplicate order submission.

### Actual
To be verified during execution.

### Status
Needs Reproduction
