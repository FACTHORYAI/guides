# Contributing to Facthory Guides

Thank you for helping improve Facthory’s customer documentation.

## Source of truth

| Surface | Role |
| --- | --- |
| **Notion Documentation** | Editorial source of truth (write path) |
| **facthory.com/resource/documentation** | Canonical product UX + SEO |
| **This repository (`FACTHORYAI/guides`)** | Public Markdown mirror |

Guide content is **not** authored in GitHub.

## How to report a problem

1. Open an issue with the **[Documentation feedback](.github/ISSUE_TEMPLATE/doc-feedback.yml)** template.
2. Include:
   - Guide title or path (`docs/<section>/<slug>.md`)
   - Canonical URL on [facthory.com](https://facthory.com/resource/documentation/) if known
   - What is wrong, missing, or confusing
   - Screenshots only if they contain **no** secrets, tokens, or customer data
3. Maintainers apply accepted changes in Notion. This repo updates when the mirror is refreshed.

## Pull requests

| Allowed | Not accepted |
| --- | --- |
| Meta fixes to `README.md` / `CONTRIBUTING.md` / issue templates (rare; discuss in an issue first) | Rewrites of guide bodies under `docs/` |
| Typos reported via Issues | Adding internal engineering runbooks or architecture diagrams |
| | Committing secrets, customer data, or screenshots with PII |

PRs that change `docs/**` content will typically be closed with a request to file an issue instead.

## What not to include in issues or PRs

- API keys, tokens, connection strings, or `.env` contents
- Customer names, emails, or private operational data
- Internal infrastructure, service topology, or implementation details
- Attempts to reverse-engineer or document proprietary internals

## Code of conduct

Be respectful and constructive. We moderate issues that include abuse, spam, or leaked secrets (we will redact and close).

## Questions about the product

For product support (not documentation feedback), use in-app help or contact your Facthory account team. Marketing and sales: [facthory.com](https://facthory.com).
