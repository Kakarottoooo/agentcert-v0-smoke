# AgentCert v0 Smoke Repo

This repository verifies that an external project can run:

```yaml
- uses: Kakarottoooo/agentcert/actions/tripwire@v0
```

It starts a local deterministic refund form, runs a small Playwright-style
browser agent through Tripwire faults, and emits AgentCert evidence, report,
badge, monitor snapshot, JUnit, and reviewed failure dataset artifacts.

The workflow intentionally uses local demo systems only. It does not call real
payment, email, ERP, or vendor systems.
