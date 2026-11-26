---
"pnpm": patch
---

A file that `include` delegates `overrides` or `permissions` to can now set `overrides.unused` or `permissions.unused`. pnpm failed with `ERR_PNPM_SETTING_NOT_DELEGATED` unless the policy was delegated separately.
