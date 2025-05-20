# Purpose of This Guide

> Documentation isn’t just about telling users *what to do*—it’s about making sure they know *why they’re doing it*.  
> This guide helps you write like a guide, not a checklist.

---

## Problem

Too many user guides:
- Start with steps before establishing relevance or context  
- Forget that users aren’t all the same—some are writers, some developers, some just lost  
- Treat clarity like an optional feature instead of a core function  

As a result, documentation becomes a maze of instructions—no entry point, no map, no motivation.

---

## Rule

**Every guide should begin with a Purpose section** that:
1. **Identifies** the role(s) the document serves (writer, editor, dev, etc.)  
2. **Defines** the exact problem it helps solve  
3. **Guides** the reader on how to use the doc most effectively

This creates orientation, sets expectations, and invites the reader in.

---

## Example

❌ **Wrong** (too eager, no context):

```markdown
# How to Contribute
Fork the repo, clone it, create a new branch...
```

✅ **Right** (context-first clarity):

```markdown
# Purpose of This Guide

This document helps **first-time contributors** understand how to work with the `sans-serif-sentiments` repository.  
You’ll learn **how the repo is structured**, **what the style rules are**, and **how to contribute confidently** without breaking anything.

# How to Contribute
1. Fork the repo…
2. Clone it locally…
```
