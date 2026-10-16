# zynko-oracle · `php-run-length-encoding-encode-conformance-oracle`

**A deterministic, re-checkable conformance oracle for `run-length-encoding` (php).**

## Proven
Measured on the canonical Exercism corpus — **7 input/output pairs, 7 distinct outputs** — produced by *running* the reference in a sealed sandbox, not asserted.

## Scope (declared)
The corpus is the canonical Exercism test data for `run-length-encoding`. Inputs outside that set are **not covered**; this oracle decides agreement on the published corpus only and makes no claim of general correctness.

## Provenance
Reference: the Exercism reference solution for `run-length-encoding` (php; MIT, Exercism), body unchanged. Proven by the exercism testsuite (pin=5eba12c1b7a9a238), re-executed by harvest in a sealed sandbox (unshare -rn) before this bundle was generated.

## License
Apache-2.0 for the scaffolding; the reference body retains its upstream MIT (Exercism) license.
