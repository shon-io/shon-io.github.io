---
title: Do you have an observability problem? Probably not.
author: Shon Frazier
date: 19 Nov 2024
Topic: Observability & Monitoring
---

---

If you think you do, it's likely because your engineering team is struggling with an abundance of metrics. Dashboards multiply, alerts accumulate. The result: on-call engineers learn, through painful experience, which alerts to ignore, and that tribal knowledge never gets written down.

The underlying mistake is treating observability as a data collection exercise. More metrics, more coverage, more visibility. But a dashboard with 200 panels that nobody acts on is noise with good branding, not observability.

With every metric you collect, ask "What decision does this enable?" If you can't answer that, you don't need the metric.

You need discipline in tying every signal to a user-facing outcome. Latency matters because users experience it. Error rates matter because users hit them. CPU utilization only matters insofar as it predicts something a user will notice. Start there, work backwards, and cut everything that doesn't connect to that chain.

This changes how you instrument, how you alert, and how you respond. Engineers who understand why a metric exists act on it. Engineers drowning in undifferentiated telemetry develop alert fatigue and stop trusting their tools.

Your goal is useful visibility, and "comprehensive" is too often its antithesis.
