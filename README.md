# Queencard Mini Program

Standalone repository for the Queencard mini-program implementation and its
product workstream documents.

## Structure

- `app/` — native WeChat Mini Program frontend.
- `backend/` — standalone Node.js backend, tests, templates, and runtime assets.
- `specs/w9/` — workstream source and migration notes.
- `xhs-mini-program/` — product research and index documents.

The implementation was recovered from the original Queencard repository at
commit `45d1700c5c8c1bbeb97330dc9a32422d2bbb4a29`. Its Web application remains in
the original repository; this repository contains only the mini-program side.

## Verify

```bash
(cd app && npm run validate)
(cd backend && npm test)
```

Copy the environment examples under `backend/` into local, ignored environment
files before configuring deployment credentials. Never commit production keys.
