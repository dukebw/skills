---
name: grill-me
description: Interview the user relentlessly about a plan or design until reaching shared understanding, resolving each branch of the decision tree. Use when user wants to stress-test a plan, get grilled on their design, or mentions "grill me".
---

Interview me relentlessly about every aspect of this plan until we reach a shared understanding. Walk down each branch of the decision tree, resolving dependencies between decisions one-by-one.

Ask exactly one question at a time. Do not batch multiple questions into a single message. For each question:
- provide your recommended answer first
- explain briefly why that recommendation is your default
- use the `question` tool for every question; prefer a concise single-select toggle/button choice, with the recommended option first
- then ask the single next highest-leverage unresolved question

After the user answers, incorporate that answer and ask the next single question. Continue iteratively until the design is fully resolved.

If a question can be answered by exploring the codebase, explore the codebase instead.
