---
name: "Task"
about: "One task for one PR: goal, acceptance criteria, how to verify."
---

## Goal

[One sentence: what works after this issue that does not work today.]

## Context

Spec: [factory/specs/NNNN-slug.md]
Depends on: [#issue, or none]

## Acceptance criteria

- [ ] [Observable behaviour. Proved by: the test that checks it.]

## How to verify

[Exact commands and their expected result, e.g. `scripts/check.sh` green, then
`go -C backend test ./services/<service>/...`, then `curl …` returns 200 with fields x and y.]

## Where to look

[Files to change, and an existing example to copy.]

## Constraints

[Must and must not, beyond AGENTS.md: performance, compatibility, libraries to use or avoid.]

## API impact

[None, or the contract change: service, operations, schemas.]

## Out of scope

[What this issue does not do, to keep the PR small.]
