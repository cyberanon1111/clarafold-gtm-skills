# Clarafold GTM Skills

**Five B2B go-to-market workflows, packaged as agent skills your own AI can install and run.**

These are the playbooks behind the GTM systems [Clarafold](https://clarafold.com) builds for complex B2B companies: small markets, buying committees, long sales cycles. Each skill follows the open [Agent Skills](https://agentskills.io) format, so it works in Claude, Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI and other agents that read `SKILL.md`.

Every skill asks for real inputs first, works step by step so you can correct course, and refuses to invent metrics, companies, contacts or quotes. Agents do the repetitive work; people make the calls.

## The skills

| Skill | Category | Level | Time | What it produces |
|---|---|---|---|---|
| [ICP Research](skills/clarafold-icp-research/SKILL.md) | ABM / RevOps | Intermediate | 2–4 hrs per segment | Documented ICP, buying-committee map, buyer problem statement, exclusion criteria |
| [Outbound Personalization](skills/clarafold-outbound-personalization/SKILL.md) | Outbound | Intermediate | 5–10 min per account | Personalization variables, change signal + source, reason to contact now, skip list |
| [LinkedIn Content Research](skills/clarafold-linkedin-content-research/SKILL.md) | Content | Beginner | 2–3 hrs per cycle | Topic queue with one claim per topic, evidence needed and link to positioning |
| [Lead Enrichment](skills/clarafold-lead-enrichment/SKILL.md) | RevOps | Beginner | Runs continuously | Enriched, deduped, fit-scored records with rule-based routing and an exception queue |
| [Account Prioritization](skills/clarafold-account-prioritization/SKILL.md) | ABM | Advanced | 1–2 days to build | Scored universe, tiered and capped target list, scoring model, re-scoring cadence |

Read the full walkthrough of each workflow at [clarafold.com/workflows](https://clarafold.com/workflows).

## Install

**Claude Code**

```bash
git clone https://github.com/cyberanon1111/clarafold-gtm-skills.git
cp -r clarafold-gtm-skills/skills/* ~/.claude/skills/        # personal
# or: cp -r clarafold-gtm-skills/skills/* .claude/skills/   # one project
```

**Claude (web or desktop)**: download the bundle from [clarafold.com/workflows](https://clarafold.com/workflows), then upload it under Settings → Capabilities → Skills.

**Codex**: copy the skill folders into `~/.agents/skills/` or a repo's `.agents/skills/`.

**Cursor, GitHub Copilot, Gemini CLI and others**: add the skill folders to that tool's skills directory. See [agentskills.io](https://agentskills.io).

## Try it

Once installed, just ask in plain English:

> "Use the ICP research skill on these closed-won and closed-lost deals and tell me who we should stop targeting."

> "Run outbound personalization on these 20 accounts. Skip any without a real signal."

## Why these exist

Building got cheap. Buying got harder. Tools and agents are everywhere, most of them free. The hard part is knowing which steps matter and in what order. These skills encode that order, from GTM systems run in complex B2B markets.

- See the results they came from: [case studies](https://clarafold.com/customers)
- Read the thinking behind them: [insights](https://clarafold.com/insights)
- More open-source tools for AI-powered GTM: [awesome-ai-gtm](https://github.com/cyberanon1111/awesome-ai-gtm)

## Want it built and run for you?

Clarafold designs, builds and runs these workflows as connected GTM systems, starting with a 10-day [Diagnosis Sprint](https://clarafold.com/diagnosis-sprint). More in the [Clarafold portfolio](https://github.com/cyberanon1111/clarafold).

---

Free to use and adapt. Published by [Clarafold](https://clarafold.com) · built by [Aman Istwal](https://www.linkedin.com/in/amanistwal/). Issues and suggestions welcome.
