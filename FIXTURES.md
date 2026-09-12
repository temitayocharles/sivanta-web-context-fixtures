# Sivanta Web Context deterministic fixtures

This public repository contains **non-secret deterministic test documents only** for production runtime certification of Sivanta Web Context.

The fixtures are generated from the canonical `benchmarks/document/generate_fixtures.py` contract in the private Sivanta source repository. Production certification MUST use commit-pinned raw GitHub URLs, never branch-floating URLs.

## Current native fixture

- `fixtures/native.pdf`
- SHA-256: `0f79e631489a7040cfc21f409697d00b1962aa1d82c0268ea60fdb9700f9a536`
- Expected markers: `InfraForge Document Benchmark`, `Scrapling Web Context Platform`, `Search`, `HTTP`, `Ready`, `Documents`, `Native`, `Benchmark`

Additional scanned PDF, DOCX, and PPTX fixtures will use the same deterministic semantic contract.
