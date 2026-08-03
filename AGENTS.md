# AGENTS.md

## Scope

This guide applies to `infrastructure/rincorpes-workflows`.

## Purpose

This subtree contains reusable GitHub Actions workflows shared across personal
projects and published repositories.

## Working Rules

- Prefer reusable, parameterized workflow logic over repo-specific assumptions.
- Be conservative with workflow interface changes because downstream repos may
  depend on them.
- Keep action versions, inputs, and required secrets explicit.
- Update the local README when workflow usage meaningfully changes.

## Verification

- Validate YAML carefully.
- Check that changed inputs still match the calling workflows in consuming
  repos when possible.
