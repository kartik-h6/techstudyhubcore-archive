# Application Security Principles

Principles adopted after the prototype phase, stated for future work.

## Authentication vs authorization

- **[LESSON]** Authentication and authorization are different things. Proving who someone is does not establish what they may do.
- Permissions must be checked **server-side** on every protected request.
- Never trust frontend-supplied user IDs, roles, or prices.

## Data boundaries

- Validate data at backend boundaries.
- Prevent users from accessing each other's data.
- Minimize access to sensitive data — collect and expose as little as possible.

## Secrets

- Keep secret API keys out of frontend code.
- Keep `.env` files out of Git and public folders.
- Scan Git history for leaked secrets; rotate anything exposed.
- Never hardcode production credentials.
- Avoid publishing private infrastructure information.

## Design posture

- Design for misuse and failure, not only for successful flows.
- Document security assumptions so they can be reviewed later.

## Relevance to PMAS

**[FACT]** These principles became directly relevant when work began on **PMAS**, where medication and adherence data carry privacy obligations that a static educational site never had.

## Details not available

Specific implementation details for PMAS are not part of this archive.
