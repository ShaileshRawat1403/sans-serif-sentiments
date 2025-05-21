---
permalink: /STYLE-GUIDE/
---

# 🎨 Style Guide for sans-serif-sentiments

**Version 1.0 • 2025-05-19**

_A living framework for calm, clear, human-first documentation._

## 📑 Table of Contents

1. [Purpose of This Guide](#purpose-of-this-guide)  
2. [Tone & Voice](#tone--voice)  
3. [Structure & Hierarchy](#structure--hierarchy)  
4. [Emphasis Rules](#emphasis-rules)  
5. [Language & Word Choice](#language--word-choice)  
6. [Layout Patterns](#layout-patterns)  
7. [Content Philosophy](#content-philosophy)  
8. [Markdown & Commit Style](#markdown--commit-style)  
9. [Accessibility & Inclusivity](#accessibility--inclusivity)  
10. [Localization & Translation](#localization--translation)  
11. [Linking & Cross-Referencing](#linking--cross-referencing)  
12. [Code & Command Snippets](#code--command-snippets)  
13. [Admonitions & Callouts](#admonitions--callouts)  
14. [Asset Management](#asset-management)  
15. [Tables, Lists & Layouts](#tables-lists--layouts)  
16. [Terminology & Glossary](#terminology--glossary)  
17. [Doc Versioning & Changelogs](#doc-versioning--changelogs)  
18. [Review & Feedback Process](#review--feedback-process)  
19. [Automation & Tooling](#automation--tooling)  
20. [SEO & Discoverability](#seo--discoverability)  
21. [Living Documentation](#living-documentation)  
22. [AI-Assisted Writing](#ai-assisted-writing)  
23. [Multi-Format Output](#multi-format-output)  
24. [Evolution Rules](#evolution-rules)

---

---

## 1. Purpose of This Guide

> A style guide is not just about formatting—it's about trust.  
> This document exists to create a **shared voice**, a **clear standard**, and a **reliable starting point** for anyone contributing to sans-serif-sentiments.

You can use this guide when:
- You're writing docs, READMEs, guides, or changelogs
- You're reviewing someone else’s writing
- You’re rewriting dry tech speak into something more human

This isn’t about rules. It’s about rhythm.

---

## 2. Tone & Voice  
_Calm, clear, sincere—never robotic._

Your writing should feel like a conversation with someone who’s:
- Confident but not arrogant
- Knowledgeable but not preachy
- Friendly but not trying too hard

### 🎯 What We Aim For

| Trait     | What It Means                          |
|-----------|-----------------------------------------|
| **Calm**  | No over-explaining. No panic. No exclamation marks unless they earn it. |
| **Clear** | Say what you mean. Cut half your words—if it still works, it’s better. |
| **Sincere** | Be helpful, not hypey. Avoid jargon, sarcasm, or corporate filler. |
| **Minimal** | Don’t write a sentence when a phrase will do. Let whitespace speak. |
| **Human** | We talk like real people. Write like someone who wants to be understood. |

---

### ❌ Cold, Robotic
```markdown
To proceed with installation, users are advised to verify system prerequisites prior to continuing.
```

### ✅ Calm + Human
```markdown
Before you install, check if your system meets the requirements.  
It takes 30 seconds and saves frustration later.
```

---

### ❌ Corporate & Vague
```markdown
Our platform leverages AI capabilities to enhance synergies across verticals.
```

### ✅ Sincere + Clear
```markdown
We use AI to help teams work faster and with fewer manual tasks.
```

---

### ❌ Friendly but Overdone
```markdown
Hey there, champ! 😎 Ready to install some software?! Let’s crush it! 💥
```

### ✅ Friendly and Respectful
```markdown
Let’s get you set up. This guide takes about 3 minutes to follow.
```

---

> Write like you're helping someone intelligent—but tired.  
> That’s the reader who matters most.

---

## 3. Structure & Hierarchy  
_When and how to use headings and whitespace._

### 🧱 Use heading levels to guide the eye:

| Markdown | Purpose |
|----------|---------|
| `#` H1   | Page title (only once per doc) |
| `##` H2  | Major sections |
| `###` H3 | Subsections within an H2 |
| `####` H4 | Rarely used—only if absolutely needed |

✅ Always keep 1 blank line **before** and **after** headings.

---

### 🧼 Use whitespace like punctuation

- One thought = one paragraph  
- Use bullets or tables instead of dense text  
- Group related content with clear spacing

> If it looks dense, it reads dense.

---

## 4. Emphasis Rules  
_Use emphasis to guide—not distract._

Use `**bold**` and `*italic*` intentionally. Don’t shout. Don’t decorate.

| Use case | Style |
|----------|-------|
| Highlight a key term | `**bold**` |
| Add nuance or light stress | `*italic*` |
| Reference file/code | `` `inline code` `` |
| Technical snippets/output | Triple backticks (```bash) |

---

### ❌ Overdone & Distracting
```markdown
**IMPORTANT**: You MUST click the **FINAL** button at the **END** of the page.
```

### ✅ Balanced and Focused
```markdown
Click the **Final** button at the end of the page.  
This step completes the setup.
```

---

### ❌ Emphasizing full sentences
```markdown
**You should always check the version before upgrading.**
```

### ✅ Use emphasis *within* the sentence
```markdown
You should always check the **version** before upgrading.
```

> ✅ Let emphasis **support meaning**—not add noise.

---

## 5. Language & Word Choice  
_Preferred words, banned jargon._

### ✅ Use simple, common words:
| Bad | Better |
|-----|--------|
| Utilize | Use |
| Leverage (as a verb) | Apply, use |
| Facilitate | Help |
| Navigate to | Go to |
| Interface (as noun) | Screen, page, dashboard |
| In order to | To |

### ❌ Avoid these patterns:
- "It is recommended that…" → say “We recommend…”  
- “At your earliest convenience…” → say “When you’re ready”  
- “Endeavor to…” → just… don’t.

---

### ❌ Vague, bloated
```markdown
Our solution facilitates synergistic workflows across multiple platforms.
```

### ✅ Specific, human
```markdown
Our tool helps teams work together across different apps—without switching tabs.
```
---

### ❌ Legalese-style
```markdown
Users are advised to initiate credential verification upon initial login.
```

### ✅ Human-first
```markdown
When you log in for the first time, we’ll ask you to verify your account.
```

> Write like you're helping a smart friend, not submitting to a legal department.

---

## 6. Layout Patterns  
_Common structures for different doc types._

Use these reusable layouts to speed up writing and bring consistency across docs.

### 📦 Setup Guide

```markdown
## Getting Started

> What this guide helps you do in under 5 minutes.

### Step 1: Install XYZ  
Brief one-line description.

### Step 2: Configure XYZ  
Break it into 2–3 bullets if needed.

### Step 3: Verify  
Show how success looks.
```

---

### 📘 How-To Guide

```markdown
## How to Do One Specific Thing

> What this does and why it’s useful.

1. Step 1  
2. Step 2  
3. Step 3

✅ Result: What the user should see or achieve.
```

---

### 🧠 Concept/Overview Doc

```markdown
## What is [Concept]?

> Short, calm, non-salesy definition

- Why it matters  
- Where it fits in  
- When to use it
```

> ✨ These aren’t strict templates. Think of them as scaffolding—there to support you, not box you in.

---

## 7. Markdown & Commit Style  
_The backbone of formatting clarity._

### ✅ Markdown Guidelines

| Task | Rule |
|------|------|
| Code blocks | Use triple backticks: \`\`\`bash |
| Inline code | Use backticks: \`filename.txt\` |
| Headings | One `#` per level, no skipping |
| Lists | Use `-` or numbered lists (avoid asterisks) |
| Links | Use `[text](url)` syntax—no raw URLs |

✅ Always use one blank line between headings, paragraphs, and list items.

---

### ✅ Commit Message Style

We use conventional commit prefixes for clarity and changelogs:

```bash
feat: add onboarding checklist template
fix: resolve broken anchor link in API doc
docs: rewrite intro paragraph for tone
refactor: reorganize folder structure
chore: update dependencies
```

✅ Keep commit messages under 72 characters in subject line.  
✅ Use present tense (“add”, not “added”).

---

## 8. Accessibility & Inclusivity  
_Write for all brains, eyes, and contexts._

| Element | Best Practice |
|--------|---------------|
| **Images** | Always add alt text (`![desc](img.png)`) |
| **Links** | Avoid "click here" — use descriptive text |
| **Headings** | Use in order (H2 → H3 → H4) for screen readers |
| **Contrast** | Ensure visuals are readable in light/dark modes |
| **Tone** | Avoid gendered, biased, or culture-specific language |

✅ Use tools like [Hemingway](https://hemingwayapp.com/) or [Grammarly](https://grammarly.com) to keep writing clean and readable.

---

## 9. Linking & Cross-Referencing  
_Teaching users how to navigate like pros._

| Type | Format |
|------|--------|
| Same page | `[Go here](#section-name)` |
| Another file | `[Style Guide](../STYLE-GUIDE/STYLE-GUIDE.md)` |
| External site | `[GitHub](https://github.com)` |

✅ Always test your links.  
✅ Don’t link full sentences—keep it clean.  
✅ Use consistent casing in anchor links (`#like-this`, not `#Like-This`).

---

## 10. Code & Command Snippets  
_Highlight with clarity, not clutter._

| Rule | Example |
|------|---------|
| Triple backticks | \`\`\`bash |
| Label your language | `bash`, `json`, `html`, `js`, etc. |
| Keep commands copyable | No `$` in front of terminal code |
| Highlight results when helpful | Show example output or success message |
| Use inline for filenames and flags | `` `README.md` ``, `` `--verbose` `` |

> 🧠 Use code like it's a diagram: clean, meaningful, and visually distinct.

---



## Structure & Hierarchy
_When and how to use headings and whitespace._

## Emphasis Rules
_`**bold**` vs `*italic*`._

## Language & Word Choice
_Preferred words, banned jargon._

## Layout Patterns
_Templates for quickstarts, APIs, error docs._

## Content Philosophy
_Empathy-led, human-first writing._

## Markdown & Commit Style
_Your personal conventional-commit prefixes._

## Accessibility & Inclusivity
_Alt-text, plain language, ARIA considerations._

## Localization & Translation
_Placeholder syntax and tone shifts._

## Linking & Cross-Referencing
_Anchors, footnotes, citation formats._

## Code & Command Snippets
_Block vs inline, labels, prompt styling._

## Admonitions & Callouts
_⚠️ warnings, 💡 tips, ✅ examples._

## Asset Management
_Folder conventions, image specs._

## Tables, Lists & Layouts
_When to use which._

## Terminology & Glossary
_Define and link key terms._

## Doc Versioning & Changelogs
_Semantic versions and CHANGELOG.md._

## Review & Feedback Process
_How to propose and merge changes._

## Automation & Tooling
_Linting, CI checks, hooks._

## SEO & Discoverability
_Slugs, meta-tags, front-matter._

## Living Documentation
_Review schedules and archival policy._

## AI-Assisted Writing
_Guidance on safe AI use._

## Multi-Format Output
_PDF, slides, video scripts._

## Evolution Rules
_How and when to update this guide._

---
