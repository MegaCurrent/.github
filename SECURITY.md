# Security policy

## Reporting a vulnerability

Do not open a public issue. Use GitHub's "Report a vulnerability" button on
this repository (`MegaCurrent/.github`, where private vulnerability
reporting is enabled) with reproduction steps and the component affected.
Reports are acknowledged within 2 business days.

## Scope

Every repository in the `MegaCurrent` organization.

## Secrets

No credential is ever committed, on any branch. `.env*` files are ignored
everywhere; `.env.example` carries names only. A secret that reaches a
commit, a transcript or a chat is rotated; rewriting history is not a
substitute.
