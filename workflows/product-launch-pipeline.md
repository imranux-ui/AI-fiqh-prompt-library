# Workflow: Product Launch Content Pipeline

**Type:** Multi-step chain  
**Steps:** 4  
**Estimated time:** 30–45 minutes

---

## Overview

A 4-step prompt chain that takes you from internal product notes to a scheduled, multi-platform content plan — including a client announcement email.

---

## When to Use

- Launching a new Fiqh Tech product or feature
- Preparing a coordinated marketing push across platforms
- Ensuring Islamic calendar alignment for release timing

---

## Step-by-Step

### Step 1 — Summarise the feature
**Prompt to use:** `prompts/content/shariah-content-brief.md`  
**Input:** Internal product notes or feature spec  
**Output:** A plain-language, Shariah-framed feature summary (save this for step 2)

---

### Step 2 — Generate multi-platform posts
**Prompt to use:** `prompts/content/shariah-content-brief.md` (run twice)  
**Input:** Feature summary from Step 1  
**First run:** Set platform to LinkedIn  
**Second run:** Set platform to Instagram  
**Output:** Two adapted, platform-specific captions

---

### Step 3 — Schedule into content calendar
**Prompt to use:** `prompts/content/content-calendar-generator.md`  
**Input:** Current month + the two posts from Step 2  
**Output:** Updated monthly calendar with new posts slotted in, Islamic dates noted

---

### Step 4 — Draft client announcement email
**Prompt to use:** `prompts/correspondence/professional-email-drafter.md`  
**Input:** Feature summary from Step 1, recipient = existing client base  
**Purpose:** "Product launch announcement"  
**Output:** Ready-to-send email notifying clients of the new feature

---

## Chaining Tip

Copy the output of each step directly as context into the next prompt. Add a line like:  
> "Here is the feature summary from the previous step: [paste output]"

This keeps each prompt grounded in consistent messaging across all four outputs.
