# Contributing

- Branch from `main`; every change reaches `main` through a pull request.
  Squash merge; the PR title becomes the commit subject.
- One PR = one concern.
- CI must be green: each repository's own check wrapper (typecheck, lint,
  tests, dead-code check where configured).
- A change on a tier A path (listed in that repository's `CLAUDE.md`) is
  security-relevant: tick the box in the PR template; it gets the tier A
  review.
- The workflow every session follows, the review loop and the merge rules:
  `MegaCurrent/workflow` (private; `CLAUDE.md` there).
