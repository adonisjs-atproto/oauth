---
'@adonisjs-atproto/oauth': major
---

Rename the package to the `@adonisjs-atproto` org scope: `@thisismissem/adonisjs-atproto-oauth` is now published as `@adonisjs-atproto/oauth`.

This is a breaking change. To upgrade:

- Replace the dependency `@thisismissem/adonisjs-atproto-oauth` with `@adonisjs-atproto/oauth` in your `package.json`.
- Update all imports, including subpath imports such as `@adonisjs-atproto/oauth/auth/provider` and the `@adonisjs-atproto/oauth/provider` provider registration in `adonisrc.ts`.
