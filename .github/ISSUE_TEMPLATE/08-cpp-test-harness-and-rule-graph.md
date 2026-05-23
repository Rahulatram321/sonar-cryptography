---
name: "PR-08 C/C++ Test Harness"
about: "Add full test harness, fixtures, assert helper, and rule graph export for cpp"
title: "test(cpp): full test harness, fixtures, assert helper, and rule graph export"
labels: ["type:test", "area:cpp", "area:ci", "priority:high"]
assignees: []
---

## Problem Statement
C/C++ support needs stable testing and rule-graph visibility to prevent regressions.

## Tasks
- [ ] Add cpp `TestBase`
- [ ] Add fixture directory conventions and baseline fixtures
- [ ] Add assert helper for repetitive node assertions (optional but preferred)
- [ ] Add `ExportCppRulesToJsonTest`
- [ ] Add graph generation instructions/scripts for cpp rules
- [ ] Integrate cpp tests into CI
- [ ] Update contributor documentation for cpp rule testing workflow

## Definition of Done
- [ ] `mvn clean package` runs cpp tests in CI
- [ ] `target/rules.json` is generated for cpp
- [ ] New contributors can add cpp rule tests following docs only

## Dependencies
PR-07

