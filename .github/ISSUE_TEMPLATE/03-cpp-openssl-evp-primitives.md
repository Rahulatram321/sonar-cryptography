---
name: "PR-03 OpenSSL EVP Primitives"
about: "Detect OpenSSL EVP symmetric/digest/HMAC usage"
title: "feat(cpp-openssl-evp): detect OpenSSL EVP symmetric/digest/HMAC primitives"
labels: ["type:feature", "area:cpp", "area:openssl", "area:rules", "priority:high"]
assignees: []
---

## Problem Statement
Core OpenSSL EVP primitive usage is not currently detected in C/C++.

## Tasks
- [ ] Add rules for `EVP_EncryptInit*`, `EVP_EncryptUpdate`, `EVP_EncryptFinal*`
- [ ] Add rules for `EVP_DecryptInit*`, `EVP_DecryptUpdate`, `EVP_DecryptFinal*`
- [ ] Add rules for `EVP_DigestInit*`, `EVP_DigestUpdate`, `EVP_DigestFinal*`
- [ ] Add HMAC family detection where EVP-backed
- [ ] Capture algorithm names and operation context
- [ ] Add dependent rule chaining where required
- [ ] Add fixtures: AES-CBC, AES-GCM, SHA-256, SHA-512, HMAC-SHA256
- [ ] Add exhaustive assertions for detection + translation

## Definition of Done
- [ ] EVP fixtures produce expected algorithm + operation nodes
- [ ] False positives reviewed on internal samples
- [ ] Rule graph export includes EVP family

## Dependencies
PR-02

