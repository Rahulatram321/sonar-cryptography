---
name: "PR-06 OpenSSL TLS Config"
about: "Detect TLS context/version/cipher-suite configuration in OpenSSL"
title: "feat(cpp-openssl-tls): detect TLS context/version/cipher-suite configuration"
labels: ["type:feature", "area:cpp", "area:tls", "area:mapper", "priority:high"]
assignees: []
---

## Problem Statement
TLS posture in C/C++ OpenSSL (protocol and cipher configuration) is not visible in inventory output.

## Tasks
- [ ] Add rules for `SSL_CTX_new` and key TLS context APIs
- [ ] Add rules for protocol version configuration APIs
- [ ] Add rules for cipher suite list APIs
- [ ] Reuse existing SSL mapper logic for OpenSSL suite names where possible
- [ ] Add TLS protocol/cipher translator mappings for cpp
- [ ] Add fixtures for modern/legacy TLS configuration patterns
- [ ] Add assertions for protocol and cipher suite node output

## Definition of Done
- [ ] TLS fixtures emit version and cipher suite inventory nodes
- [ ] Known OpenSSL suite names normalize correctly
- [ ] Unknown suites fallback consistently without runtime failure

## Dependencies
PR-03, PR-04, PR-05

