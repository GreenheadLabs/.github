# Security Policy

Greenhead Labs builds crypto infrastructure, autonomous on-chain agents, and
payment systems. We take security seriously and appreciate the work of security
researchers who help keep our users and funds safe.

## Reporting a vulnerability

**Please do not report security vulnerabilities through public GitHub issues,
discussions, pull requests, or social media.**

Instead, use one of the following private channels:

1. **GitHub Private Vulnerability Reporting (preferred).** On the affected
   repository, go to the **Security** tab → **Report a vulnerability**. This opens
   a private advisory visible only to maintainers.
2. **Email** — send details to **security@greenhead.io**. If you'd like to encrypt
   your report, request our PGP key first.

### What to include

To help us triage quickly, please provide:

- A clear description of the issue and its potential impact
- Steps to reproduce (proof-of-concept, scripts, or transactions where relevant)
- Affected repository, component, endpoint, contract, or network (e.g. XRPL
  mainnet/testnet, Flare)
- Any relevant logs, transaction hashes, or addresses
- Your assessment of severity and any suggested remediation

> [!WARNING]
> Never include private keys, seed phrases, mnemonics, or other secrets in your
> report. We will never ask you for them.

## Our commitment

When you report a vulnerability responsibly, we will:

- **Acknowledge** your report within **3 business days**.
- Provide an initial **assessment and triage** within **7 business days**.
- Keep you informed of remediation progress.
- **Credit** you for the discovery once the issue is resolved, if you wish.

## Scope

In scope:

- Code and services in [@GreenheadLabs](https://github.com/GreenheadLabs)
  repositories
- Our hosted services, including `greenhead.io` and `x402.greenhead.io`
- On-chain components we operate (XRPL / Flare)

Out of scope (examples):

- Vulnerabilities in third-party dependencies without a demonstrated impact on us
  (please report those upstream)
- Social engineering, phishing, or physical attacks against staff
- Automated scanner output without a working proof-of-concept
- Denial-of-service via volumetric traffic

## Safe harbor

We consider security research conducted in good faith and in accordance with this
policy to be authorized. We will not pursue or support legal action against
researchers who:

- Make a good-faith effort to avoid privacy violations, data destruction, and
  service disruption
- Only interact with accounts, funds, or data they own or have explicit
  permission to test
- Give us a reasonable time to remediate before any public disclosure

Thank you for helping keep Greenhead Labs and our users secure.
