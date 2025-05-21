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

Your doc should feel like a conversation with chapters—not a cluttered note.

---

### 📐 Use heading levels to guide the eye:

| Markdown | Purpose |
|----------|---------|
| `#` H1   | Title of the page (only once per doc) |
| `##` H2  | Major sections |
| `###` H3 | Subsections under an H2 |
| `####` H4 | Rarely needed—only for edge-case nesting |

✅ Use **1 blank line** before and after headings.  
✅ Start each section with a quick sentence or blockquote for orientation.

---

### ❌ Cluttered Heading Use
```markdown
# How it Works
## Setup
### Token
#### Details
### Login
### Interface
```

### ✅ Clear Hierarchy
```markdown
# How It Works

## 1. Setup

### Generate a Token  
Explain what it does and why it’s needed.

### Log In  
Describe what users should expect.

## 2. Using the Interface  
Quick intro before listing features.
```

---

## 📏 Whitespace = Breathing Room

Use whitespace like punctuation. It slows the scroll and helps the eye.

---

### ❌ Wall of Text
```markdown
To install the CLI tool, go to the website and download the installer. After that, run the installer and follow the setup wizard. Finally, verify the installation by typing `tool --version` in the terminal.
```

### ✅ Structured & Skimmable
```markdown
### Install the CLI Tool

1. Go to the [Downloads page](#)
2. Run the installer
3. Follow the setup wizard

✅ To confirm it worked:
```bash
tool --version
```
```

---

> ✅ Structure isn’t just for looks. It tells the reader:  
> “You’re in good hands. Keep going.”

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

## 7. Content Philosophy  
_Empathy-led, human-first writing._

We don’t write to look smart.  
We write so the reader doesn’t have to feel stupid.

This guide exists to protect that principle.

---

### 💭 Why This Philosophy Matters

Documentation is the *first real conversation* between your product and your user.  
If that conversation is cold, robotic, or overloaded—they walk away.

---

### 🎯 What We Believe

| Principle | What It Means |
|----------|----------------|
| **Writing is a product** | Docs are part of the experience—not an afterthought |
| **Clarity is kindness** | Confusion costs time. Clarity creates momentum |
| **Brevity isn’t the goal—clarity is** | Sometimes more words are needed to say it simply |
| **Anticipation builds trust** | Predict what might confuse the reader—and address it before they ask |
| **Tone is UX** | A friendly line at the right time does more than a button ever can |

---

### ❌ A Typical, Surface-Level Doc
```markdown
The installation process requires you to download the binary, extract it, and modify your PATH variable accordingly.
```

### ✅ A Human-First Rewrite
```markdown
To install the tool:

1. Download the `.zip` file
2. Extract it to any folder
3. Add that folder to your system PATH (here’s how →)

Not sure what "PATH" means? No worries—[we’ll explain it here](#what-is-path).
```

> 🤝 Help before it’s asked for. Confidence before confusion.

---

### ❌ Corporate Legalese
```markdown
This integration utilizes proprietary methods to ensure optimal connectivity across environments.
```

### ✅ Sans-Serif Sentiments Style
```markdown
We built this integration to be reliable, fast, and easy to connect—no matter your environment.
```

> Say it like you’d say it in real life. Not like you’re talking to a boardroom.

---

## ✅ TL;DR

- People don’t read docs because they *want* to. They read them because they’re stuck.
- We don’t waste their time trying to sound impressive—we respect it by being helpful.
- Empathy isn’t a “nice-to-have”—it’s our UX strategy in writing.

> Clarity is the kindest thing we can offer someone mid-problem.

---

## 8. Markdown & Commit Style  
_The backbone of formatting clarity._

Markdown is the shared language of your documentation.  
Used well, it brings structure and calm. Used carelessly, it creates chaos.

---

### ✅ Markdown Guidelines

| Task | Rule |
|------|------|
| Code blocks | Use triple backticks: \`\`\`bash |
| Inline code | Use backticks: \`filename.txt\` |
| Headings | One `#` per level, no skipping |
| Lists | Use `-` or numbered lists (avoid asterisks) |
| Links | Use `[text](url)` syntax—no raw URLs |

✅ Always use **one blank line** between headings, paragraphs, and list items.  
✅ Use indentation sparingly; avoid nested chaos.

---

### ❗ Common Markdown Mistakes to Avoid

| Mistake | Better Approach |
|--------|-----------------|
| Mixing `*` and `-` in lists | Stick with `-` for all unordered items |
| Raw URLs | ❌ `https://example.com` → ✅ `[Example](https://example.com)` |
| No blank lines around blocks | Markdown breaks—add spacing |
| Code without context | Always add a sentence before code to explain what it does |

