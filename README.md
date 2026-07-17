# spec-tree

Spec Tree methodology skills for Outcome Engineering

> This repo is auto-generated from [outcomeeng/plugins](https://github.com/outcomeeng/plugins).
> For the shared marketplace, use `claude plugin marketplace add outcomeeng/plugins` or `codex plugin marketplace add outcomeeng/plugins`.

## Install

```bash
npx skills add outcomeeng/spec-tree
```

## Skills (37)

| Skill | Description |
| ----- | ----------- |
| `align` | reviewing, auditing, or checking spec file conformance |
| `apply` | ALWAYS invoke this skill before implementing any spec-tree work item |
| `audit-adr` | ADR audit methodology — judges one ADR against the ADR evidence model, covering section structure, atemporal voice, and per-rule tag validity |
| `audit-eval-evidence` | Eval-evidence audit methodology — judges whether a spec node's eval suite provides evidence its `[eval]` assertions are fulfilled, covering case quality, verdict schema fit, and producer coupling |
| `audit-implementation` | Implementation-audit orchestration methodology — discovers implementation languages, composes code, test, and architecture concern audits, and records one audit verification run |
| `audit-pdr` | PDR audit methodology — judges one PDR against the PDR evidence model, covering content classification, property quality, per-rule tag validity, atemporal voice, and consistency with ancestor decisions |
| `audit-specs` | Spec-node audit methodology — judges one enabler or outcome spec against the node-spec form, covering section structure, atemporal voice, and per-assertion tag fitness |
| `audit-tests` | Test-evidence audit methodology — judges whether a spec node's tests provide behavior-coupled evidence its assertions are fulfilled, covering source ownership, coupling, falsifiability, and full-chain coverage |
| `author` | adding, defining, or creating specs, decisions, or nodes |
| `bootstrap` | setting up a new spec tree or when /author detects an empty spx/ directory |
| `commit-changes` | committing changes or when user says "commit" |
| `contextualize` | asking about status, progress, or what exists in the spec tree |
| `decompose` | breaking down, splitting, scoping, composing, or structuring spec tree nodes |
| `diagnose` | diagnosing the health of a spec-tree or spx environment, when checking whether the SessionStart hook fired for the current session, or when troubleshooting a missing session identity, worktree claim, or unreachable spx CLI |
| `handoff` | ALWAYS invoke to close active spec-tree work or a merge lifecycle closeout — archive claimed sessions, decide session-file creation, prepare continuation context, and produce operator-useful closeout — only once its goal is met with no continuation remaining, the user halted work, context is exhausted, or an external blocker prevents the next action |
| `init-worktrees` | setting up a repository's git worktree layout — classifying a checkout as a single tree, a bare-repo worktree pool, or non-compliant, and provisioning the bare-repo pool while pushing every local ref to the remote and carrying a prior checkout's gitignored state across |
| `inspect-github-actions` | the user asks about CI failures, workflow logs, GitHub Actions status, pipeline issues, or troubleshooting failed builds |
| `interview` | ALWAYS invoke before requirements interviews, draft approval, or unresolved scope/design questions while creating or modifying an artifact (spec, ADR, PDR, test, code, doc) |
| `issue` | filing a follow-up into a spec-tree dependency's own session queue — for observations about the spec-tree plugin, the spx CLI, or another spec-tree dependency needing a change |
| `manage-github-pr` | the user asks to open or manage a GitHub pull request, or runs /manage-github-pr |
| `manage-pr` | managing, waiting on, or continuing an open pull request lifecycle after a PR exists |
| `merge` | the user asks to ship, integrate, or merge a changeset into the default branch on origin, or runs /merge |
| `merging-standards` | Shared vocabulary for the merge lifecycle — pre-flight predicates, branch topology gate, push command, authority gates, review classification, integration review surfaces, action tokens, delivered-value boundary, closeout, and repo-local overlay topics |
| `open-pr` | PR opening protocol for VERIFICATION_READINESS, branch push, ready PR creation, and first management pass |
| `pickup` | resuming prior spec-tree work, loading a handoff session, claiming queued session work, or continuing from another saved context |
| `project-run-journal` | Verification run-journal projection methodology loaded by audit and review skills when building spx journal events, computing rollups, or rendering verdict surfaces |
| `refactor` | moving nodes, re-scoping content, or extracting shared enablers |
| `refocus` | running ad hoc commands, writing debug scripts, or writing code without a spec |
| `review-changes` | reviewing working changes on a branch against a base ref |
| `scope-changeset` | Canonical git-derived changeset primitives loaded by verification and lifecycle skills instead of re-implementing branch, base-ref, commit-identity, slug, or diff-scope derivation |
| `slice` | selecting the next executable slice to implement or deciding which spec-tree nodes /apply should build next from an implementation plan |
| `sync-base` | ALWAYS invoke this skill to bring a branch behind its base current — before reading product truth, before verifying, and before every merge push |
| `task-tracking-standards` | Runtime task-tracking standards for skills that schedule heartbeats or timers |
| `test` | ALWAYS invoke this skill before writing tests or when learning the testing approach |
| `understand` | the live SPEC_TREE_FOUNDATION marker is absent before direct filesystem access under spx/ or before reading, searching, listing, or changing source or test files |
| `update-instruction-block` | manually regenerating, refreshing, or scaffolding a product's root CLAUDE.md and AGENTS.md managed Spec Tree instruction surface from the installed spec-tree template, or reconciling a `shared` region that differs between the two files |
| `wait-for-load` | ALWAYS invoke this skill before starting a resource-intensive local command or when host load is high |

## License

MIT
