# SeleniumLens

AI-Powered Selenium Test Quality Analyzer

---

## Overview

SeleniumLens is a hybrid Selenium test quality analysis platform designed to evaluate the quality, maintainability, stability, and reliability of Selenium automation scripts.

The system combines:

- Static Analysis
- AI-Based Analysis
- Quality Metric Evaluation
- Refactoring Suggestions

to provide intelligent insights into Selenium test automation quality.

---

# Key Features

## Static Analysis

Detects common Selenium anti-patterns such as:

- `Thread.sleep()`
- Absolute XPath locators
- Basic synchronization risks

---

## AI-Powered Analysis

Uses OpenAI API to perform intelligent analysis of Selenium test scripts.

The AI module can:

- Detect advanced issues
- Classify issue severity
- Generate recommendations
- Suggest refactoring improvements

---

## Quality Metrics Engine

Computes multiple quality indicators including:

- Maintainability
- Stability Score
- Flakiness Risk
- Technical Debt
- Complexity

---

## SLQI (SeleniumLens Quality Index)

Generates an overall quality score using weighted metric evaluation.

---

## Refactoring Suggestions

Automatically generates improved Selenium code suggestions including:

- Explicit waits
- Improved locator strategies
- Better test practices

---

## Interactive Dashboard

Displays:

- Quality score
- Grade
- Issues detected
- Metrics
- Refactored code
- Suggestions

through a clean user interface.

---

# Technologies Used

## Frontend

- React
- Vite
- CSS

---

## Backend

- Node.js
- Vercel Serverless Functions

---

## AI

- OpenAI API
- GPT-4.1 Nano

---

## Software Engineering Concepts

- Static Analysis
- Hybrid Analysis
- Quality Metric Modeling
- Rule-Based Detection
- AI-Assisted Code Analysis

---

# System Workflow

1. User uploads Selenium test script
2. Static analysis is performed
3. Quality metrics are calculated
4. Script is sent to OpenAI API
5. AI analysis is generated
6. Results are aggregated
7. SLQI score is computed
8. Dashboard displays final results

---

# Detected Issue Categories

SeleniumLens detects issues related to:

- Timing Problems
- Locator Issues
- Maintainability Problems
- Stability Risks
- Complexity Concerns
- Selenium Best-Practice Violations

---

# Project Architecture

```text
Selenium Script
       ↓
Static Analysis + AI Analysis + Metrics
       ↓
Result Aggregation
       ↓
SLQI Calculation
       ↓
Interactive Dashboard
