# Bug Report

| Bug ID  | Module       | Summary                                                         | Severity | Priority | Environment       | Status      | Assigned To |
| ------- | ------------ | --------------------------------------------------------------- | -------- | -------- | ----------------- | ----------- | ----------- |
| BUG_001 | Login        | Login button accepts multiple clicks causing duplicate requests | Medium   | High     | UAT - Chrome 137  | Open        | Dev Team    |
| BUG_002 | Registration | Email validation allows invalid formats                         | Low      | Medium   | UAT - Firefox 140 | Fixed       | Dev Team    |
| BUG_003 | Checkout     | Payment page crashes on invalid coupon code                     | Critical | High     | Production        | In Progress | Dev Team    |

---

## BUG_001 Details

**Title:** Login button remains enabled after multiple clicks

**Steps to Reproduce:**

1. Open the application.
2. Enter valid credentials.
3. Click the Login button multiple times quickly.

**Expected Result:**
The Login button should be disabled after the first click.

**Actual Result:**
Multiple API requests are triggered.

**Severity:** Medium

**Priority:** High

**Attachments:** Screenshot_Login_001.png
