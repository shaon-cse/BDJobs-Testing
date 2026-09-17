# BDJobs-Testing
This repository contains Software Quality Assurance (SQA) testing documentation for the Bdjobs website. It includes test cases, test execution results, bug reports, mind maps, and screenshots. The project demonstrates practical skills in manual testing, test case design, defect reporting, and QA documentation.

---

## Modules Tested
- Create Account (Registration)
- Sign In (Login)

---

## Bug Findings

During testing, the following issues were identified on production:

| # | Module | Issue | Severity | Priority |
|---|--------|-------|----------|----------|
| 1 | Create Account | Invalid email format (e.g. `shaon@te`) is accepted and account is registered successfully instead of showing a validation error | Major | High |
| 2 | Sign In | Invalid email format is not validated at Sign In; instead of a format error, system shows "Couldn't find your Bdjobs Account!" | Minor | Medium |
| 3 | Sign In | Numeric-only usernames create ambiguity with mobile number lookups — entering a digit string matching an existing username fetches that account instead of validating it as an invalid mobile number | Minor (Suggestion) | Medium |
| 4 | Sign In | No account lockout or captcha triggered after 6–7 consecutive failed login attempts, posing a potential security/brute-force risk | Critical | High |

Full reproduction steps, screenshots, and expected vs. actual behavior for each issue are documented in the **Bug Report** sheet of `BDJobs-Testing.xlsx`.

---

## Project Files

### Testing Documentation
**File:** `BDJobs-Testing.xlsx`

This Excel file contains multiple QA artifacts organized into separate sheets:

- Test Plan
- Mind Map
- Test Case Scenarios
- Test Cases
- Test Summary Report
- Bug Report
- Test Metrics

---

### Additional Files

**Test Plan Document**  
`BDJobs-TestPlan.pdf`

**Mind Map Image**  
`Mind Map.png`

**Bug Screenshots**  
`BDJobs Bug Screenshot`

**Project Logo**  
`BDJobs Logo.png`

---

## Tools Used
- Microsoft Excel
- Manual Testing Techniques
- Mind Mapping Tool- XMind
- Browser Developer Tools
- Screenshot Documentation

---

## Repository Structure
