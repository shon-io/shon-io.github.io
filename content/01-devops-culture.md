---
title: DevOps Isn't an Ops Problem
author: Shon Frazier
date: 15 Sep 2024
Topic: DevOps Culture & Team Dynamics
---

---

Every few months, a company announces they've "adopted DevOps." What they usually mean is that they've renamed the ops team, given them a Jenkins instance, and asked them to go faster. The developers remain upstream, tossing releases over a wall. The ops team catches them ... or doesn't.

This is the original sin of most DevOps transformations: treating it as an ops concern. The logic seems convenient and tidy: ops runs production, so ops handles DevOps. But that framing guarantees failure, and the failure has a very specific smell.

Blame culture is the most visible symptom of misalignment. When developers have no stake in what happens after merge - no on-call rotation, no ownership of deployment pipelines, no visibility into production behavior - incidents become finger-pointing sessions. Ops blames dev for shipping bad code; dev blames ops for a fragile environment ... and nothing improves.

So when something breaks in production, who does get blamed? That's a trick question - failures have to be blameless if we're going to prevent the same problems in the future. If you're not figuring that out together, you've rebadged instead of implementing DevOps.

Real DevOps culture requires developers to care about operability as a first-class concern. That means writing runbooks, participating in postmortems, owning their services through to production. It also means ops teams stop being gatekeepers and become platform builders, while removing friction without adding process.

The cultural shift is "everyone owns the whole lifecycle *together*." That's uncomfortable for org charts, but it's the only thing that actually works.
