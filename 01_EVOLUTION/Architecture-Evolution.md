# Architecture Evolution

## Stages

**[FACT]** The architecture developed in recognisable stages:

1. **Client-side prototype** — HTML/JS with client-side rendering (TrailCode)
2. **Version control** — Git and GitHub introduced; the project became a repository
3. **Deployment** — hosting built from the repository
4. **Netlify** — used for several deployments
5. **Custom domain** — a purchased domain for the brand
6. **Cloudflare DNS** — DNS managed at Cloudflare
7. **Subdomains** — separate areas on separate subdomains
8. **Multiple independent projects** — gateway, Pharmacy, SSLC, Digital Setup, portfolio, calculator
9. **Content architecture** — a structured hierarchy with resources attached to topic pages
10. **AI-assisted development** — local and hosted AI tools integrated into the workflow
11. **Retirement** — public infrastructure retired, knowledge preserved

## The layer model

**[LESSON]** The most valuable architectural insight was that these are *separate layers*:

```text
Source code
→ GitHub
→ Hosting
→ Domain
→ DNS
→ Application
```

Understanding the separation explained why changing one layer does not fix a problem belonging to another.

## Notable problems encountered

**[FACT]** At one point there were domain/subdomain association problems with Netlify.

**[LESSON]** Changing hosting providers does not eliminate the underlying responsibility of maintaining the platform. Also, Cloudflare DNS does not need to be moved simply because hosting changes.

## Details not available

A formal architecture diagram, if one was drawn, is not available in the current archive context.
