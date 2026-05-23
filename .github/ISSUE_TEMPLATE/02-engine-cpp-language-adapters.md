---
name: "PR-02 Engine C/C++ Adapters"
about: "Implement C/C++ language adapters for the detection engine"
title: "feat(engine-cpp): implement C/C++ language adapters for detection engine"
labels: ["type:feature", "area:engine", "area:cpp", "priority:high"]
assignees: []
---

## Problem Statement
Without C/C++ language adapters, detection rules cannot execute over C/C++ AST nodes.

## Tasks
- [ ] Implement `CppLanguageSupport`
- [ ] Implement `CppDetectionEngine`
- [ ] Implement `CppLanguageTranslation`
- [ ] Implement `CppScanContext`
- [ ] Implement C/C++ base visitor/traversal adapter
- [ ] Register `cppLanguageSupporter()` in `LanguageSupporter`
- [ ] Add unit tests for call matching and parameter extraction
- [ ] Add unit tests for value/literal resolution
- [ ] Document known engine limitations for cpp

## Definition of Done
- [ ] Minimal cpp detection rule matches function call in tests
- [ ] New engine tests pass in CI
- [ ] No regressions in existing language test suites

## Dependencies
PR-01

