---
name: step-23-kdp-skill-version-maintenance
description: KDP skill health review and controlled version-maintenance planning. Use for periodic drift checks or proposed skill improvements.
license: Complete terms in LICENSE.txt
---

# Sys 04 Kdp Skill Version Maintenance

Check every workflow skill for stale rules, broken paths, conflicts, and missing gates without silently changing it.

## Non-negotiable project rules

- Keep Samir in control: never publish, upload, pay, change an account, or submit a form. Prepare files and instructions only.
- Use free methods first. Before any tool or provider that may cost money, ask exactly: **Free tool or paid tool?** If free is insufficient, explain why, list paid options from highest to lowest price, and wait for written approval.
- Work only in the active browser and project files. Do not use a VPS, proxy, CAPTCHA bypass, private login, or hidden scraping.
- Never invent Amazon search counts, BSRs, ratings, prices, quotes, sales, reviews, or search volume. Missing data is `no data`, `UNKNOWN`, or `INCOMPLETE`.
- Attach an evidence tag to every number: `[VERIFIED: URL, YYYY-MM-DD]`, `[COURSE]`, `[ESTIMATE]`, `[ASSUMPTION]`, or `[RECOMMENDATION]`.
- Use dated lowercase filenames such as `output_<topic>_<yyyymmdd>.md`. Never overwrite a dated file; create a new dated file with a `Supersedes:` header.
- If work cannot be completed, mark it `BLOCKED` and record exactly: `Error / Tried / Next`.
- Do not claim completion without a real file path, read-back, command result, or visited URL.

## Inputs

Current skill files, registry, operating rules, recent reports, validator output, and user-approved change request.

## Procedure

1. Inventory skill names, frontmatter, triggers, paths, and validator status.
2. Compare instructions with operating rules and current project registry.
3. Identify contradictions, stale policy references, duplicate skills, and missing outputs.
4. Propose changes in a new dated file with exact rationale.
5. Wait for Samir’s approval before editing any installed skill.

## Required outputs

`00_Project_Control/weekly_skill_health_review_<yyyymmdd>.md` and proposed files under `15_Skills/_corrected/`.

## Quality gate

A health review is not permission to modify skills. Report BLOCKED when source access or approval is missing.
## Workflow position

**Step 23** — this card is part of the numbered KDP workflow. Use the previous step outputs before starting it and pass its required outputs to the next step.

