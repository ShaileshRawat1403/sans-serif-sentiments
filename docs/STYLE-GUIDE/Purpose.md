# Purpose of This Guide

> A guide is only as useful as its intention. Before diving into rules and examples, we need to know **why** this guide exists, and **who** it’s for.

---

## Problem

Too often, documentation:
- Jumps straight into “how” without explaining **why** readers should care.  
- Leaves out context about **who** the intended audience is.  
- Forces readers to guess the **intended use** or scope of the material.

As a result, users skim, get lost, or abandon the doc entirely.

---

## Rule

**Always begin with a clear Purpose statement** that, in 2–3 sentences:
1. **Identifies** the primary audience.  
2. **States** the problem this document solves.  
3. **Describes** how the reader should use it.

This orients readers at the outset, builds trust, and sets expectations.

---

## Example

❌ **Wrong** (no purpose—reader is left guessing):

```markdown
# Installation
1. Download the package…
2. Run `install.sh`…
```

✅ **Right** (with purpose—reader knows exactly why and how):

```markdown
# Purpose of This Guide

This document helps **busy developers** integrate the `sleepsort` API in **under five minutes**.  
You’ll learn **what** endpoints you need, **how** to authenticate, and **where** to find examples.

# Installation
1. Download the package…
2. Run `install.sh`…
```


