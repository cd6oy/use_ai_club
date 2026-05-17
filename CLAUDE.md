# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repo Is

This is a non-code repository for the **Youth AI Engineering Club** — a community-based club for high school students. It contains club specs and proposals, not software.

## Structure

```
specs/          ← club proposals and specs (source of truth)
  proposal.md   ← founding proposal
```

## How to Work Here

New club initiatives (plans, workshops, projects, policy decisions) go into `specs/` as Markdown files. Each spec should capture **what** the club is doing and **why** — not implementation steps.

When proposing a change to an existing spec, edit it in place. There is no separate change-tracking layer.

## Conventions

- Branch per proposal: `proposal/<name>` → PR → merge to main
- Specs are written for founding families and student members, not a technical audience — keep language plain
- The club's core loop is **learn → practice → share** — proposals should map back to one or more of these verbs
- ACSL and FRC are high-priority **domains** the club practices on, not the club's identity
