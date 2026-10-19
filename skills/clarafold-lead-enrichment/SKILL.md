---
name: clarafold-lead-enrichment
description: "Runs Clarafold's Lead Enrichment Workflow: Enriches incoming or sourced leads and routes structured information into the CRM without manual handling. Use when the user wants to enrich, verify, deduplicate, score or route leads before they enter a CRM."
---

# Lead Enrichment Workflow

The Lead Enrichment Workflow is a seven-step RevOps process that enriches inbound and sourced leads, normalises and deduplicates the data, scores every record for fit and routes it into the CRM by rule — with an exception queue for records that fail. Once built, it runs continuously without manual handling.

## When to use

Use this skill when the user wants to enrich, verify, deduplicate, score or route leads before they enter a CRM.

## Ask the user for these inputs first

- Inbound form submissions
- Sourced lists
- Existing CRM records

If an input is missing, say what is missing and what the output will lack without it. Do not fill gaps with invented data.

## Tools this workflow assumes

- CRM
- Enrichment provider
- Automation platform
- Email verification

Use whatever the user has available (uploaded exports, connected tools, web search). Say which tools you actually used.

## Steps

1. **Define the required fields.** Decide what must be present for a record to be actionable. Enrich to that standard, not to whatever the vendor returns.
2. **Normalise on entry.** Standardise company names, domains, titles and geography before anything is written to the CRM.
3. **Enrich and verify.** Append firmographic and contact data, then verify deliverability before the record is usable.
4. **Deduplicate against existing.** Match on domain and contact to avoid creating a second record for an account already in play.
5. **Score for fit.** Apply ICP criteria so routing reflects fit rather than arrival order.
6. **Route by rule.** Assign by segment, territory or owner using explicit rules, and log why the decision was made.
7. **Handle failure explicitly.** Records that cannot be enriched go to a defined queue instead of silently entering the database.

Work through the steps in order. Show the result of each step briefly before moving on, so the user can correct course.

## Output

Produce one document with a section for each of these:

- Enriched, verified, deduplicated records
- Fit score on every record
- Rule-based routing with an audit trail
- An exception queue for failures

## Rules

- Use only evidence the user provides or that you can cite. Label assumptions as assumptions.
- Never invent metrics, company names, contacts or quotes.
- Prefer specific, checkable statements over general advice.

---

Published by Clarafold (https://clarafold.com/workflows/lead-enrichment). Free to use and adapt.
