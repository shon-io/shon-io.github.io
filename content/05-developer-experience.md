---
title: Tooling Chaos
author: Shon Frazier
date: 30 Apr 2025
Topic: Developer Experience (DevEx)
---

---

Ask a developer at a mid-to-large engineering organization how many tools they interact with in a typical workday. The answer is usually somewhere between alarming and depressing. A deployment tool, a secrets manager, a different secrets manager for a different environment, three monitoring platforms, a CI system that's being migrated to a different CI system, and a runbook that references two tools that were deprecated last year.

This is the real DevEx problem. Not any single tool, but the incoherence of the whole landscape. Every tool was a reasonable decision in isolation. Together, they form a maze that taxes developer cognition before they've written a line of code.

The best platform teams give developers fewer tools with better defaults and less to learn.

An opinionated internal platform solves the problem that better documentation only papers over. Developers shouldn't need to know which of the three deploy mechanisms applies to their service. They should be able to run one command and have it work.

Building this requires a team that treats developers as customers, that measures friction as seriously as reliability, and that is willing to make unpopular consolidation decisions. It's harder than adding another tool, but it's the only thing that actually reduces the cognitive overhead that kills developer flow.
