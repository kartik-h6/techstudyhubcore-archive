# Subdomain Inventory

Inventory of the subdomains used by the TechStudyHubCore ecosystem.

**Status: 7 hostnames confirmed** (root, `www`, and five subdomains), from screenshot evidence and the Cloudflare DNS capture. Hosting destinations are partially known.

## Root domain

| Field | Value |
|---|---|
| Root domain | `techstudyhubcore.in` |
| Root purpose | Gateway (front door / routing layer) |
| Root status | `[CAPTURED]` — screenshot and DNS record |

## Confirmed hostnames

| Subdomain | Purpose | Hosting destination | Existence | Evidence source |
|---|---|---|---|---|
| `techstudyhubcore.in` (root) | Gateway | `75.2.60.5` (proxied) — consistent with Netlify | `[CAPTURED]` | DNS record + screenshot |
| `www.techstudyhubcore.in` | Redirect / alias of root | CNAME → `techstudyhubcore.in` | `[CAPTURED]` | DNS record |
| `pharmacy.techstudyhubcore.in` | Pharmacy / B.Pharm learning area | CNAME target truncated (DNS only) | `[CAPTURED]` | Screenshot + DNS record |
| `digitalsetup.techstudyhubcore.in` | Digital Setup service concept | `tshdigitalsetup.netlify…` | `[CAPTURED]` | Screenshot + DNS record |
| `portfolio.techstudyhubcore.in` | Personal portfolio | `kartik-h-portfolio.netli…` | `[CAPTURED]` | Screenshot + DNS record |
| `cgpacalculator.techstudyhubcore.in` | SGPA / CGPA calculator utility | `sgpa-cgpa-calculator…` | `[CAPTURED]` | Screenshot + DNS record |
| `sslc.techstudyhubcore.in` | School-level learning area | CNAME target truncated (DNS only) | `[CAPTURED]` | DNS record |

## Known areas of the ecosystem (from the historical documentation)

| Area | Subdomain | Confirmed? |
|---|---|---|
| Gateway | `techstudyhubcore.in` (root) | `[CAPTURED]` |
| Pharmacy / B.Pharm | `pharmacy.techstudyhubcore.in` | `[CAPTURED]` |
| SSLC | `sslc.techstudyhubcore.in` | `[CAPTURED]` (DNS record; no screenshot yet) |
| Digital Setup | `digitalsetup.techstudyhubcore.in` | `[CAPTURED]` |
| Portfolio | `portfolio.techstudyhubcore.in` | `[CAPTURED]` |
| CGPA Calculator | `cgpacalculator.techstudyhubcore.in` | `[CAPTURED]` |

## Observations

- `pharmacy` and `sslc` were configured **DNS only** (not proxied) while the others were proxied — worth noting as a configuration difference.
- Two of the CNAME targets are opaque identifiers rather than readable hostnames (truncated in the capture).

## Capture metadata

| Field | Value |
|---|---|
| Capture date | Evidence uploaded 2026-10-01 (original capture dates not recorded) |
| Evidence source | Screenshots with visible address bar; Cloudflare DNS Records panel |
| Evidence status | `[CAPTURED]` — 7 hostnames |

## Reminder

A subdomain is recorded as confirmed here only once it has been observed in evidence. Do not infer subdomains from the documentation.
