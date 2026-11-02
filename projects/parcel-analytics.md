# Real estate analytics platform

**Status:** Private team project; functional prototype. **Code and data:** not public.

## Problem and approach

Property screening requires joining records from different public sources while preserving source context and indicating where data is incomplete or stale. I worked on a PostgreSQL-backed platform that brings municipal parcel and service-request data into a repeatable analysis workflow. The project also explored area and property-level screening views for acquisition research.

## My contribution

My resume records work on the data platform and screening models. The private repository contains ingestion scripts, database modules, API routes, tests, and documentation. Commits are attributed to an organization account and include AI-assisted tooling. This was shared work; I do not claim sole authorship of the codebase or independently verified production outcomes.

## Engineering decisions and limits

The prototype separates source data, derived signals, and presentation. Its internal documentation explicitly labels source freshness, missing fields, and directional estimates. Those safeguards matter because municipal records and historical sales are incomplete proxies for current property conditions. This case study intentionally omits internal scoring rules, specific records, customer information, and implementation details that could disclose proprietary work.

The repository is private, so the code, test results, and live data cannot be independently reproduced from this page. For public code, see [Will I Gap It?](https://github.com/gabemuk/will-i-gap-it).
