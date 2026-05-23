# Mentorship 15-PR Pack: Manual Creation Links

This file gives one branch per planned PR and a direct GitHub compare link so you can create PRs manually.

Repository used for links:
- `https://github.com/Rahulatram321/sonar-cryptography`
- Base branch: `main`

## Workflow (for each PR)
1. `git checkout main`
2. `git pull`
3. `git checkout -b <branch-name>`
4. Implement only that PR scope
5. `git add -A && git commit -m "<PR title>"`
6. `git push -u origin <branch-name>`
7. Open the compare link below
8. Use `.github/pull_request_template.md` and complete every checkbox before merge

## PR List + Compare Links

1. **feat(cpp): bootstrap C/C++ module and plugin wiring**  
   Branch: `mentorship/pr-01-cpp-bootstrap`  
   Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-01-cpp-bootstrap?expand=1

2. **feat(engine-cpp): implement C/C++ language adapters for detection engine**  
   Branch: `mentorship/pr-02-engine-cpp-adapters`  
   Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-02-engine-cpp-adapters?expand=1

3. **feat(cpp-openssl-evp): detect OpenSSL EVP symmetric/digest/HMAC primitives**  
   Branch: `mentorship/pr-03-openssl-evp`  
   Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-03-openssl-evp?expand=1

4. **feat(cpp-openssl-kdf-rng): detect PBKDF2/HKDF and random generation APIs**  
   Branch: `mentorship/pr-04-openssl-kdf-rng`  
   Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-04-openssl-kdf-rng?expand=1

5. **feat(cpp-openssl-pki): detect OpenSSL asymmetric crypto and keygen flows**  
   Branch: `mentorship/pr-05-openssl-pki`  
   Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-05-openssl-pki?expand=1

6. **feat(cpp-openssl-tls): detect TLS context/version/cipher-suite configuration**  
   Branch: `mentorship/pr-06-openssl-tls`  
   Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-06-openssl-tls?expand=1

7. **feat(cpp-translation): add C/C++ translation and reorganization pipeline**  
   Branch: `mentorship/pr-07-cpp-translation`  
   Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-07-cpp-translation?expand=1

8. **test(cpp): full test harness, fixtures, assert helper, and rule graph export**  
   Branch: `mentorship/pr-08-cpp-test-harness`  
   Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-08-cpp-test-harness?expand=1

9. **validation(cpp): real-world benchmark suite and detection accuracy report**  
   Branch: `mentorship/pr-09-cpp-validation`  
   Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-09-cpp-validation?expand=1

10. **feat(policy-cross-language): add actionable cryptographic policy rules beyond inventory**  
    Branch: `mentorship/pr-10-policy-cross-language`  
    Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-10-policy-cross-language?expand=1

11. **rfc: C/C++ parser and architecture decision record (ADR)**  
    Branch: `mentorship/pr-11-proposal-cpp-adr`  
    Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-11-proposal-cpp-adr?expand=1

12. **rfc: OpenSSL coverage matrix v1 (API -> crypto asset contract)**  
    Branch: `mentorship/pr-12-proposal-openssl-matrix`  
    Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-12-proposal-openssl-matrix?expand=1

13. **research: feasibility comparison for wolfSSL, libsodium, BoringSSL, Botan**  
    Branch: `mentorship/pr-13-proposal-cpp-libs-feasibility`  
    Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-13-proposal-cpp-libs-feasibility?expand=1

14. **research: Rust language and crypto ecosystem integration feasibility**  
    Branch: `mentorship/pr-14-proposal-rust-feasibility`  
    Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-14-proposal-rust-feasibility?expand=1

15. **rfc: OPA policy evaluation pack for CBOM workflows**  
    Branch: `mentorship/pr-15-proposal-opa-policy-pack`  
    Compare: https://github.com/Rahulatram321/sonar-cryptography/compare/main...Rahulatram321:mentorship/pr-15-proposal-opa-policy-pack?expand=1

## Merge-Readiness Rule
A PR is merge-ready only when all checkboxes in `.github/pull_request_template.md` are complete.
