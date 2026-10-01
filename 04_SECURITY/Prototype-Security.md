# Prototype Security

## The context

**[FACT]** TrailCode — the early prototype — contained prototype-level security concepts:

- hardcoded admin credentials
- localStorage-based administration
- client-side assumptions about trust

**[LESSON]** These were not suitable as production security.

## Why this is documented rather than hidden

This archive deliberately preserves the mistakes. They are the most transferable part of the experience.

## The lessons drawn

- **localStorage is not a secure backend.** Client-side storage can be read and modified by the user.
- **Frontend authentication is not sufficient.** Anything enforced only in the browser can be bypassed.
- **Hardcoded credentials must never be used for real production security.** They are readable by anyone who can see the code.
- **Authorization must happen server-side.** Hiding a button is not access control.
- **Prototypes should not automatically become production architecture.** A prototype is a learning device; promoting it unchanged carries its shortcuts forward.

## The transfer

**[LESSON]** These prototype shortcuts are exactly what `04_SECURITY/Application-Security-Principles.md` exists to prevent in future work — including PMAS.
