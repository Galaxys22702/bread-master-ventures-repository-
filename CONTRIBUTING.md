# Contributing to Bread + Master Ventures

This repository is the shared planning workspace for Bread + Master.

## Working rules

1. Keep `main` stable.
2. Use a short branch for meaningful changes.
3. Make one logical change per pull request when practical.
4. Use clear commit messages that describe what changed.
5. Record material business decisions in `docs/decision-log.md`.
6. Add the source and date beside quotes, market figures, licence requirements or other facts that may change.
7. Mark financial figures as **estimate**, **quote** or **actual**.
8. Do not treat an unverified idea as a confirmed plan.

## File organisation

Use the existing structure:

- `docs/` for group-wide planning and decisions
- `ventures/` for for-profit business planning
- `nonprofit/` for the separate fathers-focused initiative

Use lowercase, hyphenated Markdown file names where possible.

## Sensitive information

Do not commit:

- passwords or recovery codes
- API keys or tokens
- bank or card information
- Social Security numbers
- tax IDs or identity documents
- private client or programme participant information
- confidential contracts or unredacted legal documents

This repository is public. Store confidential operating records somewhere designed for private records, not here.

## Before merging

Check that:

- links work
- names and terminology are consistent
- new figures have a source/date
- no sensitive information is present
- nonprofit and for-profit records remain clearly separated
- the change does not contradict a recorded decision without documenting the new decision
