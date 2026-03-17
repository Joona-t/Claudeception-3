# Bugs & Iterations

## : |2026-01-18|||fix: use correct slash command /continuous-learning instead of /retrospective

**Problem:** |2026-01-18|||fix: use correct slash command /continuous-learning instead of /retrospective
**Details:** Since Claude Code 2.1, skills appear in the slash command menu via /skill-name.
The skill is named 'continuous-learning', so the correct command is /continuous-learning.
Fixes #1
**Files:** README.md,SKILL.md
**Commit:** 04ebad3

## : |2026-01-18|||feat: improve skill description for better semantic matching on manual triggers

**Problem:** |2026-01-18|||feat: improve skill description for better semantic matching on manual triggers
**Details:** - Add explicit trigger phrases: /retrospective, 'save this as a skill', 'what did we learn?'
- Mention debugging/workaround/trial-and-error discovery triggers
- Bump version to 2.5.0
Co-Authored-By: Warp <agent@warp.dev>
**Files:** SKILL.md
**Commit:** ad0c3bd

## : |2026-01-22|||fix: remove duplicated sentence in README

**Problem:** |2026-01-22|||fix: remove duplicated sentence in README
**Files:** README.md
**Commit:** ec1991f

<!-- Format:
## YYYY-MM-DD: Short Title

**Problem:** What went wrong or needed changing
**Root cause:** Why it happened
**Fix:** What was done to resolve it
-->
