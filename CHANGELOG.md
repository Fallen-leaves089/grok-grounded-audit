# Changelog

## Unreleased

- Separate deterministic package and contract checks from model-behavior evidence in the README and model-eval record format.

## 0.1.0 - 2026-11-18

- Split `grok-grounded-audit` out of the combined `grounded-audit` package.
- Keep the evidence-first audit method, read-only default, memory recorder, package verifier and Apache-2.0 licensing.
- Specialize the skill for Grok Build and the Grok model profile.
- Revalidate the host contract against the current official `xai-org/grok-build` snapshot.
- Compensate for Grok's fail-open hooks, Plan Mode shell-redirection gap, read-only-list caveats and subagent permission inheritance.
