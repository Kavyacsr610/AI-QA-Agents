# 🧪 Test Case Generator Agent

## Purpose

Generate comprehensive software test cases from business requirements, user stories, or acceptance criteria.

---

## When to Use

Use this agent when:

- A new feature is developed
- User stories need test cases
- Regression test cases are required
- Smoke test cases need to be prepared

---

## Inputs

- User Story
- Requirement Document
- Acceptance Criteria
- Feature Description

Example:

"As a user, I should be able to login using email and password."

---

## Outputs

The agent generates:

- Positive Test Cases
- Negative Test Cases
- Boundary Value Test Cases
- Edge Cases
- Test Data Suggestions
- Expected Results

---

## Example Prompt

Generate test cases for the following requirement:

"As a user, I should be able to login using email and password."

---

## Example AI Response

### Positive Test Case

Login with valid username and password.

Expected Result:
User is redirected to the Dashboard.

### Negative Test Case

Login with invalid password.

Expected Result:
Display "Invalid Credentials".

### Boundary Test

Password length = minimum allowed characters.

Expected Result:
Login succeeds.

---

## Best Practices

- Provide complete requirements.
- Include business rules.
- Mention validation rules.
- Specify supported browsers if UI-specific.

---

## Limitations

- Cannot replace manual requirement analysis.
- May miss hidden business logic.
- Depends on the quality of the input requirement.
