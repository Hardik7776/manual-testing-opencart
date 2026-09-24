# Test Plan — OpenCart Demo Store

## 1. Objective
Validate the core functionality and user experience of the OpenCart e-commerce application and identify defects that could affect browsing, account management, shopping cart, checkout and order workflows.

## 2. Scope

### In Scope
- Registration
- Login and logout
- Password recovery
- Product search
- Product details and options
- Wishlist
- Shopping cart
- Coupons where enabled
- Checkout
- Payment/shipping selection where enabled
- Order confirmation and history
- Navigation and UI validation
- Form validation
- Basic compatibility testing
- Basic accessibility/usability checks

### Out of Scope
- Production payment processing
- Real customer data
- Destructive security testing
- Load/stress testing
- Infrastructure/server testing

## 3. Test Types
- Functional
- Smoke
- Regression
- Positive
- Negative
- Boundary value
- UI/Usability
- Compatibility
- Basic security validation

## 4. Entry Criteria
- Demo application is accessible.
- Test environment/browser is available.
- Test data is prepared.
- Required test accounts can be created.

## 5. Exit Criteria
- Planned test cases are executed or marked Blocked.
- Critical/high-priority failures are documented.
- Defects contain reproducible steps and evidence where available.
- Execution summary is prepared.

## 6. Severity
- Critical: Core application/security failure with severe impact.
- High: Major business flow is unavailable or incorrect.
- Medium: Important functionality is affected but workaround exists.
- Low: Minor UI/content/usability issue.

## 7. Priority
- Critical: Must be addressed immediately.
- High: Important for the current release.
- Medium: Should be addressed in normal development.
- Low: Can be scheduled after higher-impact issues.

## 8. Environment
- OS: Windows 10/11
- Browsers: Chrome, Firefox, Edge
- Viewports: Desktop, tablet, mobile
- Network: Normal internet connection

## 9. Risks
- Demo data may reset.
- Demo configuration may change.
- Payment/shipping functionality may be disabled.
- Some features may differ between OpenCart versions.

## 10. Deliverables
- Test plan
- Test scenarios
- 110+ test cases
- Test data
- Bug reports
- Test execution report
- Screenshots/evidence
