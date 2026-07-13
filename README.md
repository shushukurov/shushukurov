# Shakhzod

Fintech founder. I run my startup on AI agents — they write the code, run the research, maintain the knowledge base, and quiz me on the results. The useful parts get published here.

## Agent artifacts

One artifact per repo, each installable in one line.

| Artifact | What it does |
|---|---|
| [quiz-me](https://github.com/runsagents/quiz-me) | Your agent quizzes **you** on your repo's recent changes, honest grading. Move fast *and* understand what you're shipping |
| [rival-review](https://github.com/runsagents/rival-review) | Every agent-written diff gets attacked by a **different model** before merge. Same model reviewing itself is homework marking itself |
| [airlocks](https://github.com/runsagents/airlocks) | Trust state, not words: "merged / deployed / passing" gets verified at the system of record, never grepped from logs |
| [voice-calibration](https://github.com/runsagents/voice-calibration) | Method + template for agent drafts that actually sound like you, calibrated on your own message history |

## Operating principles

- **One writer per worktree.** Parallel agents get isolated checkouts, or they corrupt each other's work
- **Review by a rival model.** A model can't catch its own blind spots; a different one has different ones
- **Verify state, not words.** "Done" is a claim. A green build, a live build number, a passing quiz — that's evidence

## Background

Ex fraud & payments data scientist — decisioning used by tier-1 banks. Co-founder & Chief Risk and Data Officer at [IMAN](https://imanum.app/en). Now building fintech #2 with the fleet.

**X: [@runsagents](https://x.com/runsagents)** — the operating log.
