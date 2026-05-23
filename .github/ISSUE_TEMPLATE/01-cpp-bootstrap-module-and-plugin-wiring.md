---
name: "PR-01 C/C++ Bootstrap"
about: "Bootstrap C/C++ module and plugin wiring"
title: "feat(cpp): bootstrap C/C++ module and plugin wiring"
labels: ["type:feature", "area:cpp", "area:plugin", "priority:high"]
assignees: []
---

## Problem Statement
CBOMkit plugin currently has no C/C++ scan path, so C/C++ repositories cannot produce cryptographic inventory.

## Tasks
- [ ] Create `cpp` module and register it in root `pom.xml`
- [ ] Add cpp dependency to `sonar-cryptography-plugin/pom.xml`
- [ ] Add C/C++ file extensions/language wiring
- [ ] Add `CppScannerRuleDefinition`
- [ ] Add `CppRuleList` and `CppInventoryRule` shell
- [ ] Add `CppAggregator` and wire into scanner aggregation
- [ ] Register cpp extensions in plugin class
- [ ] Add plugin-level test updates for extension registration
- [ ] Update docs/readme for cpp support status

## Definition of Done
- [ ] Sonar scan runs on sample C/C++ source without runtime failure
- [ ] Inventory rule is visible for cpp repository
- [ ] Existing Java/Python/Go/C# behavior remains unchanged

## Dependencies
None

