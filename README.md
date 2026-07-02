# AgentCert v0 Smoke Repo

[![AgentCert](https://kakarottoooo.github.io/agentcert-v0-smoke/agentcert/latest/badge.svg)](https://kakarottoooo.github.io/agentcert-v0-smoke/agentcert/latest/agentcert-report.html)

The badge above is generated and published by the AgentCert Tripwire action on
every run (`publish-pages: "true"`). It links to the hosted evidence report;
the full Tripwire report with screenshots and traces is published next to it
[here](https://kakarottoooo.github.io/agentcert-v0-smoke/agentcert/tripwire/tripwire-report.html).

This repository verifies that an external project can run:

```yaml
- uses: Kakarottoooo/agentcert/actions/tripwire@v0
```

It starts a local deterministic refund form, runs a small Playwright-style
browser agent through Tripwire faults, and emits AgentCert evidence, report,
badge, monitor snapshot, JUnit, and reviewed failure dataset artifacts.

The workflow intentionally uses local demo systems only. It does not call real
payment, email, ERP, or vendor systems.
