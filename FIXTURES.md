# Sivanta Web Context deterministic fixtures

This public repository contains **non-secret deterministic test documents only** for production runtime certification of Sivanta Web Context.

The fixture semantics are generated from the canonical `benchmarks/document/generate_fixtures.py` contract in the private Sivanta source repository. Production certification MUST use commit-pinned raw GitHub URLs, never branch-floating URLs.

## Fixture hashes

- `fixtures/native.pdf`: `0f79e631489a7040cfc21f409697d00b1962aa1d82c0268ea60fdb9700f9a536`
- `fixtures/scanned.pdf`: `372bd4ee1bbcd9311f2a94bf79e81800c63947a854e1b4ca0d8a1e2045e3cd4c`
- `fixtures/sample.docx`: `12a7506f7dcbc31a336ac9b5893410fb110c1c7a3d90cba9cc7275a9299d5990`
- `fixtures/sample.pptx`: `aeab3915332d5c175bf3624d9ccdd34222f30c1ab185a689fe0c1137f087da49`

## Expected semantic markers

All formats contain `InfraForge Document Benchmark`, `Scrapling Web Context Platform`, `Search`, `HTTP`, `Ready`, `Documents`, and `Benchmark`. Native PDF/DOCX/PPTX contain `Native`; scanned PDF contains `OCR`.
