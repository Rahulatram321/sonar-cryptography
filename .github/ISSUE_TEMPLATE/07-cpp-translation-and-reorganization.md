---
name: "PR-07 C/C++ Translation Pipeline"
about: "Add translation and reorganizer flow for C/C++ detections"
title: "feat(cpp-translation): add C/C++ translation and reorganization pipeline"
labels: ["type:feature", "area:cpp", "area:translation", "area:reorganizer", "priority:high"]
assignees: []
---

## Problem Statement
Raw detection trees are not enough; semantically organized node trees are required for robust CBOM output.

## Tasks
- [ ] Implement `CppTranslator`
- [ ] Add context translators under cpp translation contexts
- [ ] Add `CppReorganizerRules` and required mapper-level reorganizer rules
- [ ] Implement `CppTranslationProcess` (translate -> reorganize -> enrich)
- [ ] Wire translation process into cpp base detection rule and test base
- [ ] Add tests for translated/reorganized/enriched outputs
- [ ] Add/update docs for cpp translation architecture

## Definition of Done
- [ ] Output tree semantics match expected relationships
- [ ] Enrichment runs correctly for translated cpp nodes
- [ ] Assertions cover both detection stores and final node trees

## Dependencies
PR-03, PR-04, PR-05, PR-06

