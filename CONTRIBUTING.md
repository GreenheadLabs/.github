# Contributing to Greenhead Labs

Thanks for your interest in contributing! These guidelines apply across all
[@GreenheadLabs](https://github.com/GreenheadLabs) repositories unless a specific
repository provides its own `CONTRIBUTING.md`.

## Code of Conduct

By participating, you agree to uphold our [Code of Conduct](CODE_OF_CONDUCT.md).
Please report unacceptable behavior to **conduct@greenhead.io**.

## Ways to contribute

- **Report a bug** — open a [bug report](../../issues/new?template=bug_report.yml).
- **Request a feature** — open a [feature request](../../issues/new?template=feature_request.yml).
- **Improve docs** — typo fixes and clarifications are always welcome.
- **Submit code** — see the workflow below.

> [!IMPORTANT]
> **Never open a public issue for a security vulnerability.** Follow our
> [Security Policy](SECURITY.md) for responsible disclosure. Never share private
> keys, seed phrases, or secrets in an issue, PR, commit, or log.

## Development workflow

1. **Fork** the repository and create a branch from `main`.
   ```bash
   git checkout -b feat/short-description
   ```
2. **Make your change.** Keep it focused — one logical change per pull request.
3. **Follow existing conventions** for the project's language and structure. If a
   repo defines linters/formatters or tests, run them locally before pushing.
4. **Commit** using clear, descriptive messages. We prefer
   [Conventional Commits](https://www.conventionalcommits.org/):
   ```text
   feat: add x402 payment retry logic
   fix: handle XRPL tx timeout
   docs: clarify DID setup steps
   ```
5. **Open a pull request** against `main` and fill out the PR template. Link any
   related issues (e.g. `Closes #123`).

## Pull request expectations

- Describe **what** changed and **why**.
- Keep PRs small and reviewable; split unrelated changes.
- Ensure CI (if configured) passes.
- Be responsive to review feedback — we aim to review promptly.

## Commit signing

We encourage signed commits where possible. See
[GitHub's guide on commit signature verification](https://docs.github.com/en/authentication/managing-commit-signature-verification).

## Questions

Not sure where to start? See [SUPPORT.md](SUPPORT.md) or reach out via the links
on our [organization profile](https://github.com/GreenheadLabs).

We appreciate your contributions. 🟢
