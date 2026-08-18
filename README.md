# Claude Architect Lab

Hands-on exercise lab built while preparing for the **Anthropic Claude Developer & Architect certifications** (CCDV-F → CCAR-F → CCAR-Professional). Every exercise here reinforces a specific course topic with working code, measured before/after results, and documented tradeoffs — not just notes.

## Purpose

This repository turns certification study into practice. Instead of passively completing courses, each topic is paired with a runnable exercise that intentionally breaks something, measures the failure, then fixes it and re-measures. The goal is to build defensible, evidence-based intuition for the scenario-based tradeoff questions the exams are known for.

## Certification Track

| Stage | Credential | Status |
|---|---|---|
| 1 | Claude Certified Developer – Foundations (CCDV-F) | In progress |
| 2 | Claude Certified Architect – Foundations (CCAR-F) | Planned |
| 3 | Claude Certified Architect – Professional | Planned |

## Focus Areas

- **Agentic loop mechanics** — `stop_reason`-driven control flow, tool result handling, anti-pattern comparisons
- **Batch API & cost modeling** — throughput vs. latency tradeoffs, partial-failure recovery
- **Structured output & extraction** — schema design, validation-retry loops, hallucination containment, confidence-based routing
- **MCP tool design** — tool description engineering, error taxonomy, resource discovery, least-privilege tool sets
- **Claude Code workflows** — configuration hierarchy, path-scoped rules, custom commands/skills, CI/CD integration
- **Agent SDK & multi-agent orchestration** — hooks, escalation logic, sub-agent context isolation, provenance-preserving synthesis

## Repository Structure

```
info-docs/     # Personal planning docs (roadmap, exam blueprint tracking)
src/           # Exercise implementations
tests/         # Tests proving anti-patterns fail and fixes work
evals/         # Evaluation sets and measured results
docs/          # Architecture notes, decision records, diagrams
```

Each exercise documents:
- **What it proves** — the concept or exam objective it targets
- **Before/after measurements** — a concrete metric, not a subjective impression
- **Anti-pattern comparison** — the wrong approach, why it fails, and how it was fixed

## License

MIT — see [LICENSE](LICENSE).
