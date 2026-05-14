# Day 03: Test Cases for Login Feature

## Feature: Login

Project example: E-commerce website login page.

The user should be able to log in with valid credentials and should see clear validation messages when login data is invalid.

---

## Test Case 1: Successful login with valid credentials

**Type:** Positive test

**Title:** Verify that user can log in with valid email and valid password

**Prerequisites:**
- User is registered
- User is on the login page
- Test account exists

**Test Data:**
- Email: valid_user@test.com
- Password: CorrectPassword123

**Steps:**
1. Open the login page.
2. Enter valid email.
3. Enter valid password.
4. Click the Login button.

**Expected Result:**
User is successfully logged in and redirected to the account/dashboard page.

**Actual Result:**
Not executed yet.

**Status:**
Not executed

---

## Test Case 2: Login with invalid password

**Type:** Negative test

**Title:** Verify that user cannot log in with invalid password

**Prerequisites:**
- User is registered
- User is on the login page

**Test Data:**
- Email: valid_user@test.com
- Password: wrongPassword123

**Steps:**
1. Open the login page.
2. Enter valid email.
3. Enter invalid password.
4. Click the Login button.

**Expected Result:**
User is not logged in. Error message is displayed: "Invalid email or password."

**Actual Result:**
Not executed yet.

**Status:**
Not executed

---

## Test Case 3: Login with empty email field

**Type:** Negative test

**Title:** Verify validation message when email field is empty

**Prerequisites:**
- User is on the login page

**Test Data:**
- Email: empty
- Password: CorrectPassword123

**Steps:**
1. Open the login page.
2. Leave the email field empty.
3. Enter valid password.
4. Click the Login button.

**Expected Result:**
User is not logged in. Validation message is displayed: "Email is required."

**Actual Result:**
Not executed yet.

**Status:**
Not executed

---

## Test Case 4: Login with empty password field

**Type:** Negative test

**Title:** Verify validation message when password field is empty

**Prerequisites:**
- User is on the login page

**Test Data:**
- Email: valid_user@test.com
- Password: empty

**Steps:**
1. Open the login page.
2. Enter valid email.
3. Leave the password field empty.
4. Click the Login button.

**Expected Result:**
User is not logged in. Validation message is displayed: "Password is required."

**Actual Result:**
Not executed yet.

**Status:**
Not executed

---

## Test Case 5: Login with invalid email format

**Type:** Negative test

**Title:** Verify validation message when email format is invalid

**Prerequisites:**
- User is on the login page

**Test Data:**
- Email: invalidemail
- Password: CorrectPassword123

**Steps:**
1. Open the login page.
2. Enter invalid email format.
3. Enter valid password.
4. Click the Login button.

**Expected Result:**
User is not logged in. Validation message is displayed: "Please enter a valid email address."

**Actual Result:**
Not executed yet.

**Status:**
Not executed
