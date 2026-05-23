# SeleniumLens_test_Script_analyzer
A tool for QA engineers to analyze Selenium test scripts for issues in locators, timing, naming, structure, and best practices.

## Features

- 🎯 **Fragile locator detection** — Identifies brittle XPaths and suggests stable alternatives
- ⏱ **Timing issues** — Flags Thread.sleep and missing explicit waits
- ✏️ **Naming violations** — Catches poor method/variable names
- 🏗 **Structural analysis** — Recommends Page Object Model patterns
- ✓ **Assertion gaps** — Detects missing or weak assertions  
- ⭐ **Best practices** — General Selenium anti-pattern detection
- 📊 **Quality score** — A–F grading with 0–100 score
- ✏️ **Suggestions** - suggestion improvements
- ✏️ **Refactored code**- Code refactoring

## Setup

### 1. Install dependencies
```bash
npm install
```

### 2. Set up your OpenAI API key

Create a `.env.local` file:
```
create a API key from OpenAI API and place it this file
```


### 3. Run locally
```bash
npm run dev
```

## Tech Stack
- React 18 + Vite
- ChatGPT API
- Pure CSS (no UI library)
- Vercel for deployment
