# Public Data and Privacy

AltoTrail is designed to present public job-search and labour-market information
in a way that is useful, cautious, and privacy-conscious.

## Public data principles

Public-facing information should:

- Be presented with clear context and appropriate limitations.
- Avoid implying certainty where source data is incomplete or changing.
- Avoid exposing private operational access patterns.
- Separate public descriptions from private data preparation systems.

## Privacy principles

User-specific features should follow conservative privacy expectations:

- Collect only what is needed for the user-facing feature.
- Keep personal data out of public repositories.
- Avoid exposing raw identifiers, tokens, private URLs, or operational reports.
- Keep public content separate from private notification or account-like flows.

## Notifications and user-specific features

Any notification or alert feature should be opt-in, bounded, and designed with
clear user controls. Implementation details for such systems are intentionally
private and are not included in this repository.

## Repository exclusions

This repository does not contain user records, subscription data, delivery
reports, credentials, tokens, token hashes, analytics identifiers, private URLs,
generated datasets, prompts, operational snapshots, or production configuration.
