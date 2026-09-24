# Product Test Cases

| Test Case ID | Test Case | Steps | Test Data | Expected Result | Priority | Status |
|---|---|---|---|---|---|---|
| TC_PRODUCT_001 | Product name | Open product details | Any active product | Correct product name should display | High | Not Run |
| TC_PRODUCT_002 | Product price | Open product details | Any active product | Correct price should display | High | Not Run |
| TC_PRODUCT_003 | Description | Open description | Any active product | Description should load correctly | Low | Not Run |
| TC_PRODUCT_004 | Images | Switch product images | Product with multiple images | Selected image should display | Low | Not Run |
| TC_PRODUCT_005 | Quantity valid | Add valid quantity | 2 | Quantity should be accepted | High | Not Run |
| TC_PRODUCT_006 | Quantity zero | Enter zero quantity | 0 | System should reject/remove according to requirements | High | Not Run |
| TC_PRODUCT_007 | Negative quantity | Enter negative quantity | -1 | Invalid quantity should be rejected | High | Not Run |
| TC_PRODUCT_008 | Large quantity | Enter excessive quantity | 999999 | System should enforce stock/quantity limits | High | Not Run |
| TC_PRODUCT_009 | Required option | Add product without required option | No option selected | Validation should request option | High | Not Run |
| TC_PRODUCT_010 | Option price | Select paid option | Configured option | Price should update correctly | Medium | Not Run |
| TC_PRODUCT_011 | Add to cart | Click Add to Cart | Valid product | Product should enter cart | High | Not Run |
| TC_PRODUCT_012 | Same product twice | Add same product twice | Same product | Quantity/duplicate behavior should match requirements | Medium | Not Run |
| TC_PRODUCT_013 | Stock display | Open unavailable product | Out-of-stock product | Availability should be shown correctly | High | Not Run |
| TC_PRODUCT_014 | Related products | Inspect related products | Any product | Relevant related products should display where configured | Low | Not Run |
| TC_PRODUCT_015 | Review | Submit/view review where enabled | Valid review data | Review flow should follow configured rules | Low | Not Run |
