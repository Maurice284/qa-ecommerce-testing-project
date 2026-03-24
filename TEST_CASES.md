# TEST CASES for E-Commerce Website

## Overview
This document contains comprehensive test cases for the e-commerce website, covering all functionality as outlined in the bug reports and test case table. Each test case is organized by feature area and includes the following sections:

- **Test Case ID**: Unique identifier for the test case
- **Description**: Brief details of what is being tested
- **Preconditions**: Any conditions that must be met before executing the test
- **Test Steps**: Steps to carry out the test
- **Expected Results**: What the outcome should be if the test is successful

## Feature Area: User Authentication                                                                                     

### Test Case 1: User Login
- **Test Case ID**: TC_AUTH_001
- **Description**: Verify that a user can log in with valid credentials                                                                   
- **Preconditions**: User must be registered.
- **Test Steps**:
  1. Navigate to the login page.
  2. Enter valid username and password.
  3. Click on the Login button.
- **Expected Results**: User should be redirected to the dashboard.

### Test Case 2: User Registration
- **Test Case ID**: TC_AUTH_002
- **Description**: Verify that a user can register with valid details
- **Preconditions**: None.
- **Test Steps**:
  1. Navigate to the registration page.
  2. Fill in all required fields.
  3. Click on the Register button.
- **Expected Results**: User should receive a confirmation message and be redirected to the login page.

## Feature Area: Product Management

### Test Case 3: Add Product to Cart
- **Test Case ID**: TC_PRODUCT_001
- **Description**: Verify that a user can add a product to the cart
- **Preconditions**: User must be logged in.
- **Test Steps**:
  1. Navigate to the product page.
  2. Click on the "Add to Cart" button.
- **Expected Results**: Product should be added to the cart successfully with a confirmation message.

### Test Case 4: Checkout Process
- **Test Case ID**: TC_PRODUCT_002
- **Description**: Verify that a user can complete the checkout process
- **Preconditions**: User must have items in the cart.
- **Test Steps**:
  1. Navigate to the cart page.
  2. Click on the "Checkout" button.
  3. Enter shipping and payment details.
  4. Confirm the order.
- **Expected Results**: User should receive an order confirmation message.

## Feature Area: Bug Reports

### Test Case 5: Verify Bug Fixes
- **Test Case ID**: TC_BUG_001
- **Description**: Ensure that reported bugs are fixed
- **Preconditions**: Bug fixes have been implemented.
- **Test Steps**:
  1. Navigate to the related feature.
  2. Execute the tests related to the reported bugs.
- **Expected Results**: No issues should be present for the fixed features.

---
<img width="778" height="371" alt="image" src="https://github.com/user-attachments/assets/28449fab-86c0-4baa-96b6-062e4190e76e" />

<img width="1177" height="436" alt="image" src="https://github.com/user-attachments/assets/3ec6a9a6-c0a1-4884-9f5f-9692dd29a333" />
<img width="1167" height="410" alt="image" src="https://github.com/user-attachments/assets/5af1f8d0-6531-462a-a42d-ecf9a6ab5fd0" />



*Note: This document is a living document and will be updated as new test cases are added or existing test cases are modified.*
