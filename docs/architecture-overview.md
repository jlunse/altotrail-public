# Architecture Overview

This document describes AltoTrail at a high level for public understanding. It
does not disclose private implementation details.

## Conceptual model

AltoTrail can be understood as a product made of several broad layers:

- A public web experience for job, occupation, and labour-market exploration.
- A multilingual content layer for localized public pages and interface text.
- A data preparation layer that supports structured, source-aware public
  information.
- A privacy-conscious layer for user-specific features.
- Private operational systems for quality control, publication, and monitoring.

## Design principles

The public architecture is guided by these principles:

- Keep public content separate from user-specific workflows.
- Prefer prepared public content over exposing operational systems directly.
- Treat multilingual routing, metadata, and interface language as first-class
  concerns.
- Keep delivery, notification, and account-like workflows behind strict
  operational boundaries.
- Avoid exposing internal source access patterns, scheduling, credentials, or
  production configuration.

## Public and private boundaries

The public-facing product may describe jobs, occupations, skills, and
labour-market context. The private implementation that prepares, validates,
publishes, and operates that information is not part of this repository.

This repository intentionally omits:

- Data ingestion and cache implementation.
- Ranking, matching, scoring, and alert delivery internals.
- Scheduler and deployment configuration.
- Operational reports, logs, and runbooks.
- Schemas, prompts, generated datasets, and private quality-control systems.
