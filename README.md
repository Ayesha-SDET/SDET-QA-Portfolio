# Sample Test Strategy – Web & API Application (Playwright, CI/CD)

## Executive Summary

This repository presents a **sample test strategy for a modern web-based SaaS application with supporting REST APIs**, reflecting a practical approach to **quality engineering and test automation**. It is designed to support **frequent, reliable releases** in Agile environments while ensuring high product quality.

### Key Principles
- Risk-based testing focused on **critical user journeys and business logic**
- Balanced **manual and automated testing** for efficiency and coverage
- **Shift-left quality**: QA involvement from early development to release
- Collaborative approach: QA embedded in cross-functional teams

### Tooling & Practices
- **Playwright** for UI and API automation
- JavaScript / TypeScript-based test framework
- Integrated into **CI/CD pipelines** for fast, reliable feedback
- End-to-end defect lifecycle management and traceability

### Measurable Outcomes
- Increased automated test coverage by **25–30%**
- Reduced regression execution time by **~40%**
- Improved early defect detection and overall release confidence

---

## Repository Structure

```
├── README.md                   # This document
├── Test_Strategy.pdf           # Full Test Strategy document
├── Automation_Pyramid.png      # Visual representation of automation focus
├── sample_test_cases/          # Example test cases
└── CI_CD_Workflow.md           # Sample CI/CD integration overview
```

---

## Automation Pyramid

```
                ┌───────────────────────┐
                │     UI / E2E Tests     │
                │   (Playwright - Key    │
                │    User Journeys)      │
                └───────────▲───────────┘
                            │
            ┌────────────────────────────────┐
            │          API Tests              │
            │   (Business Logic, Validation,  │
            │    Error Handling)               │
            └───────────────▲────────────────┘
                            │
        ┌────────────────────────────────────────┐
        │        Manual & Exploratory Testing     │
        │   (Usability, Edge Cases, Risk Areas)  │
        └────────────────────────────────────────┘
```
*Automation is focused primarily at the API level, with UI automation targeting critical user journeys.*

---

## How to Use This Repository

1. Review the **Test_Strategy.pdf** to understand the testing approach, scope, and automation strategy.
2. See **sample_test_cases/** for example manual and automated tests.
3. Refer to **CI_CD_Workflow.md** for a conceptual overview of pipeline integration.
4. View **Automation_Pyramid.png** for a visual summary of testing priorities.

---

## How to Run Tests

This section demonstrates how automated tests could be executed in a Playwright-based framework, giving recruiters a **hands-on feel** of an SDET project.

### 1. Install Dependencies
```bash
npm install
```

### 2. Run All Tests
```bash
npx playwright test
```

### 3. Run a Specific Test File
```bash
npx playwright test sample_test_cases/login.spec.ts
```

### 4. Generate HTML Test Report
```bash
npx playwright show-report
```

### 5. Run Tests in CI/CD Mode (Headless)
```bash
npx playwright test --headless --reporter=html
```

> These commands simulate a realistic SDET workflow and demonstrate integration with CI/CD pipelines, giving recruiters confidence in your automation skills.

---

## Purpose & Audience

This repository is intended as a **professional portfolio piece** to demonstrate:
- Expertise in **manual and automated testing**
- Experience with **Playwright and CI/CD integration**
- Ability to define **test strategies and risk-based approaches**
- Alignment with **UK QA Engineer and SDET expectations**

---

## Contact

For inquiries or opportunities, please connect via LinkedIn or email:
- **LinkedIn:** [https://www.linkedin.com/in/ayesha78699/]
- **Email:** [ayesha.uni.hudd@gmail.com]
