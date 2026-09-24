# Cart Test Cases

| Test Case ID | Test Case | Steps | Test Data | Expected Result | Priority | Status |
|---|---|---|---|---|---|---|
| TC_CART_001 | Add product | Add product from product page | Valid product | Product should appear in cart | High | Not Run |
| TC_CART_002 | Update quantity | Change quantity and update | 2 | Cart total should recalculate | High | Not Run |
| TC_CART_003 | Remove item | Remove product | Existing cart item | Item should disappear | High | Not Run |
| TC_CART_004 | Empty cart | Open cart with no items | Empty cart | Empty-cart message should display | Medium | Not Run |
| TC_CART_005 | Zero quantity | Set quantity to zero | 0 | System should remove or reject according to requirements | High | Not Run |
| TC_CART_006 | Invalid quantity | Enter letters in quantity | abc | Invalid quantity should be rejected | High | Not Run |
| TC_CART_007 | Subtotal | Check subtotal | Known product price | Subtotal should be mathematically correct | High | Not Run |
| TC_CART_008 | Tax | Check tax where configured | Taxable item | Tax should follow configuration | High | Not Run |
| TC_CART_009 | Shipping | Calculate shipping where configured | Valid destination | Shipping cost should be correct | High | Not Run |
| TC_CART_010 | Coupon valid | Apply valid coupon where enabled | Valid coupon | Discount should apply | High | Not Run |
| TC_CART_011 | Coupon invalid | Apply invalid coupon | INVALID10 | Appropriate error should appear | Medium | Not Run |
| TC_CART_012 | Coupon remove | Remove applied coupon | Applied coupon | Discount should be removed | Medium | Not Run |
| TC_CART_013 | Continue shopping | Click continue shopping | Cart item | User should return to shopping flow | Low | Not Run |
| TC_CART_014 | Refresh cart | Refresh cart page | Existing cart | Cart should retain valid items | Medium | Not Run |
| TC_CART_015 | Total after removal | Remove one of multiple items | Two items | Totals should recalculate correctly | High | Not Run |
