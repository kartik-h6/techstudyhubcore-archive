# Cloudflare & DNS

## What was learned

**[FACT]** DNS was learned as a distinct layer of the system:

- how records work
- how subdomains are created and pointed
- how a domain relates to where a site is actually hosted

Cloudflare was used for DNS management.

## The layer separation

**[LESSON]** Understanding that source code, GitHub, hosting, domain, DNS and the application are *separate layers* was one of the most useful technical insights of the project.

It explained why changing a hosting provider does not fix a domain problem, and why DNS does not need to move when hosting changes.

## Ownership as obligation

**[LESSON]** DNS was the point where the project stopped being a folder of files and became infrastructure. A domain is not an asset you own outright — it is an obligation you renew.

## Before the domain expires

**[FACT / ACTION]** The DNS configuration should be exported and kept in this archive before the domain lapses, because that configuration is otherwise lost.

## Details not available

The exact DNS records and zone configuration are not available in the current archive context.
