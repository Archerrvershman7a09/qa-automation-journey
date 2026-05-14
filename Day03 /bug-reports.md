# Day 03: Bug Reports for Login Feature

## Bug Report 1

**Title:** Error message is not displayed after login with invalid password

**Severity:** Medium

**Priority:** High

**Environment:**
- Browser: Chrome
- OS: Windows 10
- Page: Login page

**Steps to Reproduce:**
1. Open the login page.
2. Enter a valid email: valid_user@test.com
3. Enter an invalid password: wrongPassword123
4. Click the Login button.

**Expected Result:**
User should not be logged in. Error message should be displayed: "Invalid email or password."

**Actual Result:**
User is not logged in, but no error message is displayed.

**Attachments:**
Screenshot or screen recording should be attached if this issue is found during real testing.

---

## Bug Report 2

**Title:** User can click Login button when both email and password fields are empty

**Severity:** Low

**Priority:** Medium

**Environment:**
- Browser: Chrome
- OS: Windows 10
- Page: Login page

**Steps to Reproduce:**
1. Open the login page.
2. Leave the email field empty.
3. Leave the password field empty.
4. Click the Login button.

**Expected Result:**
Login button should be disabled or validation messages should appear:
- "Email is required"
- "Password is required"

**Actual Result:**
Login button is clickable, but no validation message is shown.

**Attachments:**
Screenshot or screen recording should be attached if this issue is found during real testing.
