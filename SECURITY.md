# Security policy

## Reporting a vulnerability

Do not open a public issue. Use GitHub's "Report a vulnerability" button on
the affected repository (private vulnerability reporting), with reproduction
steps and the component affected. Acknowledgement within 2 business days; a
remediation timeline within 7.

## Scope

Every repository in the `MegaCurrent` organization. The highest-value
targets are the portal's sign-in and session cookie (`victron-tools`, the
`@megacurrent/victron-auth` package every tool imports) and the tool
registry's redirect and download targets.

## Secrets

No credential is ever committed, on any branch. `.env*` files are ignored
everywhere; `.env.example` carries names only. A secret that reaches a
commit, a transcript or a chat is rotated; rewriting history is not a
substitute.
