# AgentCert Evidence Report

Subject: agentcert-v0-smoke
Generated: 2026-07-02T03:03:15.861Z
Verdict: PASS
Score: 83
Level: Silver

## Results

- tripwire-ci: PASS (83/100, pre-release)
  Tripwire CI gate passed.

## Evidence

- [high] assertion_result: Visible text should include Refund request submitted
- [high] assertion_result: No console errors should be recorded

## Standards Mapping

- AIUC-1 agent security, safety, and reliability: AgentCert evidence can support preparation for independent AIUC-1-style reviews; it is not an official certification.
- NIST AI Agent Standards Initiative: AgentCert evidence aligns with secure, interoperable, auditable agent deployment goals.
- OWASP Agentic AI threats and mitigations: AgentCert scenarios cover prompt injection, tool misuse, excessive agency, and runtime action governance.

## Artifacts

- tripwire-ci.result: `.tripwire/latest/tripwire-result.json`
- tripwire-ci.outDir: `/home/runner/work/agentcert-v0-smoke/agentcert-v0-smoke/.tripwire/latest`
