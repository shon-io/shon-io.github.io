# The Tooling Isn't the Problem. The Chaos Is.

**Topic:** Developer Experience (DevEx)

---

Ask a developer at a mid-to-large engineering organization how many tools they interact with in a typical workday. The answer is usually somewhere between alarming and depressing. A deployment tool, a secrets manager, a different secrets manager for a different environment, three monitoring platforms, a CI system that's being migrated to a different CI system, and a runbook that references two tools that were deprecated last year.

This is the real DevEx problem. Not any single tool, but the incoherence of the whole landscape. Every tool was a reasonable decision in isolation. Together, they form a maze that taxes developer cognition before they've written a line of code.

> The best platform teams don't give developers more tools. They give them fewer — with better defaults and less to learn.

The answer isn't better documentation for the maze. It's an opinionated internal platform: a curated, integrated set of tools with sensible defaults, where the happy path is obvious and the sharp edges are smoothed out. Developers shouldn't need to know which of the three deploy mechanisms applies to their service. They should be able to run one command and have it work.

Building this requires a team that treats developers as customers, that measures friction as seriously as reliability, and that is willing to make unpopular consolidation decisions. It's harder than adding another tool. It's the only thing that actually reduces the cognitive overhead that kills developer flow.
