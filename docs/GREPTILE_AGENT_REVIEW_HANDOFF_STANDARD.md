# Greptile agent-ready review handoff — v1 (24 October 2026)

Applies to each repo in [the portfolio review queue](GREPTILE_PORTFOLIO_REVIEW_QUEUE_2026-10-24.md).

## Job opening checklist
- Read canonical `AGENTS.md`, working checkpoint, original task tracker and repository engineering rules.
- Verify origin, branch, current PRs, latest commit, public/private/mirror status and whether another agent has claimed overlapping files.
- Inspect exact Greptile PR review run, GitHub inline comment and current branch diff; verify that a finding remains actionable.
- Do not reuse or change existing identifiers. Search all central task docs and issues for existing work before allocating a new ID.

## Required task format
```md
- [ ] **PREFIX-001** [P1] Concise impact-focused title.
  - **Start/triage:** Inspect <canonical path/symbol> on <branch/SHA>; reproduce <failure>; check if fixed elsewhere.
  - **Evidence:** Greptile run <ID>; PR/comment URL; current baseline <SHA>. Unverified suggestions are marked 'needs confirmation'.
  - **Dependencies:** <parent IDs>, branch/claim collision warnings; human approval and privacy constraints.
  - **Proposed minimal fix:** <specific expected behavioural change>; avoid style-only churn.
  - **Acceptance:** <unit+integration+browser tests>, security/privacy checks, exact command/exit evidence, re-review and production SHA only where publication is part of scope.
  - **Closure:** PR/commit/deployed URL, logs, Greptile addressed state. Keep OPEN if any required proof is missing.
```

## Severity
- **P0 / immediate:** active exposure of personal data/secrets, credible exploitation, irreversible data corruption, dangerous public medical instructions, or broken emergency escalation. Verify first; stop affected release.
- **P1 / urgent:** serious incorrect app behaviour, privilege boundary risk, unusable core feature, financial/data-integrity flaw, blocked safety regression.
- **P2 / normal:** reproducible moderate bugs, important missing regression tests, broken noncritical workflows, deployment drift.
- **P3 / backlog:** polish, maintainability and genuinely nonblocking improvements.
- **TRIAGE:** confidence insufficient or no actual defect established; do not inflate urgency.

## Starting order for an agent
1. Confirm source of truth, read original requirements and repro failing state; report valid / false-positive / already-fixed.
2. Claim only specific numbered IDs and list files in checkpoint; check competing work.
3. Repair shared root causes and security risks before lower-level symptoms; add negative and failure-path tests.
4. Run lowest-cost focused tests then full project gates; verify output and logs.
5. Push code and checkpoint together to the correct branch; perform a new Greptile review on updated PR when available.
6. Review Greptile new/old comments, resolve only demonstrated fixes; run deployment/browser checks where required.
7. Check boxes only for tasks whose acceptance is actually verified; update cross-repository queue with source/PR/commit and count.

## Limits
Greptile reviews are PR-diff reviews. A completed PR review is not proof the whole repository is safe. Native Greptile knowledge bases may be missing; saved context patterns are not equivalent to a complete indexed codebase. Provider installations missing permission cannot be bypassed. AI comments are engineering leads, not proof; independent human clinical review remains mandatory for public medical content.
