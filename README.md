# SDET / QA Portfolio Repository

## Overview

This repository is a **professional portfolio** demonstrating my approach to **quality engineering, test automation, and CI/CD integration** for a modern web-based SaaS application with REST APIs. It is structured to show recruiters and hiring managers my practical experience in both **manual and automated testing**, aligned with **UK QA Engineer / SDET expectations**.

---

## Repository Structure

```
├── README.md                   # Recruiter-optimized overview, executive summary, and instructions
├── Test_Strategy.pdf           # Full Test Strategy document
├── CI_CD_Workflow.md           # Sample CI/CD integration workflow
├── Automation_Pyramid.png      # Visual representation of automation focus
├── sample_test_cases/          # Example test cases
├── badges/                     # Optional: Status, coverage, or CI/CD badges
└── docs/                       # Optional: Additional diagrams, screenshots, or reference materials
```

---

## README.md Highlights

* **Executive Summary:** 1-page overview of QA approach, automation, and measurable outcomes
* **Automation Pyramid:** Visual of manual, API, and UI testing focus
* **How to Run Tests:** Sample commands for Playwright execution (PR validation, full regression, CI/CD headless)
* **Contact Info:** LinkedIn and email for recruiter follow-up

---

## CI/CD Workflow

* Integrates automated tests at **PR validation**, **nightly regression**, and **pre-production deployment**
* Supports **fast feedback**, **risk mitigation**, and **release confidence**
* Mermaid diagram included for visual clarity

---

## Automation Pyramid

* **Manual & Exploratory Testing:** Edge cases, usability, exploratory testing
* **API Tests:** Business logic, validation, contract tests
* **UI / E2E Tests:** Critical flows automated with Playwright

*Focus is primarily on API-level automation, with selective UI coverage.*

---

## How to Run Tests (Sample)

### Install Dependencies

```bash
npm install
```

### Run All Tests

```bash
npx playwright test
```

### Run Specific Test File

```bash
npx playwright test sample_test_cases/login.spec.ts
```

### Generate HTML Test Report

```bash
npx playwright show-report
```

### CI/CD Mode (Headless)

```bash
npx playwright test --headless --parallel --reporter=html
```

---

## Contact

* **LinkedIn:** [[LinkedIn](https://www.linkedin.com/in/ayesha78699/)]
* **Email:** [ayesha.uni.hudd@gmail.com]


