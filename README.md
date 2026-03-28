# Stratum — Incremental Consensus System

**Knowledge doesn't arrive complete. It accretes.**

Stratum-ICS is an open platform for collaborative, peer-reviewed scientific knowledge management.
It lets researchers and teams build shared knowledge bases where claims earn confidence through
structured review, versioning, and incremental consensus — not authority.

---

## What Stratum Does

- **Capture knowledge as nodes** — notes linked to papers, sources, and each other
- **Propose changes formally** — every edit to a shared note becomes a proposal with rationale
- **Build consensus through review** — proposals pass through a quorum of reviewers before merging
- **Track confidence over time** — nodes carry confidence scores that decay without affirmation
- **Detect semantic conflicts** — embedding-based similarity flags contradictions before they merge
- **Collaborate on shared vaults** — teams fork, branch, and sync knowledge like source code

---

## Who It's For

| | |
|---|---|
| **Researchers** | Structure findings, track confidence, resolve contested claims formally |
| **Research teams** | Shared knowledge bases with proposal-based editing and reviewer routing |
| **Institutions** | Self-hostable, privacy-preserving, no vendor lock-in |
| **Developers** | Open platform — contribute to the core, build integrations, extend the protocol |

---

## The Mission

Science accumulates through disagreement, revision, and eventual convergence.
Most knowledge tools ignore this — they treat the latest edit as truth.

Stratum treats knowledge as **a living graph that earns its confidence**.
Our roadmap:

- **Now** — Self-hosted collaborative research platform (FastAPI + React, Docker-ready)
- **Next** — Local-first mode: work offline, sync selectively, own your data entirely
- **Later** — Open protocol for federated knowledge exchange across institutions

---

## Get Started

```bash
git clone https://github.com/stratum-ics/stratum
cp .env.example .env
docker compose up
```

Docs → [wiki](../../wiki) · API → `http://localhost:8000/docs`

---

## Contributing

All contributors welcome — researchers, engineers, designers, technical writers.

Read `CONTRIBUTING.md` → open an issue → send a proposal.

*We practice what we build: changes go through review.*

---

## License

MIT
