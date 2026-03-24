# You Don't Have an Observability Problem. You Have a Signal Problem.

**Topic:** Observability & Monitoring

---

Most mature engineering teams don't suffer from a lack of metrics. They suffer from an abundance of them. Dashboards multiply. Alerts accumulate. On-call engineers learn, through painful experience, which alerts to ignore — and that tribal knowledge never gets written down.

The underlying mistake is treating observability as a data collection exercise. More metrics, more coverage, more visibility. But a dashboard with 200 panels that nobody acts on is not observability. It's noise with good branding.

> Ask this about every metric you collect: "What decision does this enable?" If you can't answer that, you don't need the metric.

The discipline is tying every signal to a user-facing outcome. Latency matters because users experience it. Error rates matter because users hit them. CPU utilization only matters insofar as it predicts something a user will notice. Start there, work backwards, and cut everything that doesn't connect to that chain.

This isn't just a philosophical point — it changes how you instrument, how you alert, and how you respond. Engineers who understand why a metric exists act on it. Engineers drowning in undifferentiated telemetry develop alert fatigue and stop trusting their tools.

The goal isn't comprehensive visibility. It's useful visibility.
