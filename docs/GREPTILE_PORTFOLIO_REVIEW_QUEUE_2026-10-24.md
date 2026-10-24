# Greptile portfolio review queue — 24 October 2026

**Scope:** 163 repositories visible in Greptile and 45 other repositories visible to linked GitHub accounts but not the connected Greptile organisation, 208 unique repository identities in this snapshot. This is not proven exhaustive across every GitHub owner/account. Queue ID `GRA-NNN` is a stable tracking ID for the **repository review job**; it is not a replacement for existing in-repository task IDs.

**Latest completed run**: `parris-tech-services/coldfluapp` (Greptile PR #18, run `35000660`, no actionable PR-diff findings; numbered agent tasks committed). Earlier pilots: Repository Town and Eleven Realms reviews completed; their **fixes are not complete**.

## Portfolio-wide numbered execution tasks — GRC series (25 October 2026)

**Agent entrypoint:** Search this document's stable **`GRA-NNN`** repository audit IDs for review jobs, and use **`GRC-NNN`** below *only for programme-wide work*. Every discovered Greptile finding already has a task ID in the relevant repository; **do not allocate duplicate repair IDs**. Within a repo, follow its listed first task and prerequisite/claim/branch rules. Greptile recommendations remain open until reproduced/validated, repaired and tested. A documentation-only review is not a game-code audit.

**Strict cross-project triage:** Complete urgent, confirmed P1 source-level safety/privacy and progress integrity triage first; P2 work and lower-risk portfolio administration follow. A dependent agent should claim only a single numbered source task, not all the P1s simultaneously. Observe canonical ownership and avoid generated mirrors.

- [ ] **GRC-001** [P1 / FIRST SECURITY TRIAGE] Route and verify the DadLAN public-learning workplace-network exposure: **`GRA-035 / DLC-GR-002`**. **Start:** open [DadLAN central tasks](https://github.com/Parris-Tech-Services/DadLANControlCentre/blob/main/docs/OUTSTANDING_WORK_2026-10-24.md), inspect PR #3 and Greptile [inline P1](https://github.com/Parris-Tech-Services/DadlanControlCentre/pull/3#discussion_r4366774993) without repeating identifiers in public comments. **Accept:** confirm exposure and authorisation; remove unauthorised real-network examples in a tested source PR, independently verify rendered/bundled output and any relevant history before resolving finding. Ownership of actual repair stays with `DLC-GR-002`.
- [ ] **GRC-002** [P1 / DATA INTEGRITY] Route and verify Kaseya FieldOps **`GRA-097 / KFO-GR-011`**, the review/progress ID collision. **Start:** read the [FieldOps outstanding tasks](https://github.com/Parris-Tech-Services/KaseyaFieldOps/blob/main/docs/OUTSTANDING_WORK_2026-10-24.md), reproduce collisions on the reviewed PR head, check current branch claims. **Accept:** isolated progress identities, backward-compatible persisted state, negative regression tests and follow-up Greptile review evidence.
- [ ] **GRC-003** [P1 / TESTING BLOCKER] Route and verify Kaseya FieldOps **`GRA-097 / KFO-GR-012`**, failing browser tests. **Start:** inspect reviewed PR/test selectors and obtain failing output; distinguish stale tests from broken UI. **Accept:** corrected tests or behaviour with passing representative browser and CI evidence; do not mark fixed merely because a review suggested the change.
- [ ] **GRC-004** [P1 / CORE GAMEPLAY] Route Repository Town's canonical-source reconciliation **`GRA-136 / RTG-001`** then emergency dispatch **`RTG-002`**, response timing **`RTG-003`** and case selection **`RTG-004`**. **Start:** canonical [JoshMemory Town task tracker](https://github.com/joshualparris/JoshMemory/blob/docs%2Ftown-number-unnumbered-tasks-20261024/repository-town/docs/UNNUMBERED_TODO_IDS_2026-10-24.md), compare generated [public PR #29](https://github.com/Parris-Tech-Services/Repository-Town/pull/29) with current authoritative source/branch. **Accept:** focused failing-to-passing tests, 000 incident scenarios, save/restore, verified sync and final re-review. Do not hand-edit the public mirror.
- [ ] **GRC-005** [P2 / REMAINING FINDINGS] Triage all **12 other** Greptile findings in existing repository trackers, without new identifiers: Town `RTG-005`, `RTG-006`, `RTG-007`; Eleven Realms `ERG-004`; DadLAN `DLC-GR-011`–`014`; Kaseya FieldOps `KFO-GR-005`, `KFO-GR-013`–`015`. **Start:** select highest-impact unclaimed valid finding after P1 blockers and required branch reconciliation. **Accept:** tracked per-task repro, repair, tests, Greptile resolved status, and commit/evidence links; keep umbrella open until all 12 are evidenced.
- [ ] **GRC-006** [P2 / BUCKLAND HANDOFF] Reconcile the existing documentation-only BucklandBlocks Greptile review **`GRA-024`**, run `34999411` on [PR #42](https://github.com/Parris-Tech-Services/BucklandBlocks/pull/42). **Start:** review the [BKG-001–005 tasks now on main](https://github.com/Parris-Tech-Services/BucklandBlocks/blob/main/AUDIO_INTEGRATION_TODO.md); PR #43 was merged after successful quality checks. Work on `BKG-002` (real code PR review), followed by already numbered audio `TASK-00148`–`00150`. **Accept:** PR #43 status and commit, no invented code findings, source-code review or honest `BLOCKED_NO_PR` and updated queue.
- [ ] **GRC-007** [P2 / PROVIDER AUTH BLOCKER] Reconcile the **45** GitHub repos marked `BLOCKED_PROVIDER_ACCESS`; each already has its own **`GRA-NNN`** audit job ID below. **Start:** group blocked records by actual owner, check which GitHub/Greptile installations are missing, ask for only required interactive owner authorisation. **Accept:** provider lists each accessible repo and has genuine PR review permissions before switching its row to `QUEUED`; do not claim these have been enabled or fabricate permissions.
- [ ] **GRC-008** [P2 / REPOSITORY QUEUE] Process the remaining **158 initial `QUEUED` repo audit jobs** in stable `GRA-NNN` order *subject to risk and dependencies*; BucklandBlocks `GRA-024` is separately marked as `DOC_REVIEW_ONLY`, so the live unreviewed QUEUED count changes accordingly. **Start:** pick one eligible high-risk PR on an authoritative repository, not a mirror; Greptile review, translate distinct findings to numbered tasks in its existing central tracker, commit, re-read, update queue; respect budget. **Accept:** no skipped jobs, no fake whole-repo reviews, exact blocker status if no PR/provider access; full job completion requires repository-owned task IDs and verification.
- [ ] **GRC-009** [P2 / SCHEDULE VERIFICATION] Verify the daily **Daily Greptile Repo Audit** automation actually executes one queue job; it was enabled with no recorded runs when last checked. **Start:** check run history after first scheduled window, compare exact Greptile/GitHub commits with queue; investigate auth/credit/notification failures. **Accept:** dated evidence of first successful execution and persisted update; report notification delivery accurately (notifications currently disabled), never claim autonomous progress without a run.
- [ ] **GRC-010** [P2 / INVENTORY COVERAGE] Audit completeness beyond the **208 snapshot repository identities** and two authenticated GitHub connections. **Start:** compare accessible GitHub owners, archived/fork/mirror status and the separate all-account project inventory; deduplicate by canonical repo ID rather than display name and preserve prior `GRA` IDs. **Accept:** proven new unique audit IDs if discovered, recorded permissions gaps, and corrected counts without silently renumbering existing rows.
- [ ] **GRC-011** [P2 / PROVIDER BEHAVIOUR] Verify Greptile actually auto-reviews new/updated PRs where enabled, and whether full searchable repository knowledge bases are indexed or only custom-context patterns are saved. **Start:** inspect settings, one actual new SCM event and the returned run/comment evidence; scope by code owner and avoid paid duplicate reviews. **Accept:** verified automatic trigger and code search when supported or explicit provider BLOCKED status per repo.
- [ ] **GRC-012** [P2 / CLOSURE AND ANALYTICS] Reconcile every finding's current addressed status, original comment URL and current source SHA against all project task checkboxes. **Start:** use Greptile findings/analytics and each repo's central task register; source-level repair, tests and deployment acceptance must be independently verified. **Accept:** updated severity/open-count report and per-repo links, with no review/comment/doc-only task misreported as fixed.

### Known finding-to-task mapping (do not renumber)

**P1 (6):** DadLAN `DLC-GR-002`; Kaseya FieldOps `KFO-GR-011`, `KFO-GR-012`; Repository Town `RTG-002`, `RTG-003`, `RTG-004`.

**P2 (12):** Repository Town `RTG-005`, `RTG-006`, `RTG-007`; Eleven Realms `ERG-004`; DadLAN `DLC-GR-011`, `DLC-GR-012`, `DLC-GR-013`, `DLC-GR-014`; Kaseya FieldOps `KFO-GR-005`, `KFO-GR-013`, `KFO-GR-014`, `KFO-GR-015`.

**Status:** These 18 are still unaddressed in the last independently read Greptile analytics. The number series above represent orchestration only; underlying findings retain their project-local authoritative IDs.


## Workflow: exactly one repo at a time

1. **Discover canonical owner/source**: inspect `AGENTS.md`, `README.md`, developer principles, active branches, issues, work checkpoint, central task doc and any documented mirror relationships. If the repo is a generated mirror, route fixes and tasks to canonical source, retaining an explicit mirror cross-reference.
2. **Choose review surface responsibly**: inspect open PRs, newest impactful changes and existing Greptile runs. Reuse a completed review for an unchanged head when possible. Greptile PR reviews inspect diffs, **not automatically every file of the whole repository**; never call a PR review a whole-codebase audit. Prefer a representative non-duplicate high-impact PR. If no PR is available, record `BLOCKED_NO_PR` or perform a supported headless review from a checkout only after confirming tooling/auth; do not fabricate full audit results. Avoid mass-triggering expensive overlapping Dependabot reviews.
3. **Configure project rules**: save/reuse persistent security/privacy, correctness and project-specific architecture/testing instructions; record the context IDs. Read and query an available knowledge base if indexed; otherwise read source and store source-grounded patterns, explicitly marking native Greptile indexing unavailable.
4. **Run Greptile; wait for COMPLETED/FAILED**. Collect review ID, exact reviewed head SHA, GitHub inline links, severity and addressed state. Separate reviewer suggestions from independently validated defects; triage false positives and already-fixed findings.
5. **Convert each actionable finding into a stable, unique, numbered ID in that repo's EXISTING central task document**, retaining every old task ID, its checkbox state and wording. Assign one source-linked parent per distinct root cause and optional numbered substeps; avoid duplicating a task already tracked. If the canonical file is on a documentation branch, commit to that branch and explicitly label it not yet merged.
6. **Agent-ready contract on each task**: `[ ] ID [P0/P1/P2/P3] short problem`; exact file/function/branch and Greptile comment; initial reproduction/triage; dependencies and conflict/claim checks; intended minimal fix; explicit automated tests, browser/device proof as appropriate; review again and mark resolved only after evidence; privacy/release gates; human approval if medically or legally required.
7. **Agent starting order**: P0 exploitable safety/privacy/data loss → P1 severe correctness/security/blocked workflow → P2 functional regressions/required tests → P3 polish or tech debt. Within severity: root cause and blocker dependencies before downstream tests, fixes before release, merge last. If unknown, mark TRIAGE, not a fabricated severity.
8. **Verify GitHub persistence and update queue**: re-fetch the task doc from the committed branch, confirm IDs and checkboxes, log commit SHA, task range, Greptile run/PR, finding totals and status. Record each repo `REVIEWED_FINDINGS_OPEN`, `TASKS_COMMITTED`, `FIXED_VERIFIED`, `BLOCKED_PROVIDER_ACCESS`, `BLOCKED_NO_PR` or `REVIEW_FAILED`. Do not mark `FIXED_VERIFIED` based on docs alone.
9. **One at a time**: finish documentation+verification for the current repo before marking its queue entry complete and choosing the next risk-ranked repo. If blocked, record exact reason and advance without pretending the blocker is gone.

## Triage priorities

Select next repo by **known high-stakes user impact, real changes requiring review, whether a reviewable PR exists, and lack of previous coverage**, not arbitrary alphabet order. Health-related, child/family, login/privacy, payments and deployment/security deserve earlier inspection, but only validated findings get severity labels. Confirm canonical source and active PRs each time.

**Initial candidates after ColdFluApp**: healthlens, gentlemovement, sylvieapp, parrisvoicebank, repaircafeinternal, dadlancontrolcentre and repository-town-playtest (subject to reviewable PR availability). If a repo has no open PR, log the limitation and choose the next, rather than opening artificial PRs.

## Full inventory

| Audit job ID | Repository | Current state | Central task document |
|---|---|---|---|
| GRA-001 | `parris-tech-services/3layers` | QUEUED | — |
| GRA-002 | `parris-tech-services/a` | QUEUED | — |
| GRA-003 | `parris-tech-services/action1` | QUEUED | — |
| GRA-004 | `parris-tech-services/adventuretext` | QUEUED | — |
| GRA-005 | `parris-tech-services/aetheria` | QUEUED | — |
| GRA-006 | `parris-tech-services/agentcheck` | QUEUED | — |
| GRA-007 | `parris-tech-services/agentcouncil` | QUEUED | — |
| GRA-008 | `parris-tech-services/aigenealogy` | QUEUED | — |
| GRA-009 | `parris-tech-services/alfie` | QUEUED | — |
| GRA-010 | `parris-tech-services/analog` | QUEUED | — |
| GRA-011 | `parris-tech-services/analytics` | QUEUED | — |
| GRA-012 | `parris-tech-services/anchorflow` | QUEUED | — |
| GRA-013 | `parris-tech-services/appfactory` | QUEUED | — |
| GRA-014 | `parris-tech-services/apple` | QUEUED | — |
| GRA-015 | `parris-tech-services/arena` | QUEUED | — |
| GRA-016 | `parris-tech-services/ashfaller` | QUEUED | — |
| GRA-017 | `parris-tech-services/astradndgame` | QUEUED | — |
| GRA-018 | `parris-tech-services/avancepd` | QUEUED | — |
| GRA-019 | `parris-tech-services/avanceprofessionaldevelopment` | QUEUED | — |
| GRA-020 | `parris-tech-services/avancesubnettinglab` | QUEUED | — |
| GRA-021 | `parris-tech-services/awdagaer` | QUEUED | — |
| GRA-022 | `parris-tech-services/bramblewick` | QUEUED | — |
| GRA-023 | `parris-tech-services/breach-command` | QUEUED | — |
| GRA-024 | `parris-tech-services/bucklandblocks` | DOC_REVIEW_ONLY | [BKG tasks on main](https://github.com/Parris-Tech-Services/BucklandBlocks/blob/main/AUDIO_INTEGRATION_TODO.md) |
| GRA-025 | `parris-tech-services/bucklandblocks1` | QUEUED | — |
| GRA-026 | `parris-tech-services/campaign-copilot` | QUEUED | — |
| GRA-027 | `parris-tech-services/canonrpg` | QUEUED | — |
| GRA-028 | `parris-tech-services/carl` | QUEUED | — |
| GRA-029 | `parris-tech-services/chatgpt-history-browser` | QUEUED | — |
| GRA-030 | `parris-tech-services/chess` | QUEUED | — |
| GRA-031 | `parris-tech-services/chronos` | QUEUED | — |
| GRA-032 | `parris-tech-services/clearcore` | QUEUED | — |
| GRA-033 | `parris-tech-services/code-cleaner` | QUEUED | — |
| GRA-034 | `parris-tech-services/coldfluapp` | TASKS_COMMITTED | [ColdFluApp TODO](https://github.com/Parris-Tech-Services/ColdFluApp/blob/main/TODO.md) |
| GRA-035 | `parris-tech-services/dadlancontrolcentre` | TASKS_COMMITTED | [DadLAN tasks](https://github.com/Parris-Tech-Services/DadLANControlCentre/blob/main/docs/OUTSTANDING_WORK_2026-10-24.md) |
| GRA-036 | `parris-tech-services/dadlansubnettingscenarios` | QUEUED | — |
| GRA-037 | `parris-tech-services/dcscompanion` | REVIEW_RUNNING | [PR #2, Greptile 35081981](https://github.com/Parris-Tech-Services/DCSCompanion/pull/2) |
| GRA-038 | `parris-tech-services/dcspd` | QUEUED | — |
| GRA-039 | `parris-tech-services/dcspd-vlsmstudio` | QUEUED | — |
| GRA-040 | `parris-tech-services/dcsprep` | QUEUED | — |
| GRA-041 | `parris-tech-services/dcsprofessionaldevelopment` | QUEUED | — |
| GRA-042 | `parris-tech-services/dcssubnettingretrieval` | QUEUED | — |
| GRA-043 | `parris-tech-services/delve` | QUEUED | — |
| GRA-044 | `parris-tech-services/demo-repository` | QUEUED | — |
| GRA-045 | `parris-tech-services/dinner-decider` | QUEUED | — |
| GRA-046 | `parris-tech-services/diskcleanupaudit` | QUEUED | — |
| GRA-047 | `parris-tech-services/dndgame` | QUEUED | — |
| GRA-048 | `parris-tech-services/drifter` | QUEUED | — |
| GRA-049 | `parris-tech-services/dubbodatacentre` | QUEUED | — |
| GRA-050 | `parris-tech-services/dubbosdr` | QUEUED | — |
| GRA-051 | `parris-tech-services/echo` | QUEUED | — |
| GRA-052 | `parris-tech-services/eleven-realms` | REVIEWED_FINDINGS_OPEN | [Eleven Realms roadmap](https://github.com/Parris-Tech-Services/Eleven-Realms/blob/main/docs/GAME_DESIGN_ROADMAP.md) |
| GRA-053 | `parris-tech-services/elevenrealms` | QUEUED | — |
| GRA-054 | `parris-tech-services/elodin-deep-lore` | QUEUED | — |
| GRA-055 | `parris-tech-services/elodindeeplore` | QUEUED | — |
| GRA-056 | `parris-tech-services/emailcheck` | QUEUED | — |
| GRA-057 | `parris-tech-services/energyquest` | QUEUED | — |
| GRA-058 | `parris-tech-services/epubtranslate` | QUEUED | — |
| GRA-059 | `parris-tech-services/examsapp` | QUEUED | — |
| GRA-060 | `parris-tech-services/exchangelabmanager` | QUEUED | — |
| GRA-061 | `parris-tech-services/exitbackup` | QUEUED | — |
| GRA-062 | `parris-tech-services/fable-atlas` | QUEUED | — |
| GRA-063 | `parris-tech-services/faithhub` | QUEUED | — |
| GRA-064 | `parris-tech-services/familytree` | QUEUED | — |
| GRA-065 | `parris-tech-services/fedoracrashdoctor` | QUEUED | — |
| GRA-066 | `parris-tech-services/fieldnotes` | QUEUED | — |
| GRA-067 | `parris-tech-services/forbiddenquests` | QUEUED | — |
| GRA-068 | `parris-tech-services/forgegrid` | QUEUED | — |
| GRA-069 | `parris-tech-services/forgegrid-control` | QUEUED | — |
| GRA-070 | `parris-tech-services/game-booster` | QUEUED | — |
| GRA-071 | `parris-tech-services/gentlemovement` | QUEUED | — |
| GRA-072 | `parris-tech-services/goldfinder` | QUEUED | — |
| GRA-073 | `parris-tech-services/health-data-manager` | QUEUED | — |
| GRA-074 | `parris-tech-services/healthlens` | QUEUED | — |
| GRA-075 | `parris-tech-services/heartcalm` | QUEUED | — |
| GRA-076 | `parris-tech-services/hermescontrol` | QUEUED | — |
| GRA-077 | `parris-tech-services/hprobooktroubleshoot` | QUEUED | — |
| GRA-078 | `parris-tech-services/hrv` | QUEUED | — |
| GRA-079 | `parris-tech-services/ideas` | QUEUED | — |
| GRA-080 | `parris-tech-services/ideas2` | QUEUED | — |
| GRA-081 | `parris-tech-services/joshbios` | QUEUED | — |
| GRA-082 | `parris-tech-services/joshbooksonline` | QUEUED | — |
| GRA-083 | `parris-tech-services/joshcards` | QUEUED | — |
| GRA-084 | `parris-tech-services/joshchess` | QUEUED | — |
| GRA-085 | `parris-tech-services/joshcoach` | QUEUED | — |
| GRA-086 | `parris-tech-services/joshdashboard` | QUEUED | — |
| GRA-087 | `parris-tech-services/joshdashboard3` | QUEUED | — |
| GRA-088 | `parris-tech-services/joshfireawareness` | QUEUED | — |
| GRA-089 | `parris-tech-services/joshhealth` | QUEUED | — |
| GRA-090 | `parris-tech-services/joshhorses` | QUEUED | — |
| GRA-091 | `parris-tech-services/joshhub` | QUEUED | — |
| GRA-092 | `parris-tech-services/joshhub-local` | QUEUED | — |
| GRA-093 | `parris-tech-services/joshnfcaudio` | QUEUED | — |
| GRA-094 | `parris-tech-services/joshos-stage0` | QUEUED | — |
| GRA-095 | `parris-tech-services/joshplatform` | QUEUED | — |
| GRA-096 | `parris-tech-services/joshreading` | QUEUED | — |
| GRA-097 | `parris-tech-services/kaseyafieldops` | TASKS_COMMITTED | [FieldOps tasks](https://github.com/Parris-Tech-Services/KaseyaFieldOps/blob/main/docs/OUTSTANDING_WORK_2026-10-24.md) |
| GRA-098 | `parris-tech-services/kkc-adventure` | QUEUED | — |
| GRA-099 | `parris-tech-services/lantern-road` | QUEUED | — |
| GRA-100 | `parris-tech-services/lifehub` | QUEUED | — |
| GRA-101 | `parris-tech-services/lifehubdashboard` | QUEUED | — |
| GRA-102 | `parris-tech-services/llm` | QUEUED | — |
| GRA-103 | `parris-tech-services/llmaccountability` | QUEUED | — |
| GRA-104 | `parris-tech-services/lore` | QUEUED | — |
| GRA-105 | `parris-tech-services/marsh` | QUEUED | — |
| GRA-106 | `parris-tech-services/max` | QUEUED | — |
| GRA-107 | `parris-tech-services/midnight-line` | QUEUED | — |
| GRA-108 | `parris-tech-services/migration` | QUEUED | — |
| GRA-109 | `parris-tech-services/mining` | QUEUED | — |
| GRA-110 | `parris-tech-services/mspquest-joshhub` | QUEUED | — |
| GRA-111 | `parris-tech-services/neathbound` | QUEUED | — |
| GRA-112 | `parris-tech-services/nebuladice-browser` | QUEUED | — |
| GRA-113 | `parris-tech-services/nedjoshcollab` | QUEUED | — |
| GRA-114 | `parris-tech-services/newfileqqqwertuhvgjkk.py` | QUEUED | — |
| GRA-115 | `parris-tech-services/nextjs-expert` | QUEUED | — |
| GRA-116 | `parris-tech-services/openclaw` | QUEUED | — |
| GRA-117 | `parris-tech-services/openclaw-workspace` | QUEUED | — |
| GRA-118 | `parris-tech-services/os` | QUEUED | — |
| GRA-119 | `parris-tech-services/parrisbudgetapp` | QUEUED | — |
| GRA-120 | `parris-tech-services/parrisdubbomover` | QUEUED | — |
| GRA-121 | `parris-tech-services/parrisdubbomoverapp` | QUEUED | — |
| GRA-122 | `parris-tech-services/parrisdubbomoverapp-main` | QUEUED | — |
| GRA-123 | `parris-tech-services/parris-life-dashboard` | QUEUED | — |
| GRA-124 | `parris-tech-services/parrispiano` | QUEUED | — |
| GRA-125 | `parris-tech-services/parristechservicesapp` | QUEUED | — |
| GRA-126 | `parris-tech-services/parrisvoicebank` | QUEUED | — |
| GRA-127 | `parris-tech-services/pdfresearch` | QUEUED | — |
| GRA-128 | `parris-tech-services/pdm-parris-dubbo-mover` | QUEUED | — |
| GRA-129 | `parris-tech-services/physiobuddy` | QUEUED | — |
| GRA-130 | `parris-tech-services/powerapp` | QUEUED | — |
| GRA-131 | `parris-tech-services/privateport` | QUEUED | — |
| GRA-132 | `parris-tech-services/prompt-linker` | QUEUED | — |
| GRA-133 | `parris-tech-services/random-play` | QUEUED | — |
| GRA-134 | `parris-tech-services/repaircafeinternal` | QUEUED | — |
| GRA-135 | `parris-tech-services/repoclean` | QUEUED | — |
| GRA-136 | `parris-tech-services/repository-town` | REVIEWED_FINDINGS_OPEN | [Town task docs](https://github.com/joshualparris/JoshMemory/blob/docs%2Ftown-number-unnumbered-tasks-20261024/repository-town/docs/UNNUMBERED_TODO_IDS_2026-10-24.md) |
| GRA-137 | `parris-tech-services/repository-town-playtest` | QUEUED | — |
| GRA-138 | `parris-tech-services/researchatlas` | QUEUED | — |
| GRA-139 | `parris-tech-services/researchgems` | QUEUED | — |
| GRA-140 | `parris-tech-services/rothfuss-kkc-adventure` | QUEUED | — |
| GRA-141 | `parris-tech-services/rothfussmaps` | QUEUED | — |
| GRA-142 | `parris-tech-services/schism` | QUEUED | — |
| GRA-143 | `parris-tech-services/serenity-keep-flying` | QUEUED | — |
| GRA-144 | `parris-tech-services/skills` | QUEUED | — |
| GRA-145 | `parris-tech-services/starhaven` | QUEUED | — |
| GRA-146 | `parris-tech-services/swordchronicles-backup-20260906-204137` | QUEUED | — |
| GRA-147 | `parris-tech-services/swordcoast` | QUEUED | — |
| GRA-148 | `parris-tech-services/sylvieapp` | QUEUED | — |
| GRA-149 | `parris-tech-services/textgame` | QUEUED | — |
| GRA-150 | `parris-tech-services/trace` | QUEUED | — |
| GRA-151 | `parris-tech-services/transfer` | QUEUED | — |
| GRA-152 | `parris-tech-services/troubleshoot` | QUEUED | — |
| GRA-153 | `parris-tech-services/upskillapp` | QUEUED | — |
| GRA-154 | `parris-tech-services/virtual-tabletop` | QUEUED | — |
| GRA-155 | `parris-tech-services/wastes-courier-roguelike` | QUEUED | — |
| GRA-156 | `parris-tech-services/waypoint` | QUEUED | — |
| GRA-157 | `parris-tech-services/whirringwilderness` | QUEUED | — |
| GRA-158 | `parris-tech-services/whispering-wilds` | QUEUED | — |
| GRA-159 | `parris-tech-services/wild2` | QUEUED | — |
| GRA-160 | `parris-tech-services/work` | QUEUED | — |
| GRA-161 | `parris-tech-services/workapp` | QUEUED | — |
| GRA-162 | `parris-tech-services/workplanner` | QUEUED | — |
| GRA-163 | `parris-tech-services/wphi` | QUEUED | — |
| GRA-164 | `joshualparris/Aliens` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-165 | `joshualparris/AshFallen` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-166 | `joshualparris/BrackenHouse` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-167 | `joshualparris/buckland-blocks-demo` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-168 | `joshualparris/Cheappcslaptops` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-169 | `joshualparris/CircularEconomyDubbo` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-170 | `joshualparris/Coffeezilla` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-171 | `joshualparris/ColinBuchanan` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-172 | `joshualparris/dewey-converter-for-librarything` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-173 | `joshualparris/DubboEwaste` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-174 | `joshualparris/Dubbozoo` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-175 | `joshualparris/EliasApp` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-176 | `joshualparris/FailbetterGames` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-177 | `joshualparris/HealthiestFood` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-178 | `joshualparris/HealthiestPeople` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-179 | `joshualparris/HealthLens` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-180 | `joshualparris/HugCoach` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-181 | `joshualparris/Ideas` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-182 | `joshualparris/JoshDashboard2` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-183 | `joshualparris/JoshDashboard4` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-184 | `joshualparris/JoshDataHunt` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-185 | `joshualparris/JoshHub` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-186 | `joshualparris/JoshMemory` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-187 | `joshualparris/JoshTapApp` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-188 | `joshualparris/my-repository` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-189 | `joshualparris/ParrisTechApp` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-190 | `joshualparris/Paul-Roe` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-191 | `joshualparris/Paul-Roe-Private-Archive` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-192 | `joshualparris/realms-atlas` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-193 | `joshualparris/repository-town` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-194 | `joshualparris/ResearchLibrary` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-195 | `joshualparris/Sleepy` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-196 | `joshualparris/SylviePhonetics` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-197 | `joshualparris/the-consultancy-beneath` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-198 | `joshualparris/theUndercity` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-199 | `joshualparris/TristanHarris` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-200 | `joshualparris/Whispering-Wilds` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-201 | `joshuaparris-max/EliasApp2` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-202 | `joshuaparris-max/JoshOS` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-203 | `joshuaparris-max/realms-atlas` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-204 | `joshuaparrisdadlan-stack/JoshTapApp` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-205 | `parristechservices-prog/AIDungeonMaster` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-206 | `topsecretcheese-del/carGame` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-207 | `topsecretcheese-del/customCars` | BLOCKED_PROVIDER_ACCESS | — |
| GRA-208 | `topsecretcheese-del/gregGame` | BLOCKED_PROVIDER_ACCESS | — |


## ColdFluApp — audit job completed to tasks, not fixed

- **PR review:** [#18](https://github.com/Parris-Tech-Services/ColdFluApp/pull/18), Greptile `35000660`, completed 24 October 2026, confidence 5/5, no actionable findings in reviewed diff.
- **Task doc:** [ColdFluApp TODO.md](https://github.com/Parris-Tech-Services/ColdFluApp/blob/main/TODO.md), commit `1452bdfb54f85723771d97b815ffe3893a64fc61` with `GRT-001`–`GRT-012`; 1 review task completed, 11 engineering/release tasks still OPEN.
- **Agent start:** `GRT-002` (reconcile overlapping Dependabot updates #18/#37/#39), then GRT-003 private research auth and GRT-004 medical publication gates. A clean PR review is not proof full repo or other PRs safe.
- **Current state:** `TASKS_COMMITTED`; code changes, CI/release validation, native KB index and automatic future review remain unverified.


## DadLAN Control Centre — review in progress, numbered handoff saved

- Greptile PR #3 review run `35001261` accepted, reviewed head `45e3afbe804708c22cf81f5274988b94ff4bef75`; **COMPLETED** 2026-10-24 09:57 UTC; 5 findings (1×P1, 4×P2) and code-review suggestions posted.
- Central task doc [docs/OUTSTANDING_WORK_2026-10-24.md](https://github.com/Parris-Tech-Services/DadLANControlCentre/blob/main/docs/OUTSTANDING_WORK_2026-10-24.md), latest commit `66f2ccd7ef77df4b953aa1b79728d04b980c1fd4`; `DLC-GR-001`–`DLC-GR-014`. Review task 001 VERIFIED COMPLETE, 13 remediation/verification tasks OPEN. Pre-existing TASK-072–074 preserved.
- **Agent start** `DLC-GR-002`: review potentially sensitive real workplace networking details in public training examples; validate authorisation and replace with fictional examples if needed. This is **risk triage**, not a proven exploit.
- Original Greptile findings mapped to 5 unique tasks: existing `DLC-GR-002` for P1 security/privacy; new `DLC-GR-011`–`DLC-GR-014` for four P2 quality/testing issues, each linked to actual inline comments. All five initially UNADDRESSED. Verification includes re-reading the committed task document and Greptile analytics (5 findings, 1 P1 + 4 P2). No code changes, remediation, or CI passes are claimed.

## Kaseya FieldOps — in-progress review

- Greptile PR #2 run `35001994`, head `c5c1de85b21729fb3c4ed5d6ac0ed4af8e57be55`, **COMPLETED** 2026-10-24 10:05 UTC; 6 published findings (2 P1, 4 P2) all initially UNADDRESSED.
- Project task doc [OUTSTANDING_WORK_2026-10-24.md](https://github.com/Parris-Tech-Services/KaseyaFieldOps/blob/main/docs/OUTSTANDING_WORK_2026-10-24.md), latest commit `465198ddf6cef95396969e819a9df4eebd58d829`, `KFO-GR-001`–`KFO-GR-015`, review task 001 VERIFIED COMPLETE; 14 engineering/verification items OPEN; original TASK-086–087 unchanged.
- Agent start `KFO-GR-002`: compare related DadLAN networking curriculum and review findings, validate and correct only confirmed shared issues; `KFO-GR-003` handles public privacy risk.
- Findings triage: P1 progress/review ID collision `KFO-GR-011`; P1 browser test breakage `KFO-GR-012`; P2 LDAP/routing/ICMP factual errors `KFO-GR-013`–`015`; P2 missing renderer tests mapped to existing `KFO-GR-005` with Greptile comment. Review and task counts verified by provider analytics and re-reading the commit. Agent starts with `KFO-GR-011` → `012`. No code fixes/tests/deploy are claimed.


## BucklandBlocks — prior documentation PR reviewed, code review still owed

- `GRA-024`: [PR #42](https://github.com/Parris-Tech-Services/BucklandBlocks/pull/42) has Greptile completed run `34999411`, 5/5 and no actionable findings; it ONLY reviewed the numbering changes, not gameplay code. Original PR #42 merged at `87b5f47dc994f592bd6badfac6e29d1bdd9cfa2e`.
- New project-local Greptile triage IDs **`BKG-001`–`BKG-005`** have been committed on branch `docs/buckland-greptile-triage-20261025` at `bf7f5f961a9a84146492eecc4ddf4a68914fe06d` and accepted through [PR #43](https://github.com/Parris-Tech-Services/BucklandBlocks/pull/43), **MERGED** into `main` as `d8155c29129a35a52b65c095a7700b5256bd4219`. Both required checks (Game Release Gate and Buckland Blocks quality gate) reported SUCCESS before merge; task IDs `BKG-001`–`BKG-005` were re-read on `main`. `BKG-001` completed (docs review), `BKG-002` the next real source-code review job; original audio tasks `TASK-00148`–`00150` unchanged.
- `DOC_REVIEW_ONLY` means Buckland has a documented review but does **not** count as a substantive source-code audit; keep it open for a code-bearing diff or accurately marked `BLOCKED_NO_PR`.


## DCSCompanion — review running (GRA-037)

- **Canonical repo:** [Parris-Tech-Services/DCSCompanion](https://github.com/Parris-Tech-Services/DCSCompanion), default `main` (`ebc4cc1e1b77811525aebedb87c1200fdf351467` at initial read). Public repo. No `AGENTS.md` or central engineering TODO file found in the complete 163-entry `main` tree; existing in-app `src/data/taskTracker.ts` is not a project work tracker. Preserve the existing open [PR #2](https://github.com/Parris-Tech-Services/DCSCompanion/pull/2) and issue #2.
- **Selected review surface:** PR #2, `feat/msp-networking-reference`, exact head `5046eb8518af66e71ca8c3128a4ee227bb95eac7`; four changed files, including new networking curriculum and KB presentation. Chosen ahead of lower-risk apps because the public school-support KB may contain staff/network operational details and has Ask DCS LLM retrieval exposure. This is **risk to investigate**, not a verified data breach.
- **Greptile:** triggered **once**, review ID `35081981`; status `REVIEWING_FILES` at last poll. No earlier Greptile review for this PR; do not retrigger. Poll `get_code_review(35081981)` until COMPLETED/FAILED; validate current PR lines and duplicate task IDs before creating a central task tracker and recording findings. PR-diff review is **not** whole-codebase coverage.
- **First next action:** poll existing review `35081981`. Do not select another repo while this review is running. No fixes, tests or deployments claimed.

## Limitations

- `reviewsEnabled=true` is a Greptile setting, **not** proof automatic PR reviews run or native codebase indexing exists.
- A successful trigger confirms only the queue request; verify the completed run and actual inline comments.
- Some accessible GitHub accounts may have more repositories beyond this snapshot; periodically reconcile connected installations.
- Respect per-provider credit and budget limits, and never auto-merge or alter protected health content without review.
