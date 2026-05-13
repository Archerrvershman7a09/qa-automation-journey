# STLC Example: Login Feature

## Project Example
A web application has a login feature. The user should be able to enter email and password and access the dashboard.

## 1. Requirement Analysis
QA reads the requirements and checks if they are clear.

Example requirements:
- User can log in with valid email and password
- User cannot log in with invalid password
- Empty email or password should show validation message
- After successful login, user is redirected to dashboard

Possible questions:
- What message should appear for invalid login?
- Should the account be locked after several failed attempts?
- Is email case-sensitive?
- What happens if the user is already logged in?

## 2. Test Planning
QA decides what will be tested:
- Positive login flow
- Negative login flow
- Empty fields
- Invalid email format
- Wrong password
- Redirect after successful login

## 3. Test Case Design
QA writes test cases.

Example:
- Verify login with valid credentials
- Verify login with invalid password
- Verify login with empty email field
- Verify login with empty password field
- Verify validation message for invalid email format

## 4. Test Environment Setup
QA prepares:
- Test user account
- Browser
- Test environment URL
- Test data

## 5. Test Execution
QA executes test cases and compares actual results with expected results.

## 6. Defect Reporting
If something does not work correctly, QA creates a bug report with:
- Title
- Steps to reproduce
- Expected result
- Actual result
- Severity
- Screenshot or video

## 7. Test Closure
QA summarizes what was tested, which bugs were found, which bugs were fixed, and whether the feature is ready for release.
