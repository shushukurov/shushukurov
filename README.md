# Shakhzod

Fintech founder. I run my startup on AI agents: pick a process, design the loop, close it end to end. The useful parts get published here, distilled from running real fintech work with agents.

## Operating principles

One writer per worktree. A second, independent model attacks meaningful diffs. “Done” is checked at the system of record. Handoffs carry receipts. Unattended agents file, don't fix. The loop matters more than the prompt.

## Agent artifacts

[agent-stack](https://github.com/runsagents/agent-stack) is the map for how these pieces compose.

| Area | Artifacts |
| --- | --- |
| Money stakes | [settlement-proof](https://github.com/runsagents/settlement-proof): read-only payment evidence across processor, ledger, idempotency, and reconciliation. [route-ledger](https://github.com/runsagents/route-ledger): observed routing P&L with evidence and quality thresholds. |
| Discipline | [agent-fleet-control](https://github.com/runsagents/agent-fleet-control): separate worktrees, territory, contracts, and receipts. [airlocks](https://github.com/runsagents/airlocks): verify done at the system of record. [second-opinion](https://github.com/runsagents/second-opinion): a different model attacks meaningful diffs. [handoff-receipts](https://github.com/runsagents/handoff-receipts): validated structure for claims and checks at transfer. [night-watch](https://github.com/runsagents/night-watch): unattended, read-only sweeps that file, never fix. |
| Measurement | [second-opinion-bench](https://github.com/runsagents/second-opinion-bench): synthetic defect recall, false positives, coverage, and pair uplift. [loss-weighted-unknowns](https://github.com/runsagents/loss-weighted-unknowns): rank stated unknowns by the loss shape of being wrong. |
| Human & memory | [quiz-me](https://github.com/runsagents/quiz-me): eight-question examination on recent changes. [voice-calibration](https://github.com/runsagents/voice-calibration): corpus-derived style guide, corrected through blind tests. [memory-ledger](https://github.com/runsagents/memory-ledger): memory with provenance, scope, expiry, and action eligibility. |
| Guard | [permission-surface](https://github.com/runsagents/permission-surface): static pre-install signals, not a safety certificate. |

Background: fraud and payments data science in London, then Chief Risk and Data Officer at [IMAN](https://www.imaninvest.com/en).

**X: [@runsagents](https://x.com/runsagents)**
