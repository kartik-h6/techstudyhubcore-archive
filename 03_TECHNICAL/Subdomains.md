# Subdomains

## The architecture

**[FACT]** The ecosystem used a subdomain-per-area structure under the brand domain, including areas such as:

- the root gateway
- Pharmacy / B.Pharm
- SSLC
- Digital Setup
- personal portfolio

## Why subdomains felt right

- clean separation of topics
- independent deployment per area
- a platform-like appearance

## What they actually cost

**[LESSON]** Each subdomain implied:

- its own content
- its own deployment
- its own DNS record
- its own maintenance
- its own owner — and there was none

## The core lesson

> Subdomains are an organisational pattern. Adopting them without an organisation multiplies your own workload by the number of subdomains.

## The alternative

**[FUTURE IDEA]** For a solo builder, one domain with paths (for example `/pharmacy`, `/sslc`) keeps a single deployment and a single content pipeline — no multiplication.

A subdomain should be added only when an area has real traffic **and** a named owner. See `10_FUTURE/Future-Infrastructure.md`.
