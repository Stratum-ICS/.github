# Contributing to Stratum-ICS

Thank you for contributing. Stratum is built on the principle that good ideas earn their place through review — we apply the same standard to code.

## Ways to Contribute

- **Bug reports** — open an issue using the Bug Report template
- **Feature proposals** — open an issue using the Feature Request template
- **Research feedback** — if you use Stratum in an academic context, use the Research Feedback template
- **Code** — fix bugs, implement features, improve performance
- **Docs** — improve the wiki, add examples, fix typos
- **Design** — UI/UX improvements, icons, accessibility

---

## Before You Start

1. **Search open issues** — your idea or bug may already be tracked.
2. **Open an issue first** for non-trivial changes — align on approach before writing code.
3. **Check the roadmap** in the main `stratum` repo for planned work.

---

## Development Setup

```bash
git clone https://github.com/Stratum-ICS/stratum
cd stratum
cp .env.example .env

# Backend
cd backend
pip install -e ".[dev]"
uvicorn stratum.main:app --reload

# Frontend (separate terminal)
cd frontend
npm install
npm run dev
```

Tests:
```bash
# Backend
cd backend && pytest

# Frontend (when configured)
cd frontend && npm test
```

---

## Pull Request Process

1. Fork the repo and create a branch from `master`.
2. Make your changes — keep scope focused.
3. Ensure tests pass.
4. Open a PR against `master` with a clear description of *what* and *why*.
5. At least one maintainer review is required before merge.
6. Squash commits if requested.

### PR Title Convention

Use [Conventional Commits](https://www.conventionalcommits.org/) lowercase:

```
feat: add reviewer routing by expertise tag
fix: decay worker skips notes with no track
docs: update vault sync walkthrough
```

---

## Code Style

| Layer | Convention |
|---|---|
| Python | 3.10+, type hints in signatures, `unittest` for tests |
| TypeScript | strict mode, no `any` unless unavoidable |
| CSS | Tailwind utility classes; no inline styles |
| Commits | Conventional Commits, no period at end |

---

## Community Standards

All contributors are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

*We practice what we build: changes go through review.*
