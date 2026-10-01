# Screenshots

Visual evidence of the TechStudyHubCore sites, captured before the domain expires.

**Status: 8 screenshots captured and published.**

## Why screenshots matter

When the domain expires, the pages are gone. A screenshot is the only record of what a visitor actually saw. It also proves the site was live, and at which URL.

## What has been preserved

- **Root gateway** — `[CAPTURED]`
- **Major subdomains** — pharmacy, digital setup, portfolio, CGPA calculator, SSLC — `[CAPTURED]`
- **Important project pages** — landing pages of each area — `[CAPTURED]`
- **Infrastructure panels** — Cloudflare DNS `[CAPTURED]`, Netlify projects `[CAPTURED]`
- **Mobile view** — `[NOT CAPTURED]`

## Capture guidance

- Keep the browser address bar visible where it helps prove URL identity.
- Prefer full-page captures over cropped fragments.
- Capture desktop and mobile versions of the same page where possible.
- Do not capture anything showing private data, credentials, or personal information.

## Where the files are stored

All captures are stored as **release assets** on the `archive-evidence-v1` release, not as files in this directory. Binary files of this size cannot be committed through the archive's authoring toolchain.

Release: https://github.com/kartik-h6/techstudyhubcore-archive/releases/tag/archive-evidence-v1

Each asset is downloadable by its original filename from that release page.

## Inventory

| File | Area | URL shown in capture | Size | Status |
|---|---|---|---|---|
| `techstudyhubcore.in.png` | Root gateway | not visible | 567 KB | `[CAPTURED]` |
| `pharmacy.techstudyhubcore.in.png` | Pharmacy / B.Pharm | `pharmacy.techstudyhubcore.in` | 328 KB | `[CAPTURED]` |
| `digitalsetup.techstudyhubcore.in.png` | Digital Setup | `digitalsetup.techstudyhubcore.in` | 258 KB | `[CAPTURED]` |
| `portfolio.png` | Portfolio | `portfolio.techstudyhubcore.in` | 387 KB | `[CAPTURED]` |
| `cgpacalculator.techstudyhubcore.in.png` | CGPA Calculator | `cgpacalculator.techstudyhubcore.in` | 221 KB | `[CAPTURED]` |
| `sslc.techstudyhubcore.in.png` | SSLC | not visible | 237 KB | `[CAPTURED]` |
| `cloudfare.png` | Cloudflare DNS panel | `dash.cloudflare.com` (redacted) | 272 KB | `[CAPTURED]` — redacted |
| `netlify.png` | Netlify projects panel | `app.netlify.com/teams/…/projects` | 295 KB | `[CAPTURED]` — redacted |

### What each capture shows

**`techstudyhubcore.in.png` — root gateway.** Heading *TechStudyHubCore*; navigation Explore / About / Contact; tagline *ONE ECOSYSTEM — MULTIPLE FOCUSED SYSTEMS*; prompt *What do you need today?*; description of a clarity-first academic and digital ecosystem; calls to action *Explore Destinations* and *Get Help Finding*.

**`pharmacy.techstudyhubcore.in.png` — Pharmacy Hub.** Heading *The B.Pharm syllabus, clearly mapped. The tools you actually need.* Content built on the official PCI 2026 syllabus; calls to action *Download Syllabus*, *CGPA Calculator*; a Resources section of downloadable guides.

**`digitalsetup.techstudyhubcore.in.png` — Digital Setup.** Heading *Your business is already local. Make it easier to find, trust, and contact.* Navigation: Solutions, How It Works, Live Examples, Pricing, FAQ. Describes combining Google search visibility, a mobile-first digital hub, and a direct WhatsApp enquiry flow.

**`portfolio.png` — Portfolio.** Heading *B.Pharm Health-Tech AI Specialist*; name KARTIK H. Navigation: About, Case Study, Projects, Visuals, Certs. Statistics displayed at capture: 100+ Students Reached, 5 Languages, 3 Live Projects, 2 AI Certs.

> Those statistics are recorded as **what the page displayed at capture** — the site's own figures, preserved as evidence, and not independently verified.

**`cgpacalculator.techstudyhubcore.in.png` — SGPA / CGPA calculator.** Heading *Calculate Your SGPA & CGPA Clearly*; an SGPA calculator with a semester dropdown auto-filling subjects (labelled PCI B.Pharm 2026 NEP Syllabus); a sidebar labelled PMAS-ToC.

**`sslc.techstudyhubcore.in.png` — SSLC landing page.** Heading *Learn Clearly. Revise Smartly. Score Confidently.* Announcement bar *KARNATAKA SSLC — PILOT BATCH NOW OPEN*. Navigation: Why This Exists, Classroom, Mentor, Reviews, FAQ, with a Reserve Seat button. Describes a structured digital classroom for Karnataka SSLC 10th standard students — visual notes, NotebookLM revision, solved PYQs, direct mentor support. Bilingual: the hero is repeated in Kannada. Calls to action: *Join Pilot Batch — Freemium*, *See What's Inside*. Feature tags: Karnataka SSLC · Full Syllabus; in Kannada + English; 25 Seats Only; Phone-First; NotebookLM Powered.

> The address bar is **not visible** in the SSLC capture. The subdomain's existence is confirmed by its DNS record; this image does not itself show the URL.

**`cloudfare.png` — Cloudflare DNS panel.** Source for the records in `../dns/DNS-Snapshot.md`. Shows 8 DNS rows and reports 12 of 200 records in use.

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
| Capture date | Originals captured by the author (exact dates not recorded); uploaded to the archive 2026-10-01 |
| Evidence source | Author's own screenshots; Cloudflare and Netlify dashboards |
| Evidence status | `[CAPTURED]` — 8 files |

## Still to capture

- Mobile views of the sites — `[NOT CAPTURED]`
- Cloudflare zone export (all 12 records, untruncated) — `[NOT CAPTURED]`
- Vercel projects, if any exist — `[NOT CAPTURED]`
- Registrar / expiry details — `[NOT CAPTURED]`

## Reminder

Do not add placeholder or reconstructed images. If a page can no longer be captured, record it as `[UNAVAILABLE]` instead.
