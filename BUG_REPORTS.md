# Bug Reports

## Bug Overview
This document tracks bugs found during QA testing of the e-commerce platform. Five critical and high-priority issues have been identified affecting core functionality including cart operations, user authentication, checkout process, product display, and coupon validation.

## Detailed Bugs

### BUG-01: Add to Cart Button Not Working
- **Description:** User is unable to add product to cart from product page
- **Steps to Reproduce:**
  1. Go to product page
  2. Click "Add to Cart"
  3. Observe button behavior
- **Expected Result:** Product should be added to cart
- **Actual Result:** Nothing happens when button is clicked
- **Severity:** High
- **Priority:** High
- **Status:** Open

### BUG-02: Login Fails with Valid Credentials
- **Description:** Registered user cannot log in with correct email and password
- **Steps to Reproduce:**
  1. Go to login page
  2. Enter valid credentials
  3. Click login
- **Expected Result:** User should be logged in successfully
- **Actual Result:** Error message displayed: "Invalid credentials"
- **Severity:** Critical
- **Priority:** High
- **Status:** Open

### BUG-03: Cart Total Not Updating
- **Description:** Cart total does not update when quantity is changed
- **Steps to Reproduce:**
  1. Add product to cart
  2. Change quantity
  3. Verify total updates
- **Expected Result:** Total price should update based on quantity
- **Actual Result:** Total remains the same
- **Severity:** Medium
- **Priority:** Medium
- **Status:** Open

### BUG-04: Broken Image on Product Page
- **Description:** Product image fails to load on product detail page
- **Steps to Reproduce:**
  1. Search product
  2. Click product
  3. Observe product image
- **Expected Result:** Product image should display correctly
- **Actual Result:** Image appears broken or missing
- **Severity:** Low
- **Priority:** Low
- **Status:** Open

### BUG-05: Invalid Coupon Accepted
- **Description:** System accepts invalid coupon codes
- **Steps to Reproduce:**
  1. Go to checkout
  2. Enter invalid coupon
  3. Apply coupon
- **Expected Result:** Error message should display
- **Actual Result:** Discount is applied incorrectly
- **Severity:** High
- **Priority:** Medium
- **Status:** Open

## Summary
| Bug ID | Title | Severity | Priority | Status |
|--------|-------|----------|----------|--------|
| BUG-01 | Add to Cart Button Not Working | High | High | Open |
| BUG-02 | Login Fails with Valid Credentials | Critical | High | Open |
| BUG-03 | Cart Total Not Updating | Medium | Medium | Open |
| BUG-04 | Broken Image on Product Page | Low | Low | Open |

<img width="1187" height="372" alt="image" src="https://github.com/user-attachments/assets/0a545431-73fe-4655-bced-e7657684cfdb" />

| BUG-05 | Invalid Coupon Accepted | High | Medium | Open |

## Screenshot Reference
[Screenshots to be added]
