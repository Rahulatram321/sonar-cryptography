---
name: "PR-09 C/C++ Validation Report"
about: "Validate cpp openssl detection on real-world projects and publish report"
title: "validation(cpp): real-world benchmark suite and detection accuracy report"
labels: ["type:validation", "area:cpp", "area:quality", "priority:high"]
assignees: []
---

## Problem Statement
Production confidence requires measurable validation against real-world C/C++ repositories.

## Tasks
- [ ] Define benchmark project selection criteria
- [ ] Select benchmark repos and lock commit hashes
- [ ] Create reproducible scan script/runbook
- [ ] Run scans and classify TP/FP/FN samples
- [ ] Publish primitive-family coverage summary
- [ ] Document known gaps and root causes
- [ ] Add reproducibility instructions and troubleshooting section

## Definition of Done
- [ ] Validation report published under docs
- [ ] Scripted validation is reproducible on fresh setup
- [ ] Mentor-reviewable quality metrics and findings are available

## Dependencies
PR-08

