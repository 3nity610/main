# Changelog

## 1.0.0 — Unreleased

- chore(devx): retain proof artifacts in CI through a privacy-checked allowlist (#398)

- Added an atomic compatibility manifest and release gate spanning frontend,
  backend, Noir circuit/verifier, and Soroban registry artifacts.
- Established the `harpocrates:silent-witness:v1` cryptographic domain and v1
  metadata, public-input, and registry interface bindings.
- Added staged rollout, rollback, artifact verification, and privacy-safe
  release signal requirements.
