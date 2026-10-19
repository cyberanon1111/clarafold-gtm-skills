---
name: clarafold-outbound-personalization
description: "Runs Clarafold's Outbound Personalization Workflow: Researches an account, identifies relevant signals and creates structured personalization inputs a sequence can actually use. Use when the user wants to personalise outbound emails or LinkedIn messages for specific accounts, find a reason to contact an account now, or prepare personalisation variables for a sequence."
---

# Outbound Personalization Workflow

The Outbound Personalization Workflow is a seven-step research process that produces structured personalization inputs for one target account: its business context, a named change signal and its source, the function that owns the problem, one checkable piece of evidence and a stated reason to contact now. It takes roughly 5–10 minutes per account, and accounts without a usable signal are skipped.

## When to use

Use this skill when the user wants to personalise outbound emails or LinkedIn messages for specific accounts, find a reason to contact an account now, or prepare personalisation variables for a sequence.

## Ask the user for these inputs first

- Target account list
- ICP problem statement
- Offer or point of view

If an input is missing, say what is missing and what the output will lack without it. Do not fill gaps with invented data.

## Tools this workflow assumes

- Enrichment provider
- Company news sources
- LinkedIn
- AI research assistant
- Outbound platform

Use whatever the user has available (uploaded exports, connected tools, web search). Say which tools you actually used.

## Steps

1. **Establish the account context.** Business model, who they sell to, and how they make money. Relevance starts here.
2. **Look for a change signal.** Funding, hiring, leadership change, product launch, market entry, regulatory shift. Change creates the reason to act.
3. **Locate the function that owns the problem.** Identify the role most likely accountable for the outcome you affect.
4. **Find the specific evidence.** One concrete, checkable observation — a job posting, a stated priority, a visible gap.
5. **Connect evidence to consequence.** State what that observation likely means for them commercially. This is the part that earns a reply.
6. **Produce structured fields.** Output discrete variables the sequence can insert, rather than a paragraph a human must rewrite.
7. **Quality gate.** If the research produced nothing specific, the account is skipped rather than sent a generic message.

Work through the steps in order. Show the result of each step briefly before moving on, so the user can correct course.

## Output

Produce one document with a section for each of these:

- Structured personalization variables per account
- Named change signal and its source
- A stated reason-to-contact-now
- A skip list of accounts with no usable signal

## Rules

- Use only evidence the user provides or that you can cite. Label assumptions as assumptions.
- Never invent metrics, company names, contacts or quotes.
- Prefer specific, checkable statements over general advice.

---

Published by Clarafold (https://clarafold.com/workflows/outbound-personalization). Free to use and adapt.
