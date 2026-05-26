# spec-tree

Spec Tree methodology skills for Outcome Engineering

> This repo is auto-generated from [outcomeeng/plugins](https://github.com/outcomeeng/plugins).
> For the shared marketplace, use `claude plugin marketplace add outcomeeng/plugins` or `codex plugin marketplace add outcomeeng/plugins`.

## Install

```bash
npx skills add outcomeeng/spec-tree
```

## Skills (24)

| Skill | Description |
| ----- | ----------- |
| `aligning` | reviewing, auditing, or checking spec file conformance |
| `applying` | ALWAYS invoke this skill before implementing any spec-tree work item |
| `auditing` | Use when asked by the user to invoke the audit skill |
| `auditing-product-decisions` | Use when asked by the user to invoke the PDR audit skill |
| `auditing-tests` | Use when asked by the user to invoke the test evidence audit skill |
| `authoring` | adding, defining, or creating specs, decisions, or nodes |
| `bootstrapping` | setting up a new spec tree or when /authoring detects an empty spx/ directory |
| `committing-changes` | committing changes or when user says "commit" |
| `contextualizing` | asking about status, progress, or what exists in the spec tree |
| `decomposing` | breaking down, splitting, scoping, composing, or structuring spec tree nodes |
| `github-actions` | the user asks about CI failures, workflow logs, GitHub Actions status, pipeline issues, or troubleshooting failed builds |
| `handing-off` | ALWAYS invoke when closing an in-scope spec-tree session, deciding whether to create a handoff, writing a handoff, or preparing continuation context |
| `interviewing` | ALWAYS invoke BEFORE asking the user anything while creating or modifying any artifact (spec, ADR, PDR, test, code, doc) |
| `managing-pr` | managing an open pull request after PR creation — inspecting review and check state, classifying review feedback, posting findings, pushing follow-up commits, or deciding the next PR lifecycle action |
| `opening-pr` | opening a pull request, creating a PR, or pushing a branch for review |
| `picking-up` | resuming prior spec-tree work, loading a handoff session, claiming queued session work, or continuing from another saved context |
| `refactoring` | moving nodes, re-scoping content, or extracting shared enablers |
| `refocusing` | running ad hoc commands, writing debug scripts, or writing code without a spec |
| `reviewing-changes` | the wrapper agent reviews the working changes on a branch against a base ref |
| `reviewing-pr` | Use when asked by the user to invoke the PR review skill |
| `standardizing-merging` | Shared vocabulary for the PR flow — pre-flight predicates, branch topology gate, push command, the three PR-authority gates (review / merge / production readiness), review classification, three review surfaces, action tokens, and repo-local overlay topics |
| `testing` | ALWAYS invoke this skill before writing tests or when learning the testing approach |
| `thread-store` | persisting or retrieving branch-scoped verification records |
| `understanding` | ALWAYS invoke this skill before any spec-tree work to load methodology |

## License

MIT
