# Self-Correcting Public Link Parser

[Русский](../README.md) · **English** · [Українська](README.uk.md) · [中文](README.zh-CN.md) · [עברית](README.he.md)

> **Independent product.** This project is not affiliated with, endorsed, sponsored, or certified by Google LLC, Max, WhatsApp, Telegram, or ZennoPoster. Names are used only for compatibility and purpose descriptions.

## Overview

A commercial workflow for collecting, normalising, validating, and exporting publicly accessible links from search results for research, cataloguing, and analytics.

## How collection works

1. Define the lawful research purpose, allowed domains, exclusions, regions, languages, output format, and request-rate limits.
2. Build a queue of approved search queries with status and last-run timestamps.
3. Retrieve only pages available without authentication while respecting source terms, applicable `robots.txt` directives, rate limits, pauses, and concurrency caps.
4. Extract the minimum necessary public fields: result URL, title, visible snippet, source query, and discovery timestamp.
5. Canonicalise URLs, remove non-essential tracking parameters where safe, and reject private, login, error, or out-of-scope pages.
6. Deduplicate by canonical URL and domain; retain provenance instead of creating duplicate rows.
7. Measure validity and relevance. “Self-correction” means switching between pre-approved extraction profiles or escalating to review if layout changes reduce quality — never bypassing protection.
8. Export cleaned CSV, JSON, or a table with provenance and a filtering log.

## Result

A repeatable, auditable set of public links with fewer duplicates and clearer provenance for research or human review.

## Contact

- Telegram: [@TheBotsLab](https://t.me/TheBotsLab)
- Email: [BotsLab@proton.me](mailto:BotsLab@proton.me)

## Responsible-use boundary

Use only for publicly available URLs and for an agreed lawful purpose. The product does not bypass authentication, CAPTCHA, technical protections, platform limits, or access controls. It must not be used for spam, mass messaging, unauthorised profiling, or collection of unnecessary personal data.
