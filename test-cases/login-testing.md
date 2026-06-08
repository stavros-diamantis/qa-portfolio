# Login Test Cases — saucedemo.com

## TC-001 — Successful login with valid credentials

- **Preconditions:** User is on the login page
- **Steps:**
  1. Enter username: `standard_user`
  2. Enter password: `secret_sauce`
  3. Click "Login"
- **Expected Result:** User is redirected to the products page
- **Actual Result:** User is redirected to the products page
- **Status:** ✅ Pass

## TC-002 — Login with invalid username

- **Preconditions:** User is on the login page
- **Steps:**
  1. Enter username: `wrong_user`
  2. Enter password: `secret_sauce`
  3. Click "Login"
- **Expected Result:** Error message is displayed
- **Actual Result:** "Epic sadface: Username and password do not match any user in this service"
- **Status:** ✅ Pass

## TC-003 — Login with invalid password

- **Preconditions:** User is on the login page
- **Steps:**
  1. Enter username: `standard_user`
  2. Enter password: `wrong_password`
  3. Click "Login"
- **Expected Result:** Error message is displayed
- **Actual Result:** "Epic sadface: Username and password do not match any user in this service"
- **Status:** ✅ Pass

## TC-004 — Login with both fields incorrect

- **Preconditions:** User is on the login page
- **Steps:**
  1. Enter username: `wrong_user`
  2. Enter password: `wrong_password`
  3. Click "Login"
- **Expected Result:** Error message is displayed
- **Actual Result:** "Epic sadface: Username and password do not match any user in this service"
- **Status:** ✅ Pass

## TC-005 — Login with empty fields

- **Preconditions:** User is on the login page
- **Steps:**
  1. Leave username empty
  2. Leave password empty
  3. Click "Login"
- **Expected Result:** Error message is displayed
- **Actual Result:** "Epic sadface: Username is required"
- **Status:** ✅ Pass
