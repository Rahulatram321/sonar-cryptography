---
name: "PR-05 OpenSSL Asymmetric and Keygen"
about: "Detect OpenSSL asymmetric crypto operations and key generation"
title: "feat(cpp-openssl-pki): detect OpenSSL asymmetric crypto and keygen flows"
labels: ["type:feature", "area:cpp", "area:openssl", "area:asymmetric", "priority:high"]
assignees: []
---

## Problem Statement
Asymmetric cryptography in OpenSSL is critical but currently not covered for C/C++.

## Tasks
- [ ] Add EVP_PKEY key generation rule family
- [ ] Add RSA sign/verify and encrypt/decrypt detection
- [ ] Add EC/ECDSA sign/verify and key generation detection
- [ ] Add X25519/Ed25519 detection where API patterns are stable
- [ ] Capture key size/curve metadata when available
- [ ] Add dependent rules for context/setup sequences
- [ ] Add representative fixtures and full assertions
- [ ] Document unsupported API variants explicitly

## Definition of Done
- [ ] Asymmetric fixtures produce algorithm + operation + key metadata
- [ ] Detection remains stable under call-order variations
- [ ] No regressions in previous OpenSSL rule families

## Dependencies
PR-03

