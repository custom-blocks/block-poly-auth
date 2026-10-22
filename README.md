# Poly Auth (test Block)

Use with **polyglot-base**, ideally together with **block-poly-observability**.

- Same versions as Observability for `zod`, `opentelemetry-sdk`, `tokio`,
  `golang.org/x/sync` and the Gemfile's `opentelemetry-sdk`: identical
  versions must merge, not conflict.
- Adds a root `README.md`, so the "Dependencies to install" section must be
  appended to it instead of creating a fresh README.
- Targets `apps/web/packge.json` (typo): listed in the README, build continues.
- Targets `infra/terraform/versions.tf` and `services/billing/Gemfile`: listed.
