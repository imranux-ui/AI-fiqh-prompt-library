# 🕌 Fiqh Tech — AI Prompt Workflow Library

> A curated prompt library built to support internship responsibilities at **Fiqh Tech**, a Shariah-compliant digital solutions company based in Salak Perdana, Sepang, Selangor.

---

## About

Fiqh Tech integrates technology and Islamic principles to deliver impactful solutions for businesses and communities. This library provides structured AI prompts and workflow chains for the four core intern responsibilities:

- **Social Media & Content** — Shariah-aligned posts, content calendars
- **Scheduling, Correspondence & Proposals** — emails, meeting prep, business proposals
- **Customer Support** — empathetic reply templates, FAQ builders
- **Daily System Testing** — QA checklists, structured bug reports

Each prompt is designed to be model-agnostic (works with Claude, GPT-4, Gemini, etc.) and uses `[placeholder]` markers that you fill in before running.

---

## Repository Structure

```
fiqhtech-prompt-library/
├── prompts/
│   ├── content/
│   │   ├── shariah-content-brief.md
│   │   └── content-calendar-generator.md
│   ├── correspondence/
│   │   ├── professional-email-drafter.md
│   │   └── business-proposal-outline.md
│   ├── support/
│   │   ├── support-response-generator.md
│   │   └── faq-knowledge-base-builder.md
│   └── qa/
│       ├── daily-test-checklist.md
│       └── bug-report-writer.md
├── workflows/
│   ├── product-launch-pipeline.md
│   ├── client-onboarding-workflow.md
│   └── daily-qa-routine.md
├── examples/
│   ├── example-content-brief-output.md
│   ├── example-bug-report-output.md
│   └── example-email-output.md
└── README.md
```

---

## How to Use

1. Browse to the relevant prompt file under `prompts/`
2. Copy the prompt template
3. Replace all `[placeholder]` sections with your specific context
4. Paste into your preferred AI assistant
5. For multi-step tasks, follow the matching workflow under `workflows/`

> **Tip:** The more specific your placeholder values, the sharper the output — especially for Shariah-sensitive content where nuance matters.

---

## Prompt Tags

| Tag | Meaning |
|-----|---------|
| `[Shariah]` | Output touches on Islamic principles — verify with a qualified scholar for rulings |
| `[Content]` | Social media or editorial output |
| `[Email]` | Correspondence output |
| `[QA]` | Quality assurance / testing output |
| `[Proposals]` | Business development output |
| `[Support]` | Customer-facing output |

---

## Contributing

New prompts can be added via pull request. Each prompt file should follow this structure:

```
# Prompt Title
**Category** | **Tags**

## Description
One-line explanation of what this prompt does.

## When to Use
Brief guidance on the scenario.

## Prompt Template
[The actual prompt with [placeholders]]

## Example Input
[A filled-in example]

## Expected Output Format
[Description of what good output looks like]
```

---

## Contact

Application submitted to **fiqhtech@aifiqh.com**  
📞 019 6490118  
📍 Salak Perdana, Sepang, Selangor
