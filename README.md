# spec-tree

Spec Tree methodology skills for Outcome Engineering

> This repo is auto-generated from [outcomeeng/plugins](https://github.com/outcomeeng/plugins).
> For the shared marketplace, use `claude plugin marketplace add outcomeeng/plugins` or `codex plugin marketplace add outcomeeng/plugins`.

## Install

```bash
npx skills add outcomeeng/spec-tree
```

## Skills (20)

| Skill | Description |
| ----- | ----------- |
| `aligning` | reviewing, auditing, or checking spec file conformance |
| `applying` | ALWAYS invoke this skill before implementing any spec-tree work item |
| `auditing` | running an audit pass over a code scope. Produces one structured wrapper verdict whose children carry per-language dispatched verdicts, by dispatching to language-specific auditing-{lang}* skills |
| `auditing-product-decisions` | auditing PDRs or after writing a PDR |
| `auditing-tests` | auditing test evidence quality, after writing tests for a spec node, or before closing an outcome |
| `authoring` | adding, defining, or creating specs, decisions, or nodes |
| `bootstrapping` | setting up a new spec tree or when /authoring detects an empty spx/ directory |
| `committing-changes` | committing changes or when user says "commit" |
| `contextualizing` | asking about status, progress, or what exists in the spec tree |
| `decomposing` | breaking down, splitting, scoping, composing, or structuring spec tree nodes |
| `github-actions` | the user asks about CI failures, workflow logs, GitHub Actions status, pipeline issues, or troubleshooting failed builds |
| `handing-off` | ALWAYS invoke when closing an in-scope spec-tree session, deciding whether to create a handoff, writing a handoff, or preparing continuation context |
| `interviewing` | ALWAYS invoke BEFORE asking the user anything while creating or modifying any artifact (spec, ADR, PDR, test, code, doc) |
| `opening-pr` | opening a pull request, creating a PR, or pushing a branch for review |
| `picking-up` | resuming prior spec-tree work, loading a handoff session, claiming queued session work, or continuing from another agent's saved context |
| `refactoring` | moving nodes, re-scoping content, or extracting shared enablers |
| `refocusing` | running ad hoc commands, writing debug scripts, or writing code without a spec |
| `reviewing-pr` | reviewing a pull request — produces constructive review feedback on code quality, bugs, performance, security, and test coverage, grounded in the repository's own conventions |
| `testing` | ALWAYS invoke this skill before writing tests or when learning the testing approach |
| `understanding` | ALWAYS invoke this skill before any spec-tree work to load methodology |

## License

MIT
