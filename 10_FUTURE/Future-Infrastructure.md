# Future Infrastructure

## Principles

1. **Free-first.** Personal hosting costs nothing and cannot lapse on you.
2. **Personal identity for personal assets.** Brand domains only when a brand genuinely exists.
3. **One deployment pipeline.** Git-backed, repeatable, documented.
4. **No subdomain until it is earned** — real traffic *and* a named owner.
5. **Secrets never in the frontend or the repository.**

## A suggested shape for a future solo project

```text
personal identity (free host or personal domain)
├── /            → portfolio and writing
├── /notes       → knowledge base
└── /tools       → small interactive utilities
```

One repository, one deployment, paths instead of subdomains.

## Where PMAS fits

**[FACT]** PMAS is a product with a genuine use case, tied to the author's M.Pharm work. Unlike the static brand areas, it warrants real architecture — including a backend and proper data handling — and the security principles in `04_SECURITY/`.

## Details not available

Any architecture decisions already made for PMAS are not part of this archive.
