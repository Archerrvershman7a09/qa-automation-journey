## Day02: QA / SDLC / STLC Theory

## 1. What is SDLC?

SDLC means Software Development Life Cycle.

It is the full process of creating and maintaining software. It starts from the idea or business need and continues through planning, design, development, testing, deployment, and maintenance.

Main SDLC phases:

1. Planning
2. Design
3. Development
4. Testing
5. Deployment
6. Maintenance

## 2. QA Role in SDLC

QA is important in every phase of SDLC.

### Planning
QA helps understand the product goal, possible risks, and quality expectations.

### Design
QA reviews requirements, user flows, and possible edge cases. QA can notice unclear or missing requirements before development starts.

### Development
QA prepares test cases, test data, and test scenarios while developers write code.

### Testing
QA executes test cases, reports bugs, verifies fixes, and performs regression testing.

### Deployment
QA performs smoke testing to check that the main functionality works after release.

### Maintenance
QA tests bug fixes, new features, and possible side effects after updates.

## 3. What is STLC?

STLC means Software Testing Life Cycle.

It describes the testing process from requirement analysis to test closure.

Main STLC phases:

1. Requirement Analysis
2. Test Planning
3. Test Design
4. Test Execution
5. Test Closure

## 4. Test Levels

Test levels show where testing happens in the system.

### Unit Testing
Testing a small part of code, usually one function or method.

### Integration Testing
Testing how different modules or services work together.

### System Testing
Testing the complete application as one full system.

### UAT
User Acceptance Testing checks if the product meets business and user needs.

## 5. Test Types

Test types show what kind of testing is performed and why.

### Smoke Testing
A quick check that the main functionality works.

### Regression Testing
Testing to make sure new changes did not break existing functionality.

### E2E Testing
Testing a full user flow from start to finish.

### Functional Testing
Checking that a feature works according to requirements.

## 6. Test Levels vs Test Types

Test Level answers the question: "Where do we test?"

Test Type answers the question: "What kind of testing do we perform and why?"

Example:

For a login feature:
- Unit Testing can check the password validation function.
- Integration Testing can check login API + database.
- System Testing can check login inside the full application.
- UAT can check if login is acceptable for real users.

At the same time:
- Smoke Testing can quickly check if login works after deployment.
- Regression Testing can check that login was not broken after a new release.
- E2E Testing can check the full flow: open website → login → go to dashboard → logout.
