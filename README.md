# Sivanta Web Context Fixtures

Public, deterministic, non-secret fixtures used to certify Sivanta Web Context behavior across common document formats.

## Why this repository exists

Runtime certification is stronger when the input corpus is stable, inspectable, and safe to share. These fixtures provide known inputs that can be fetched repeatedly without depending on private customer content or mutable third-party pages.

The repository currently includes representative inputs for:

- native-text PDF;
- scanned PDF;
- DOCX;
- PPTX.

See [FIXTURES.md](./FIXTURES.md) for the fixture inventory and expected characteristics.

## Engineering evidence

This is a deliberately small supporting repository. It demonstrates an operational testing pattern rather than a standalone product:

1. keep certification inputs deterministic;
2. keep them non-secret and publicly inspectable;
3. exercise format-specific extraction paths against known evidence;
4. separate test/certification data from production or customer data;
5. make regressions reproducible instead of relying on ad hoc URLs.

That pattern is used to support runtime verification of web/document-context systems while preserving a clear data-safety boundary.

## Scope boundary

These files are synthetic or purpose-built certification fixtures. They are not customer documents, credentials, production exports, or a substitute for the private implementation repositories that consume them.
