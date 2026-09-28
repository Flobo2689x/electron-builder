---
"app-builder-lib": patch
---

fix: merge the update info of a target into `latest*.yml` with `deepAssign`, which ignores `__proto__`, `constructor` and `prototype` keys
