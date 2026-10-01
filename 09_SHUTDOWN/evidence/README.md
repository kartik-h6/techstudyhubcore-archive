# Evidence Layer

This directory preserves **verifiable evidence** of the TechStudyHubCore infrastructure and public presence at the time of retirement.

> **The documentation tells the story. The evidence proves what existed.**

This layer **complements** the historical documentation — it does not replace it. Archive v1 (the historical documentation) is frozen; corrections to it should be small and deliberate.

## Why evidence is being preserved

When `techstudyhubcore.in` expires, the subdomains, the deployments, the DNS configuration and the live pages disappear with it. A future reader — the author's future self, or a future team — should be able to see not only *what was described*, but *what actually existed and how it was configured*.

## What belongs here

- **DNS** — registrar, authoritative provider, nameservers, records, subdomains, Cloudflare configuration
- **Deployments** — Netlify projects, Vercel projects, other hosts, repository mapping
- **URLs** — the root site, subdomains, repositories, portfolio, retired URLs
- **Screenshots** — visual records of the live sites before they disappear

## Rules for this directory

1. **Evidence must be captured from the actual infrastructure.** Nothing here is inferred, reconstructed, or guessed.
2. **"Evidence not yet captured." is always preferable to invented information.** If a fact cannot currently be verified, write exactly that.
3. **This directory must never contain secrets or private credentials.** See the prohibited list below.
4. **No shutdown action is performed from this directory.** It is a record, not a plan of execution.

## NEVER ARCHIVE

The following must never be placed in this repository:

- `.env` files
- API keys
- passwords
- tokens
- private OAuth credentials
- private patient or academic information
- private account exports

Where a record legitimately contains a sensitive value (for example, a DNS verification TXT token), **redact the value** and note that it was redacted.

The archive should itself demonstrate the security lessons recorded in `04_SECURITY/`.

## Evidence-status convention

Every evidence item in this layer carries one of these statuses:

| Status | Meaning |
|---|---|
| `[CAPTURED]` | Evidence has been obtained and stored in this archive |
| `[NOT CAPTURED]` | Evidence exists and can still be obtained, but has not been yet |
| `[UNAVAILABLE]` | Evidence existed but can no longer be obtained |
| `[NOT APPLICABLE]` | The item never applied to this project |

## Capture metadata

Each template records:

- **Capture date** — when the evidence was actually obtained (not the date this template was created)
- **Evidence source** — where it came from (for example: Cloudflare dashboard, Netlify dashboard, registrar account, browser)
- **Evidence status** — one of the four statuses above

## Suggested manual capture order

1. Cloudflare (DNS)
2. Netlify (deployments)
3. Vercel (deployments, if any)
4. Domain registrar (ownership and expiry)
5. GitHub (repositories)
6. Live URLs and screenshots

## Current state

**Evidence not yet captured.** No DNS records, deployments, URLs, or screenshots have been captured into this layer yet.
