# 🎯 Playwright Locator Reviewer

## Purpose

Review Playwright locators and recommend more reliable, maintainable alternatives.

---

## When to Use

Use this agent when:

- Tests are flaky
- Locators frequently fail
- Reviewing Pull Requests
- Improving automation stability

---

## Inputs

Playwright code containing locators.

---

## Outputs

- Stability score
- Suggested locator improvements
- Risk assessment
- Recommended Playwright locator

---

## Example Prompt

Review this locator:

page.locator("//div[2]/button[3]")

---

## Example AI Response

Current Locator:
XPath

Risk:
High

Suggested Locator:

page.getByRole("button", { name: "Login" })

Reason:
Role-based locators are more stable and readable.

---

## Best Practices

- Prefer getByRole().
- Use getByLabel() for form fields.
- Avoid nth().
- Minimize XPath usage.

---

## Limitations

- Cannot infer DOM changes without HTML.
- Some applications may require XPath.
