# Screenshots

Visual evidence of the TechStudyHubCore sites, captured before the domain expires.

**Status: 7 screenshots captured** — 4 site captures published, 3 further captures (gateway, Cloudflare, Netlify) prepared with redactions.

## Why screenshots matter

When the domain expires, the pages are gone. A screenshot is the only record of what a visitor actually saw. It also proves the site was live, and at which URL.

## What should be preserved

- **Root gateway** — `[CAPTURED]`
- **Major subdomains** — pharmacy, digital setup, portfolio, CGPA calculator `[CAPTURED]`; SSLC `[NOT CAPTURED]`
- **Important project pages** — `[CAPTURED]` (landing pages)
- **Mobile view** — `[NOT CAPTURED]`
- **Infrastructure panels** — Cloudflare DNS `[CAPTURED]`, Netlify projects `[CAPTURED]`

## Capture guidance

- Keep the browser address bar visible where it helps prove URL identity.
- Prefer full-page captures over cropped fragments.
- Capture desktop and mobile versions of the same page where possible.
- Do not capture anything showing private data, credentials, or personal information.

## Where the files are stored

The site captures are stored as **release assets** on the `archive-evidence-v1` release, not as files in this directory. Binary files of this size cannot be committed through the archive's authoring toolchain.

Release: https://github.com/kartik-h6/techstudyhubcore-archive/releases/tag/archive-evidence-v1

Each asset is downloadable by its original filename from that release page.

## Inventory

| File | Area | URL shown in capture | Status |
|---|---|---|---|
| `digitalsetup.techstudyhubcore.in.png` | Digital Setup | `digitalsetup.techstudyhubcore.in` | `[CAPTURED]` |
| `pharmacy.techstudyhubcore.in.png` | Pharmacy / B.Pharm | `pharmacy.techstudyhubcore.in` | `[CAPTURED]` |
| `portfolio.png` | Portfolio | `portfolio.techstudyhubcore.in` | `[CAPTURED]` |
| `cgpacalculator.techstudyhubcore.in.png` | CGPA Calculator | `cgpacalculator.techstudyhubcore.in` | `[CAPTURED]` |
| `techstudyhubcore.in.png` | Root gateway | `techstudyhubcore.in` | `[CAPTURED]` — pending asset attachment |
| `cloudfare.png` | Cloudflare DNS panel | `dash.cloudflare.com` (redacted) | `[CAPTURED]` — redacted, pending asset attachment |
| `netlify.png` | Netlify projects panel | `app.netlify.com/teams/…/projects` | `[CAPTURED]` — redacted, pending asset attachment |

### What the newer captures show

**`techstudyhubcore.in.png` — root gateway.** Heading *TechStudyHubCore*; navigation Explore / About / Contact; tagline *ONE ECOSYSTEM — MULTIPLE FOCUSED SYSTEMS*; prompt *What do you need today?*; description of a clarity-first academic and digital ecosystem; calls to action *Explore Destinations* and *Get Help Finding*. No sensitive content.

**`cloudfare.png` — Cloudflare DNS panel.** Source for the records recorded in `../dns/DNS-Snapshot.md`. Shows 8 DNS rows and reports 12 of 200 records in use.

**`netlify.png` — Netlify projects panel.** Source for the project list in `../deployments/Hosting-Inventory.md`. Shows 6 projects.

## Redactions applied before publication

| File | Removed | Reason |
|---|---|---|
| `cloudfare.png` | Browser chrome / address bar | It contained a Cloudflare session token and the account ID |
| `netlify.png` | Sidebar account block | It contained the account holder's name and email address |

Both redactions were verified: no token, account ID, or email remains visible, and the evidence content stays fully readable. The unredacted originals were **not** published and remain with the author.

## Prohibited content

Screenshots must not contain credentials, tokens, `.env` values, private account pages, private patient or academic information, or anything from an authenticated dashboard that is not public information.

## Capture metadata

| Field | Value |
|---|---|
| Capture date | Originals captured by the author (exact date not recorded); uploaded to the archive 2026-10-01 |
| Evidence source | Author's own screenshots, with the browser address bar visible |
| Evidence status | `[CAPTURED]` — 7 files |

## Still to capture

- SSLC page screenshot — `[NOT CAPTURED]`
- Mobile views — `[NOT CAPTURED]`
- Cloudflare zone export (all 12 records, untruncated) — `[NOT CAPTURED]`
- Vercel projects, if any exist — `[NOT CAPTURED]`

## Reminder

Do not add placeholder or reconstructed images. If a page can no longer be captured, record it as `[UNAVAILABLE]` instead.
