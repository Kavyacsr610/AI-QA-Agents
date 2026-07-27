# 🐞 Bug Report Generator

## Purpose

Generate standardized bug reports from defect descriptions.

---

## When to Use

- During defect reporting
- Sprint testing
- UAT testing
- Regression failures

---

## Inputs

- Bug description
- Steps performed
- Environment
- Browser
- Expected Result
- Actual Result

---

## Outputs

- Bug Title
- Severity
- Priority
- Steps to Reproduce
- Expected Result
- Actual Result
- Attachments
- Suggested Root Cause

---

## Example Prompt

Generate a bug report.

Login button is disabled after entering valid credentials.

---

## Example AI Response

Title:
Login button remains disabled.

Severity:
High

Priority:
High

Steps:

1. Open Login Page.
2. Enter valid username.
3. Enter valid password.
4. Observe Login button.

Expected:
Button should be enabled.

Actual:
Button remains disabled.

---

## Best Practices

- Include screenshots.
- Mention browser version.
- Include environment.

---

## Limitations

- Cannot verify if the issue is reproducible.
- Severity recommendations may require human review.