---

### 🧠 When to Use Inline vs Block Code

| Use Case | Use This |
|----------|----------|
| Referencing a file, flag, or CLI option | `` `inline code` `` |
| Showing steps, commands, or config | \`\`\`block code\`\`\` with language label |

✅ Be kind to the reader:  
Use inline when referencing, block when teaching.

---

### ✅ Commit Message Style

We use **conventional commit prefixes** for clarity and changelog generation:

```bash
feat: add onboarding checklist template
fix: resolve broken anchor link in API doc
docs: rewrite intro paragraph for tone
refactor: reorganize folder structure
chore: update dependencies
```

✅ Use **present tense** (`add`, not `added`)  
✅ Keep subject lines under 72 characters  
✅ Use lowercase prefixes (no `Feat:` or `Fix:`)

---

### 💬 Why It Matters

Your commit history is not just a log—it’s a **narrative**.  
Clear messages help:
- Auto-generate changelogs
- Scan history during debugging
- Guide code reviewers faster

> A good commit is a small act of documentation.

---

## 9. Accessibility & Inclusivity  
_Alt-text, plain language, and respect for real-world readers._

Accessibility isn't just about screen readers.  
It’s about making your docs usable by people who are tired, rushed, anxious, distracted—or differently abled.

That includes:
- Screen reader users
- Non-native English speakers
- Colorblind users
- Newcomers who don’t know your product (yet)

---

### 🧭 Core Principles

| Principle | What It Means |
|-----------|----------------|
| **Clarity is accessibility** | Dense, jargon-heavy text excludes readers |
| **Alt-text is not optional** | Every image should explain its meaning or context |
| **Structure aids navigation** | Headings, spacing, and order help users skim |
| **Link labels should describe action** | Never say "click here" |
| **Tone should respect all backgrounds** | No idioms, jokes, or references that might alienate |

---

### ❌ Inaccessible Example
```markdown
Hey! Click here to learn more! 🎉

![Graph](graph.png)
```

### ✅ Inclusive Rewrite
```markdown
Want a deeper explanation? [Read the API example guide](../examples/remapped-api.md)

