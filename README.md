# spec-tree

Spec Tree methodology skills for Outcome Engineering

> This repo is auto-generated from [outcomeeng/plugins](https://github.com/outcomeeng/plugins).
> For the shared marketplace, use `claude plugin marketplace add outcomeeng/plugins` or `codex plugin marketplace add outcomeeng/plugins`.

## Install

```bash
npx skills add outcomeeng/spec-tree
```

## Skills (31)

| Skill | Description |
| ----- | ----------- |
| `aligning` | reviewing, auditing, or checking spec file conformance |
| `applying` | ALWAYS invoke this skill before implementing any spec-tree work item |
| `audit-adr` | ALWAYS use when auditing an ADR or after making changes to an ADR |
| `audit-pdr` | ALWAYS use when auditing a PDR or after making changes to a PDR |
| `auditing` | auditing a code scope end-to-end — a diff, a branch, or a commit — partitioning by language and emitting one structured verdict |
| `auditing-tests` | auditing test evidence against spec assertions |
| `authoring` | adding, defining, or creating specs, decisions, or nodes |
| `bootstrapping` | setting up a new spec tree or when /authoring detects an empty spx/ directory |
| `changeset-scope` | deriving a changeset's base ref, branch slug, branch identity, or merge-base diff scope from git |
| `committing-changes` | committing changes or when user says "commit" |
| `contextualizing` | asking about status, progress, or what exists in the spec tree |
| `decomposing` | breaking down, splitting, scoping, composing, or structuring spec tree nodes |
| `github-actions` | the user asks about CI failures, workflow logs, GitHub Actions status, pipeline issues, or troubleshooting failed builds |
| `github-pr` | the user asks to open or manage a GitHub pull request, or runs /github-pr |
| `handoff` | ALWAYS invoke to close a claimed spec-tree session — archive it, decide session-file creation, prepare continuation context — only once its goal is met with no continuation remaining or continuation by Claude is impossible (context exhausted, user halted, external blocker) |
| `init-worktrees` | setting up a repository's git worktree layout — classifying a checkout as a single tree, a bare-repo worktree pool, or non-compliant, and provisioning the bare-repo pool while pushing every local ref to the remote and carrying a prior checkout's gitignored state across |
| `interviewing` | ALWAYS invoke BEFORE asking the user anything while creating or modifying any artifact (spec, ADR, PDR, test, code, doc) |
| `managing-pr` | Open-PR management protocol for review and check inspection, follow-up pushes, merge gates, and post-merge cleanup |
| `merge` | the user asks to ship, integrate, or merge a changeset into the default branch on origin, or runs /merge |
| `opening-pr` | PR opening protocol for REVIEW_READINESS, branch push, ready PR creation, and first management pass |
| `pickup` | resuming prior spec-tree work, loading a handoff session, claiming queued session work, or continuing from another saved context |
| `refactoring` | moving nodes, re-scoping content, or extracting shared enablers |
| `refocusing` | running ad hoc commands, writing debug scripts, or writing code without a spec |
| `reviewing-changes` | reviewing working changes on a branch against a base ref |
| `reviewing-pr` | reviewing a pull request or when the user asks to invoke the PR review skill |
| `standardizing-merging` | Shared vocabulary for the merge lifecycle — pre-flight predicates, branch topology gate, push command, the three authority gates (review / merge / production readiness), review classification, integration review surfaces, action tokens, delivered-value boundary, and repo-local overlay topics |
| `testing` | ALWAYS invoke this skill before writing tests or when learning the testing approach |
| `thread-store` | persisting or retrieving branch-scoped verification records |
| `tracking-tasks` | Runtime task-tracking standards for skills that schedule heartbeats or timers |
| `understanding` | ALWAYS invoke this skill before any spec-tree work to load methodology |
| `update-spx` | updating, refreshing, or scaffolding a product's spx/CLAUDE.md from the installed spec-tree template |

## License

MIT
