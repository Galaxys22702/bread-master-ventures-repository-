# Security

## Public repository warning

This repository is public. Treat every committed file as information that may be copied, indexed or cached.

## Never commit secrets or sensitive records

Do not add:

- passwords, passphrases or recovery codes
- API keys, access tokens or private keys
- bank account or payment-card details
- Social Security numbers or tax IDs
- identity documents
- private addresses when they are not intentionally public
- confidential contracts
- personal information about programme participants, customers, employees or applicants

Use placeholders such as `REDACTED`, `EXAMPLE_ONLY` or environment-variable names when documentation needs to show where a value belongs.

## If sensitive information is committed

1. Revoke or rotate the exposed credential immediately when applicable.
2. Remove the sensitive material from the repository.
3. Remember that deleting the latest file does not erase Git history.
4. Rewrite affected history when necessary and verify that old references no longer expose the value.
5. Review dependent accounts and services for suspicious activity.

## Business data

Public planning documents may contain ranges, assumptions and non-sensitive research. Private financial statements, signed contracts, identity records, participant files and account credentials belong outside this repository.
