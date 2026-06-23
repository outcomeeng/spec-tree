# spec-tree

Spec Tree methodology skills for Outcome Engineering

> This repo is auto-generated from [outcomeeng/plugins](https://github.com/outcomeeng/plugins).
> For the shared marketplace, use `claude plugin marketplace add outcomeeng/plugins` or `codex plugin marketplace add outcomeeng/plugins`.

## Install

```bash
npx skills add outcomeeng/spec-tree
```

## Skills (36)

| Skill | Description |
| ----- | ----------- |
| `align` | reviewing, auditing, or checking spec file conformance |
| `apply` | ALWAYS invoke this skill before implementing any spec-tree work item |
| `audit` | Generic end-to-end code-scope audit orchestration preloaded by the auditor, audit-orchestrator, pr-reviewer, and pr-review-orchestrator agents |
| `audit-adr` | ADR audit methodology preloaded by the adr-auditor agent |
| `audit-pdr` | PDR audit methodology preloaded by the pdr-auditor agent |
| `audit-specs` | Spec-node audit methodology preloaded by the spec-auditor agent |
| `audit-tests` | Test-evidence audit methodology preloaded by the test-evidence-auditor agent |
| `author` | adding, defining, or creating specs, decisions, or nodes |
| `bootstrap` | setting up a new spec tree or when /author detects an empty spx/ directory |
| `commit-changes` | committing changes or when user says "commit" |
| `contextualize` | asking about status, progress, or what exists in the spec tree |
| `decompose` | breaking down, splitting, scoping, composing, or structuring spec tree nodes |
| `diagnose` | diagnosing the health of a spec-tree or spx environment, when checking whether the SessionStart hook fired for the current session, or when troubleshooting a missing session identity, worktree claim, or unreachable spx CLI |
| `handoff` | ALWAYS invoke to close a claimed spec-tree session — archive it, decide session-file creation, prepare continuation context — only once its goal is met with no continuation remaining or continuation by Claude is impossible (context exhausted, user halted, external blocker) |
| `init-worktrees` | setting up a repository's git worktree layout — classifying a checkout as a single tree, a bare-repo worktree pool, or non-compliant, and provisioning the bare-repo pool while pushing every local ref to the remote and carrying a prior checkout's gitignored state across |
| `inspect-github-actions` | the user asks about CI failures, workflow logs, GitHub Actions status, pipeline issues, or troubleshooting failed builds |
| `interview` | ALWAYS invoke BEFORE asking the user anything while creating or modifying any artifact (spec, ADR, PDR, test, code, doc) |
| `manage-github-pr` | the user asks to open or manage a GitHub pull request, or runs /manage-github-pr |
| `manage-pr` | Open-PR management protocol for review and check inspection, follow-up pushes, merge gates, and post-merge cleanup |
| `manage-thread-store` | persisting or retrieving branch-scoped verification records |
| `merge` | the user asks to ship, integrate, or merge a changeset into the default branch on origin, or runs /merge |
| `merging-standards` | Shared vocabulary for the merge lifecycle — pre-flight predicates, branch topology gate, push command, the three authority gates (review / merge / production readiness), review classification, integration review surfaces, action tokens, delivered-value boundary, and repo-local overlay topics |
| `open-pr` | PR opening protocol for REVIEW_READINESS, branch push, ready PR creation, and first management pass |
| `pickup` | resuming prior spec-tree work, loading a handoff session, claiming queued session work, or continuing from another saved context |
| `plan-slice` | selecting the next executable slice to implement, planning the next delivery increment, or deciding which spec-tree nodes /apply should build next from an implementation plan |
| `project-run-journal` | building a verification run's spx journal events, computing its rollup, or rendering its verdict from the run journal |
| `refactor` | moving nodes, re-scoping content, or extracting shared enablers |
| `refocus` | running ad hoc commands, writing debug scripts, or writing code without a spec |
| `review-changes` | reviewing working changes on a branch against a base ref |
| `review-pr` | reviewing a pull request or when the user asks to invoke the PR review skill |
| `scope-changeset` | deriving a changeset's base ref, branch slug, branch identity, or merge-base diff scope from git |
| `sync-base` | ALWAYS invoke this skill to bring a branch behind its base current — before reading product truth, before verifying, and before every merge push |
| `task-tracking-standards` | Runtime task-tracking standards for skills that schedule heartbeats or timers |
| `test` | ALWAYS invoke this skill before writing tests or when learning the testing approach |
| `understand` | ALWAYS invoke this skill before any spec-tree work to load methodology |
| `update-spx` | manually regenerating, refreshing, or scaffolding a product's two spx-level guide files (spx/CLAUDE.md and spx/AGENTS.md) from the installed spec-tree template |

## License

MIT
