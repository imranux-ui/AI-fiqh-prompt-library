# Workflow: Daily QA Routine

**Type:** Repeatable daily loop  
**Steps:** 3  
**Estimated time:** 1–2 hours per module

---

## Overview

An intern-friendly daily system testing routine for any Fiqh Tech module — from checklist generation to clean bug reports for the dev team.

---

## When to Use

- Every working day before 10am (align with 9am–6pm working hours)
- After a new deployment or hotfix
- As part of a pre-release verification pass

---

## Step-by-Step

### Step 1 — Generate today's checklist
**Prompt to use:** `prompts/qa/daily-test-checklist.md`  
**Input:** Module name + environment (staging or production)  
**Output:** Markdown table checklist — print or keep open in a second window

---

### Step 2 — Run tests and log results
**No prompt needed — this is hands-on work.**

Work through each row of the checklist:
- Follow the test steps exactly as described
- Mark each row Pass ✅ or Fail ❌
- Add timestamped notes for anything unexpected
- Note device, browser, and environment for each failure

**Best practices:**
- Test on at least two devices/browsers where possible
- Pay special attention to Shariah-sensitive outputs (e.g. nisab values, halal/haram classifications) — verify against known correct values
- Screenshot failures immediately

---

### Step 3 — Write up bug reports
**Prompt to use:** `prompts/qa/bug-report-writer.md`  
**Input:** Each failed row from Step 2 (one report per unique bug)  
**Output:** Structured, developer-ready bug reports

**After generating:**
- Submit each report to the development team via the agreed channel (e.g. GitHub Issues, Jira, email)
- Save a copy in your daily testing log

---

## Daily Log Template

Keep a simple daily log entry:

```
Date: [DD/MM/YYYY]
Module tested: [name]
Environment: [staging / production]
Tester: [your name]
Tests run: [X]
Passed: [X]
Failed: [X]
Bug reports raised: [links or IDs]
Notes: [anything the dev team should know]
```
