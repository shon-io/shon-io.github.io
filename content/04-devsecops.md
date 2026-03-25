---
title: Security at the End Is Security Theater.
author: Shon Frazier
date: 7 Mar 2025
Topic: DevSecOps
---

---

The pattern is familiar: A team spends six weeks building a feature. In the final stretch, it goes to a security review. The security team finds issues. The issues take two weeks to fix. The launch slips. Everyone is frustrated, and the relationship between security and engineering gets a little worse.

Multiply that across an organization and you get what most companies actually have: security as a tollbooth at the end of the delivery road. It creates adversarial dynamics, last-minute rewrites, and a perverse incentive to rush through review over actually fixing problems.

Security requirements are just like other requirements. They belong in the backlog, in the design doc, in the definition of done — not in a final gate before launch.

There are two moves that change this. The first: treat security requirements like product requirements, defined at the start of a project alongside functional requirements. What data does this feature handle? What are the threat vectors? What do "done" and "secure" look like together? These questions have to be asked *before* a line of code is written.

The second: make security tooling self-serve. SAST scanners in the CI pipeline, dependency vulnerability checks on every build, secret detection before commits land. Not as blockers that frustrate developers, but as fast feedback that lets them catch and fix issues themselves in the flow of their normal work. When developers own security outcomes instead of outsourcing them to a review gate, quality improves and nobody has to play the villain.

Security is a property of the system. The only way to build it in is to start before there's a system to review.
