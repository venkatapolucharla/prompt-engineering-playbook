# 🎭 Playwright + AI Testing Prompts

This section demonstrates how AI can be used to generate, optimize, and validate Playwright test automation.

---

## 🔹 1. Test Case Generator Prompt

### Prompt

"Act as a QA automation engineer. Generate Playwright test cases for the following scenario:

Scenario: {login page functionality}

Include:

* Positive test cases
* Negative test cases
* Edge cases
* Use Playwright (JavaScript)"

---

### Example Output

```javascript
import { test, expect } from '@playwright/test';

test('valid login', async ({ page }) => {
  await page.goto('https://example.com');
  await page.fill('#username', 'user');
  await page.fill('#password', 'pass');
  await page.click('#login');
  await expect(page).toHaveURL('/dashboard');
});
```

---

## 🔹 2. Test Script Generator Prompt

### Prompt

"Convert the following manual test steps into a Playwright automation script:

Steps:

1. Open browser
2. Navigate to login page
3. Enter credentials
4. Click login
5. Verify dashboard"

---

### Value

* Converts manual QA → automation instantly
* Saves hours of scripting

---

## 🔹 3. Locator Optimization Prompt

### Prompt

"Improve the following Playwright locators to make them stable and less flaky:

Locator:
page.locator('//div[3]/span[2]')"

---

### Expected Output

* Use data-testid
* Use role-based selectors
* Avoid XPath indexing

---

## 🔹 4. Debugging Prompt (🔥 High Value)

### Prompt

"My Playwright test is failing with this error:

Error: Timeout 30000ms exceeded

Here is my code:
{paste code}

Analyze step-by-step and suggest a fix."

---

### Value

* AI acts like senior QA
* Reduces debugging time drastically

---

## 🔹 5. Test Data Generator Prompt

### Prompt

"Generate realistic test data for:

* Email
* Password
* Invalid inputs
* Boundary values"

---

---

## 🔹 6. API Testing Prompt (Playwright)

### Prompt

"Write Playwright API tests for:

Endpoint: /api/login
Method: POST

Validate:

* Status code
* Response body
* Error handling"

---

---

## 🔹 7. Cross-Browser Testing Prompt

### Prompt

"Modify this Playwright test to run across:

* Chromium
* Firefox
* WebKit

Ensure compatibility and stability."

---

---

## 🔹 8. Performance Testing Prompt

### Prompt

"Analyze this Playwright script and suggest improvements to:

* Reduce execution time
* Improve parallel execution
* Optimize waits"

---

---

## 🔹 9. AI Test Review Prompt (🔥 Recruiter Favorite)

### Prompt

"Review the following Playwright test script as a senior QA engineer:

Check for:

* Best practices
* Flaky tests
* Code quality
* Missing assertions"

---

---

## 🔹 10. CI/CD Integration Prompt

### Prompt

"Generate a GitHub Actions workflow to run Playwright tests on every commit.

Include:

* Install dependencies
* Run tests
* Upload reports"

---

---

# 📊 Real Proof Section (Add This 🔥)

## Before AI

* Manual test writing: 2 hours
* Debugging time: High

## After AI

* Test generation: 5 minutes
* Debugging: Faster with AI suggestions

---

# 🧠 Skills Demonstrated

* Playwright Automation
* AI-Assisted Testing
* Prompt Engineering for QA
* Test Optimization

---

# ⭐ Why This Matters

This shows:
✔ You don’t just write tests
✔ You **accelerate testing using AI**
✔ You think like a **modern QA engineer**

---
