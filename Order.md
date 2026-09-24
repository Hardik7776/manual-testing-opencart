# Order Test Cases

| Test Case ID | Test Case | Steps | Test Data | Expected Result | Priority | Status |
|---|---|---|---|---|---|---|
| TC_ORDER_001 | Order history | Open order history | Existing order | Order should be listed | Medium | Not Run |
| TC_ORDER_002 | Order details | Open order details | Existing order | Items, totals and status should be correct | High | Not Run |
| TC_ORDER_003 | Order status | Inspect order status | Existing order | Current configured status should display | Medium | Not Run |
| TC_ORDER_004 | Order total | Compare order total with checkout | Known order | Totals should remain consistent | High | Not Run |
| TC_ORDER_005 | Order items | Inspect ordered products | Existing order | Correct products and quantities should display | High | Not Run |
| TC_ORDER_006 | Order pagination | Navigate order history pages | Multiple orders | Pagination should work correctly | Low | Not Run |
| TC_ORDER_007 | Reorder | Use reorder where enabled | Existing eligible order | Items should be placed into cart | Medium | Not Run |
| TC_ORDER_008 | Return | Submit return where enabled | Eligible order | Return request should be submitted | Medium | Not Run |
| TC_ORDER_009 | Return validation | Submit incomplete return | Missing required data | Validation should appear | Medium | Not Run |
| TC_ORDER_010 | Invoice | Open/print invoice where enabled | Existing order | Invoice should display correct order data | Low | Not Run |
