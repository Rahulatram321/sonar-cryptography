---
name: "PR-04 OpenSSL KDF and RNG"
about: "Detect PBKDF2/HKDF and random generation usage"
title: "feat(cpp-openssl-kdf-rng): detect PBKDF2/HKDF and random generation APIs"
labels: ["type:feature", "area:cpp", "area:openssl", "area:rules", "priority:high"]
assignees: []
---

## Problem Statement
KDF and random generation usage are missing in C/C++ OpenSSL inventory.

## Tasks
- [ ] Add rule for `PKCS5_PBKDF2_HMAC`
- [ ] Add HKDF detect rules (extract/expand style APIs where applicable)
- [ ] Add RNG rules (`RAND_bytes` and related APIs)
- [ ] Capture iterations/key length/salt length when resolvable
- [ ] Add KDF/random context mappings
- [ ] Add fixtures with varied parameter styles
- [ ] Add assertions for captured parameters and source evidence
- [ ] Document unsupported parameter resolution edge cases

## Definition of Done
- [ ] KDF fixtures emit KDF nodes with parameter children
- [ ] RNG usage appears with proper evidence location
- [ ] CI remains stable and green

## Dependencies
PR-03

