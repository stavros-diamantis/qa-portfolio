# Bug Reports — saucedemo.com

## BUG-001 — Checkout is allowed with empty cart

- **Environment:** Chrome, Windows 11
- **Preconditions:** User is logged in as `standard_user`
- **Steps to Reproduce:**
  1. Add a product to the cart
  2. Navigate to the cart
  3. Remove the product from the cart
  4. Click "Checkout"
- **Expected Result:** User should see an error message preventing checkout with empty cart
- **Actual Result:** Checkout process proceeds normally with empty cart and $0 total
- **Severity:** High
- **Status:** Open
