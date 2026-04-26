# `omena-semantic`

Rust semantic boundary crate for Omena style analysis.

This crate owns generic style semantic contracts. CME-coupled graph assembly
can be layered on top through `omena-bridge`.

Current public products:

- `omena-semantic.style-semantic-boundary`
- `omena-semantic.selector-references`
- `omena-semantic.source-input-evidence`
- `omena-semantic.promotion-evidence`
- `omena-semantic.style-semantic-graph`
- `omena-semantic.theory-observation-harness`

`omena-semantic.source-input-evidence` includes value-domain derivation counts
from the source-backed expression-semantics payload.

Primary check:

```sh
cargo test
```
