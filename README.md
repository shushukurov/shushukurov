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
| [fraud-lens](https://github.com/runsagents/fraud-lens) | Your agent reviews money-adjacent flows like a fraud analyst: velocity, replay, ATO cash-out, refund abuse, promo economics |

## Operating principles

- **One writer per worktree.** Parallel agents get isolated checkouts, or they corrupt each other's work
- **Review by a rival model.** A model can't catch its own blind spots; a different one has different ones
- **Verify state, not words.** "Done" is a claim. A green build, a live build number, a passing quiz — that's evidence

## Before the hype

The dates are the receipts, so these stay public and archived instead of polished away:

- [FaceMaskDetector](https://github.com/runsagents/FaceMaskDetector) — production-style computer vision (PyTorch, FaceNet, MobileNetV2, Dockerised, Azure-deployed), **January 2021**, two years before ChatGPT
- [LLM_chatbot](https://github.com/runsagents/LLM_chatbot) — GPT-4 + Pinecone RAG over large PDF sets, **June 2023**, before "RAG" was a word everyone knew
- [ML_Portfolio](https://github.com/runsagents/ML_Portfolio) — the coursework era, 2020–21, labeled as exactly that

## Background

Ex fraud & payments data scientist — decisioning used by tier-1 banks, including a reinforcement-learning fraud-policy optimiser (2023). Co-founder & Chief Risk and Data Officer at [IMAN](https://imanum.app/en). Now building fintech #2 with the fleet.

**X: [@runsagents](https://x.com/runsagents)** — the operating log.
