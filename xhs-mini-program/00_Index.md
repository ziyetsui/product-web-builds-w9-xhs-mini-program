# w9/xhs-mini-program

- Area: 20-29 Product and Web Builds
- Workstream: w9
- Created: 2026-06-10
- Scope: 小红书小程序产品相关的产品原型、需求、设计、开发与发布资料。

## Repository layout

- `app/`: native WeChat Mini Program frontend.
- `backend/`: standalone mini-program backend, tests, templates, and runtime assets.
- `specs/w9/`: workstream-level source and migration notes.
- `xhs-mini-program/`: product research and index documents.

The implementation was recovered from the `miniapp/` subtree of commit
`45d1700c5c8c1bbeb97330dc9a32422d2bbb4a29` in the original Queencard
repository. Web code remains in that repository and is not duplicated here.

## Verification

```bash
(cd app && npm run validate)
(cd backend && npm test)
```
