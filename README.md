# AION Unified API

OpenAPI specification for the APIs shared between AION and Vision Bank (reference beneficiary,
transfer, bill payment, MOI refund, user access profile, audit logs, SME validations).

- **View:** open the GitHub Pages link of this repository, or import `aion-unified-api.yaml`
  into https://editor.swagger.io (File → Import file).
- **Source of truth:** `aion-unified-api.yaml`.

## Updating

1. Create a branch, edit `aion-unified-api.yaml`, and bump `info.version`.
2. Open a pull request into `main` for review.
3. After merge, tag the version (e.g. `v1.2.0`). GitHub Pages updates automatically.
