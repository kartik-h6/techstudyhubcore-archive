# DNS Snapshot

Record of the domain and its DNS configuration as it existed at retirement.

**Status: partially captured** — read from a Cloudflare dashboard screenshot. 8 of 12 records are visible; the browser chrome was redacted before publication.

## Domain

| Field | Value |
|---|---|
| Domain | `techstudyhubcore.in` |
| Registrar | Evidence not yet captured. |
| Registration / ownership status | Evidence not yet captured. |
| Expiry date | Evidence not yet captured. |
| Auto-renew setting | Evidence not yet captured. |

## Authoritative DNS

| Field | Value |
|---|---|
| Authoritative DNS provider | **Cloudflare** — `[CAPTURED]` |
| Nameservers | Evidence not yet captured. |
| DNSSEC status | Evidence not yet captured. |
| Record usage | 12 of 200 available records used (per the capture) |

## DNS records

Read from the Cloudflare DNS Records panel. Values are recorded exactly as shown, including truncation.

| Name | Type | Content (as shown) | Proxy status | TTL |
|---|---|---|---|---|
| `techstudyhubcore.in` | A / CNAME — **confirm** | `75.2.60.5` | Proxied | Auto |
| `cgpacalculator.techstudyhubcore.in` | CNAME | `sgpa-cgpa-calculator…` (truncated) | Proxied | Auto |
| `digitalsetup.techstudyhubcore.in` | CNAME | `tshdigitalsetup.netlify…` (truncated) | Proxied | Auto |
| `pharmacy.techstudyhubcore.in` | CNAME | `9824962f684b94cd7…` (truncated) | DNS only | Auto |
| `portfolio.techstudyhubcore.in` | CNAME | `kartik-h-portfolio.netli…` (truncated) | Proxied | Auto |
| `sslc.techstudyhubcore.in` | CNAME | `8924e04445e4seca04…` (truncated) | DNS only | Auto |
| `www.techstudyhubcore.in` | CNAME | `techstudyhubcore.in` | Proxied | Auto |
| `techstudyhubcore.in` | MX | `route3.mx.cloudflare…` (truncated) | DNS only | Auto |

**Notes**

- **12 records total; 8 visible in the capture. Four records are not captured.**
- The root record's type was read inconsistently between inspections (CNAME and A) — needs confirmation against the live panel.
- Content values are truncated in the screenshot; the full values must be read from the DNS panel or a zone export.

## Important subdomains

See `Subdomain-Inventory.md`. The records above confirm that `cgpacalculator`, `digitalsetup`, `pharmacy`, `portfolio`, `sslc` and `www` all existed in DNS.

## Cloudflare configuration notes

- DNS Setup: **Full**
- Proxy status per record: see the table above (`pharmacy` and `sslc` are DNS-only; the others are proxied)
- Page rules / redirect rules: Evidence not yet captured.
- SSL/TLS mode: Evidence not yet captured.

## Capture metadata

| Field | Value |
|---|---|
| Capture date | Screenshot uploaded 2026-10-01 (original capture date not recorded) |
| Evidence source | Cloudflare dashboard → DNS → Records (`cloudfare.png`) |
| Evidence status | `[CAPTURED]` — partial (8 of 12 records) |

## Redaction note

The original capture's browser address bar contained a **Cloudflare session token and the account ID**. Those were removed from the published copy before upload. No credentials, tokens, or account identifiers are published in this archive.

## How to complete

Export the full zone from Cloudflare (DNS → Export) to capture all 12 records with untruncated values, then replace the table above.
