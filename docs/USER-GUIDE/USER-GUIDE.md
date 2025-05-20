# USER GUIDE  
*How to Write Documentation Without Losing the Plot*

Welcome to the user guide for the **sans-serif-sentiments** project.  
This isn't your average documentation about documentation.  
This is a writer’s manual for writing manuals—without sounding like a manual.

---

## Who Is This For?

This guide is for:
- Writers who think “technical writing” is just a boring term for “corporate gray”
- Developers who document only when someone threatens their lunch break
- Contributors who want to write with clarity, consistency, and a tiny touch of soul

Whether you're creating a user manual, an API reference, or a how-to blog, this guide helps you write docs that **don’t just instruct—they resonate**.

---

## What You’ll Find Here

| Section | What It Covers |
|--------|----------------|
| [Before You Start](#2-before-you-start) | Tools, mindset, and the invisible prep work |
| [Anatomy of a Great Doc](#3-anatomy-of-a-great-doc) | Visual breakdown of documentation elements |
| [Writing Principles](#writing-principles) | How to write like a human, not a helpdesk |
| [Doc Types & Examples](#doc-types--examples) | Different doc styles and when to use them |
| [Visual Writing](#visual-writing) | Tables, UI cutouts, code blocks & delight |
| [Style in Action](./STYLE-GUIDE.md) | How to apply our style guide |
| [Remapped Examples](./examples/remapped-markdown.md) | Rewriting traditional docs in our voice |
| [FAQs](#faq--troubleshooting) | Because something will go wrong |
| [Next Steps](#next-steps) | Where to go from here |

---

## Why Another Writing Guide?

Because most guides:
- Assume you know what you’re doing
- Don’t explain *why* things are done that way
- Are as readable as your printer’s warranty

This one’s different.
It shows you how to:
- Write for when things **don’t** work (not just when they do)
- Consider how your doc will be read by a **developer**, a **designer**, or a **desperate team lead at 2:00 AM**
- Ask: “What’s the worst way this can be misunderstood?”—and then make it clearer

We respect your time, your sanity, and your tab limit.

---

## TL;DR

This is a minimalist yet detailed manual for writing helpful, honest, and human documentation.  
No buzzwords. No fluff. Just thoughtful writing for real people.

Let’s begin.
---

## 2. Before You Start 
🧭

> Good documentation isn’t just written—it’s prepared for.  
> This section helps you avoid rookie mistakes and shows you how to *think* like a technical writer before you even open a text editor.

---

### 🛠️ Tools You’ll Need

| Tool | Why You Need It |
|------|-----------------|
| A Markdown Editor (like VS Code, Typora, Obsidian) | To write in plain text and preview documentation |
| A Style Guide (like this one) | To ensure consistency in tone, format, and terminology |
| A Clear Requirements Brief | So you don’t write blindly—know what the doc needs to achieve |
| A Documentation Plan | Helps you scope the document, audience, and outcomes before you write |
| Your Brain (fully charged) | You’ll need empathy, clarity, and curiosity—no automation replaces that (yet) |

---

### 🧠 Mindset Before You Begin

- Don’t write to *impress*—write to **guide**
- Start with the reader’s **intent**, not your outline
- Avoid assuming the reader knows what you know
- Be kind to the next person who will read your doc at 2AM with tired eyes

---

### 🚫 Don’t Do This (A Little Table of Shame)

| Mistake | What It Looks Like | What to Do Instead |
|--------|---------------------|--------------------|
| ❌ Jumping straight into steps | `1. Click the button...` | ✅ Start with a purpose |
| ❌ Overloading jargon | `Configure with advanced tokenization` | ✅ Use plain English unless it’s truly needed |
| ❌ Ignoring different roles | Only SMEs will understand | ✅ Write modularly: “If you're a support agent, skip to section 3…” |
| ❌ Writing like you’re bored | “Just open the thing” | ✅ Write like you care (but don’t overdo it) |

---

### ✅ TL;DR

Before writing anything:
- Get your tools and thinking aligned
- Set your intention
- Remember: good documentation is a conversation, not a command

Up next: [Anatomy of a Great Doc →](#3-anatomy-of-a-great-doc)

---

## 3. Anatomy of a Great Doc

> You wouldn’t build a house without a blueprint. Don’t write documentation without one either.  
> This section is the blueprint. It shows you what every well-crafted document needs—no matter who it's for.

<img src="../../assets/images/doc-anatomy.png" alt="Anatomy of a Great Doc" width="700"/>
---

### 📊 The Skeleton: Standard Structure of a Useful Doc

| Section | Function |
|---------|----------|
| **📄 Title** | A short, searchable identifier—not a full sentence |
| **🎯 Purpose** | Why this document exists, and who it's meant for |
| **🧭 Scope or Audience** | Optional, but clarifies what roles it applies to (or doesn't) |
| **📚 Table of Contents** | Optional, but essential for longer docs |
| **🪜 Body** | The actual content: step-by-step, structured, scannable |
| **📷 Visual Aids** | Screenshots, tables, diagrams that reduce friction |
| **⚠️ Notes & Edge Cases** | Tips, warnings, things users might get wrong |
| **🔗 Related Links** | Point to supporting docs or source code |
| **📅 Last Updated** | Build trust. Readers want to know: *is this still valid?*

---

### 🧱 Visual Layout (Convert to Image Later)

Use this layout as a guide when building or reviewing your doc:

+----------------------------+
| 📄 Title |
+----------------------------+
| 🎯 Purpose / Audience |
+----------------------------+
| 📚 TOC (optional) |
+----------------------------+
| 🪜 Body |
| - Steps / Explanations |
| - Visuals & Examples |
+----------------------------+
| ⚠️ Tips & Notes |
+----------------------------+
| 🔗 Links / References |
+----------------------------+
| 📅 Last Updated |
+----------------------------+


📌 *Embed this as an actual diagram later via `/assets/images/anatomy.png`*

---

### 🔍 Part-by-Part Breakdown with Examples

---

#### 🎯 Purpose

> *Start by telling the reader why this doc exists and who it's for.*

**❌ Common mistake:**
```markdown
# Setup Guide
1. Install the app…
```

✅ Fixed:
```markdown
# Setup Guide

This document helps new users install the app in under 5 minutes, with tips for Mac and Windows.

1. Install the app…
```

#### 🪜 Body

> *Organize your steps. Break them down. Don't assume your reader knows as much as you do.*

❌ Common mistake:

```markdown
Do the thing. Then do the other thing.
```

✅ Fixed:
```markdown
## Step 1: Download the Installer
Include platform-specific links here.

## Step 2: Run the File
Explain how to find it and what to expect.
#### ⚠️ Tips, Notes, and What Can Go Wrong

> *Readers want to avoid mistakes. This section is where you save them.*

```

❌ Common mistake:
```markdown
Skipping it entirely.
```

✅ Fixed:
```markdown
> ⚠️ **Troubleshooting Tip:** If installation fails on macOS Ventura, check System Preferences > Security and manually allow the app.
Use callout boxes, blockquotes, or bold labels to highlight issues and solutions.
```

#### 📅 Last Updated / Versioning

> *Trust comes from transparency. Help readers know how fresh your content is.*

❌ Common mistake:
```markdown
Leaving users to guess whether the doc is still relevant.
```

✅ Fixed:
```markdown
_Last updated: May 20, 2025_  
_Compatible with version 2.4.0 and above_
```

#### 🧨 When Can You Break the Format?

> *Great docs follow structure. Brilliant ones break it on purpose—with care.*

Break the format when:

Your doc is very short (e.g., CLI command reference)

You're creating onboarding slides or UI tooltips

The context is already crystal clear (e.g., error code guides)

But still try to signal structure—even in small ways.

---

### ✅ TL;DR

Good documentation has a predictable rhythm: it tells you where you're going, shows you how to get there, warns you of cliffs, and points to other maps if needed.

Structure is what makes your writing scale. It's not a crutch—it's a scaffold.

Up next: Writing Principles →
