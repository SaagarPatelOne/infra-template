# infra-template

This repository is the starter template for infrastructure, operations, environment, and automation repositories in the `SaagarPatelOne` organization.

It stays tool-agnostic, but it assumes the repository may affect environments, credentials, deployment flow, or operational safety.

## What this template gives you

- the org baseline for CI, secret scanning, and pull-request hygiene
- lightweight contribution and security guidance
- CODEOWNERS and editor defaults
- a starting point for documenting environment scope, rollout, and rollback expectations

## Good fit

- infrastructure-as-code repositories
- environment configuration repos
- deployment automation repos
- operations and platform tooling

## First edits to make

1. Replace this README with environment scope, ownership, and blast-radius notes.
2. Document rollback expectations before making sensitive changes.
3. Add stack-specific ignores once the infra toolchain is chosen.
4. Add validation commands only when they are real and safe to run.

## Baseline expectations

- Keep the default branch as `main`.
- Prefer pull requests for non-trivial changes.
- Treat secrets and state files as out of repo.
- Call out environment impact, rollback path, and change risk in pull requests.