![Line graph showing API response time decreasing after optimization](../assets/images/api-speed.png)
```

✅ The alt text explains what the graph *means*, not just what it *is*.

---

### 🛠 Tools That Help

- [Hemingway Editor](https://hemingwayapp.com/) – Simplify complex sentences
- [WAVE Accessibility Tool](https://wave.webaim.org/) – Audit contrast, alt text, etc.
- [Inclusive Language Checker](https://alexjs.com/) – Detect biased or outdated terms

---

### 📌 TL;DR

- Add alt text that makes sense out of context
- Write like your reader has one eye on the clock and one hand on their toddler
- Don’t assume knowledge—or perfect English
- Never use “click here” as link text
- Keep sentence structure light, clean, and logically ordered

> Accessibility isn’t extra effort. It’s built-in empathy.

---

## 10. Localization & Translation  
_Placeholder syntax, tone shifts, and global awareness._

Good docs speak many languages—even when they’re only written in one.

Localization doesn’t start with translation.  
It starts with writing that’s clear, culture-neutral, and easy to adapt.

---

### 🌍 Key Practices for Localization-Friendly Writing

| Practice | Why It Matters |
|----------|----------------|
| **Keep sentences short** | Easier to translate, less room for misinterpretation |
| **Avoid idioms, slang, or cultural references** | Not all metaphors cross borders |
| **Use consistent terminology** | Reduces translation ambiguity |
| **Don’t hardcode values or labels** | Keep UI strings and placeholders separate |
| **Use neutral date/time formats** | Prefer ISO: `YYYY-MM-DD`, `14:00 UTC` |

---

### ❌ Bad for Translation
```markdown
You’ve nailed it—time to kick things off! 🎉  
Click “Go” and let’s roll!
```

### ✅ Localization-Friendly Version
```markdown
You're ready to begin.  
Click **Go** to start the process.
```

> 🎯 Be specific, not clever. Translators will thank you.

---

### 🧩 Placeholder Format

When writing text that will include dynamic values (e.g., usernames, file paths), use clear and localizable syntax:

✅ Use:
```markdown
Welcome, `{username}`.  
Your report is saved to `{filepath}`.
```

Avoid:
```markdown
Welcome, $username! Your file is in $path
```

---

### 🛠 Helpful Tools

- [Phrase](https://phrase.com) – Translation management platform
- [Crowdin](https://crowdin.com) – Collaborative localization for docs
- [LocalizationLint](https://github.com/DavidAnson/markdownlint) – Lint for localization issues in Markdown

---

### 📌 TL;DR

- Write for translation by writing clearly  
- Avoid wordplay and ambiguity  
- Use placeholders, not hardcoded strings  
- Respect language direction, spacing, and tone

> If your doc can’t travel, it can’t scale.

---

## 11. Linking & Cross-Referencing  
_Teaching users how to navigate like pros._

A good link is like a guidepost. It’s clear, descriptive, and helps the reader move forward confidently—without friction or confusion.

---

### 🔗 Link Types & Formats

| Type | Format | Example |
|------|--------|---------|
| Same page (anchor) | `[text](#section-name)` | `[Go to Setup](#setup-guide)` |
| Another file | `[text](../folder/filename.md)` | `[Style Guide](../STYLE-GUIDE/STYLE-GUIDE.md)` |
| External | `[text](https://url.com)` | `[Visit GitHub](https://github.com)` |

✅ Anchor links are based on the heading text, all lowercase, spaces → `-`, and special characters removed.

---

### ❌ Poor Linking Practices

```markdown
Click [here](https://example.com) to continue.

See [this](../other.md).

Follow this link to [go back](#).
```

### ✅ Clean, Descriptive Links

```markdown
To view our API setup process, [read the Setup Guide](../docs/api-setup.md).

Need the full changelog? [Check the release notes →](../RELEASES.md)

Want to jump ahead? [Skip to Troubleshooting](#troubleshooting)
```

---

### 📌 Internal Anchors: How They Work

GitHub automatically creates an anchor link for every heading.

```markdown
## How to Install → becomes → #how-to-install
## FAQ & Troubleshooting → #faq--troubleshooting
```

Rules:
- Use all lowercase
- Replace spaces with hyphens `-`
- Keep punctuation out unless it’s `&` or `-` (GitHub supports double hyphens for `&`)

✅ Examples:
```markdown
[Jump to Troubleshooting](#faq--troubleshooting)

[See the Doc Types section](#5-doc-types--examples)
```

---

### 🧠 Best Practices

- ✅ Link nouns, not verbs:  
  ❌ `Click here to learn more` → ✅ `Learn more about [markdown formatting]`
- ✅ Test all links in the final rendered view (not just raw Markdown)
- ✅ Keep anchor links updated if headings change

---

> Good links feel invisible. They don’t interrupt.  
> They just move the reader forward at the exact right moment.

---

## 12. Code & Command Snippets  
_Highlight with clarity, not clutter._

Code blocks aren’t just for developers—they’re clarity boosters.  
Done right, they make your docs feel helpful, visual, and skimmable.

---

### 📦 Code Block Guidelines

| Rule | ✅ Do This |
|------|-----------|
| Use triple backticks | \`\`\`bash (or json, html, etc.) |
| Label the language | Enables syntax highlighting |
| No dollar sign in terminal commands | Makes it easy to copy |
| Use inline code for filenames/flags | `` `README.md` ``, `` `--debug` `` |
| Show example output when relevant | Help readers verify results |

---

### ❌ Poorly Formatted Example
```markdown
To install, run the command below:

$ npm install my-package
Then run it.
npm start
```

### ✅ Structured, Clear Version
```markdown
## Install the Package

```bash
npm install my-package
```

## Run the App

```bash
npm start
```
```

> 🧠 Avoid putting `$` before commands—it breaks copy-paste.

---

### ❌ Unlabeled, Unreadable JSON
```markdown
```
{
"success": true,
"msg": "OK"
}
```
```

### ✅ Properly Labeled JSON Block
```json
{
  "success": true,
  "msg": "OK"
}
```

---

### ✅ Inline Code Best Practices

Use inline code (with single backticks) for:
- Filenames: `` `config.yaml` ``
- Flags: `` `--force` ``
- Paths: `` `/usr/local/bin` ``

> Avoid bold or quotes for technical terms. Use `inline code` instead.

---

### 📌 TL;DR

| ❌ Don't | ✅ Do |
|---------|------|
| Mix code and paragraph text | Separate it out visually |
| Skip labeling | Use `bash`, `json`, `sh`, `js`, etc. |
| Use `$` in front of CLI code | Leave it out for easy copying |
| Forget output examples | Help readers verify success |

> If the user has to squint at the code block, you’ve already lost them.

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

## 13. Admonitions & Callouts  
_⚠️ warnings, 💡 tips, ✅ examples._

Documentation isn’t just about **telling**—it’s about **guiding**.  
That means you need more than paragraphs. You need signals.

Admonitions (also called "callouts") help readers:
- Slow down before breaking something
- Pay attention to what’s commonly missed
- Feel reassured when they’re doing it right

---

### 🎯 Types of Admonitions We Use

| Type | Emoji | Use It When… |
|------|-------|--------------|
| **Note** | 📝 or ℹ️ | You’re adding context or useful background |
| **Tip** | 💡 | You want to help users do it faster/smarter |
| **Warning** | ⚠️ | A mistake here could break, delete, or confuse |
| **Example** | ✅ | You’re reinforcing a concept with a use-case |

---

### 💡 How to Format

#### ✅ Basic Markdown
Use blockquotes with emojis + bold labels:

```markdown
> ⚠️ **Warning:** Don’t run this command as root unless you know what you’re doing.
> 💡 **Tip:** Use `--dry-run` to preview the changes before applying them.
> ✅ **Example:** This config disables caching in local dev environments.
```

#### ✅ GitHub-Flavored Markdown (advanced)
If using a static site generator (like Docusaurus or MkDocs), you can use custom containers:

```md
:::tip
You can skip the setup step if you're using version 2.0 or later.
:::

:::warning
Never expose your API key in public repos.
:::
```

---

### ❌ Flat and Forgettable
```markdown
Be careful not to delete your database.
You can use dry-run to test it first.
```

### ✅ Structured & Supportive
```markdown
> ⚠️ **Warning:** Running this will erase all data in the `prod` environment.

> 💡 **Tip:** Add `--dry-run` to preview which records would be deleted before confirming.
```

---

### 🧠 When to Use Them

- ✅ If the reader might mess it up, use a **warning**
- ✅ If there’s a faster path, use a **tip**
- ✅ If it reinforces learning, add an **example**
- ✅ If it’s helpful but non-critical, use a **note**

> Don’t overuse them.  
> A doc full of callouts is just yelling at the user in emoji.

---

### 📌 TL;DR

- Use callouts like a mentor: kind, honest, and clear.
- Don’t write “gotchas” after the fact—guide before the fall.
- Use structure to show empathy: **highlight what matters before it’s too late**.

---

## 14. Asset Management  
_Folder conventions, image specs, and the hidden art of staying organized._

Docs are not just words.  
They’re visuals, downloads, embedded demos, diagrams, and often... a folder full of chaos.

Let’s not do that.

---

### 📁 Folder Structure

All static assets—images, icons, charts, downloadable files—go here:

```
/assets/
   └── images/
   └── diagrams/
   └── downloads/
```

Use lowercase folder and file names, with hyphens instead of spaces:
✅ `api-flowchart.png`  
✅ `user-guide-cover.png`  
❌ `Final Version (3).PNG`

> 📌 Tip: Keep assets **outside** your `/docs/` folder to avoid URL conflicts and clutter.

---

### 🌄 Image Guidelines

| Rule | What To Do |
|------|-------------|
| Format | Use `.png` for diagrams/UI, `.jpg` for photos, `.svg` for icons |
| Alt Text | Every image **must** include meaningful alt text |
| Dimensions | Keep under 1200px wide unless full-screen is needed |
| Compression | Use [TinyPNG](https://tinypng.com) or [Squoosh](https://squoosh.app) to reduce size |
| Naming | Use lowercase, hyphenated, descriptive filenames |

---

### ❌ Bad Practice
```markdown
![img1](../docs/random_assets/finalfinal2.PNG)
```

### ✅ Better
```markdown
![User selecting a date range in the dashboard](../../assets/images/date-filter-ui.png)
```

✅ Alt text describes what’s shown and why it matters.  
✅ Path follows clean folder structure.

---

### 📦 Embeddable Files

If you’re including downloads (PDFs, templates, etc.), place them under `/assets/downloads/`.

Name them clearly:
- `user-onboarding-checklist.pdf`
- `quickstart-template.docx`

Avoid:
- `final-checklist2 (copy).pdf`
- `doc1.docx`

---

### 🧠 Why This Matters

- Images without structure = broken links later  
- Large files = slow docs  
- Confusing names = contributor rage  

> Your readers may never see the asset folder—but your teammates will. Leave a trail of sanity.

---

### 📌 TL;DR

- Use `/assets/` with clear subfolders (`images`, `downloads`, `diagrams`)
- Optimize every image—don’t dump raw screenshots
- Describe visuals with intent—**alt text is content**
- File names should be readable, reusable, and lowercase

---

