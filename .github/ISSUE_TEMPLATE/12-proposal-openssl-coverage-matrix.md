---
name: "PR-12 Proposal: OpenSSL Coverage Matrix"
about: "Define OpenSSL API-to-asset coverage matrix contract"
title: "rfc: OpenSSL coverage matrix v1 (API -> crypto asset contract)"
labels: ["type:proposal", "area:openssl", "area:planning", "priority:high"]
assignees: []
---

## Problem Statement
OpenSSL support needs a measurable, reviewable contract for implementation and acceptance.

## Tasks
- [ ] Build OpenSSL API inventory by primitive family
- [ ] Define must-have and should-have sets
- [ ] Define expected captured fields per API family
- [ ] Map each API to detection + translation strategy
- [ ] Mark deferred APIs with rationale
- [ ] Publish coverage matrix in docs

## Definition of Done
- [ ] Mentor-approved matrix used as implementation baseline
- [ ] All implementation PRs reference matrix rows

## Dependencies
PR-11

