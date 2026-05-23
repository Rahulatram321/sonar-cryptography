---
name: "PR-10 Cross-Language Policy Rules"
about: "Add actionable policy rules beyond inventory"
title: "feat(policy-cross-language): add actionable cryptographic policy rules beyond inventory"
labels: ["type:feature", "area:policy", "area:rules", "priority:high"]
assignees: []
---

## Problem Statement
Inventory-only output is not enough for immediate security governance and remediation.

## Tasks
- [ ] Define v1 policy rule set and scope
- [ ] Implement shared policy logic in `rules` module where reusable
- [ ] Integrate policy rule classes into Java
- [ ] Integrate policy rule classes into Python
- [ ] Integrate into Go/C# where feasible with current engine capability
- [ ] Add tests for trigger and non-trigger scenarios per language
- [ ] Add Sonar metadata docs and remediation messaging

## Definition of Done
- [ ] Policy rules appear in Sonar repositories with metadata
- [ ] Policy issues include clear remediation guidance
- [ ] Existing inventory output remains unchanged

## Dependencies
PR-07

