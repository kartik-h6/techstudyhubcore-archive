# Security Lessons

Preserved as explicit lessons, learned through building:

1. Keep secret API keys out of frontend code.
2. Keep `.env` files out of Git and out of public folders.
3. Scan Git history for leaked secrets.
4. Rotate accidentally exposed keys.
5. Check permissions server-side on every protected request.
6. Never trust frontend-supplied user IDs, roles, or prices.
7. Prevent users from accessing each other's data.
8. localStorage authentication is not real production authentication.
9. Never hardcode production credentials.
10. Authentication and authorization are different.
11. Validate data at backend boundaries.
12. Minimize access to sensitive data.
13. Document security assumptions.
14. Avoid publishing private infrastructure information.
15. Design for misuse and failure, not only successful flows.

## Why these are recorded here

**[LESSON]** These lessons became particularly important when work began on **PMAS**, where privacy and data handling are central rather than incidental.

They arrived through building, not through a course. That is a legitimate path — provided the lessons are actually written down, which is the purpose of this file.
