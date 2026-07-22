# Recovered Test Provenance

This folder contains only test artifacts directly identified as relevant in the analysis conversation. It does not include unrelated files whose names merely contained `stress_test`.

## 1. Small-curvature perturbative analytical check

Repository copy:

- `tests/recovered/perturbative_small_curvature_check.py`

Original workspace artifact:

- `/mnt/e/my theory/perturbative analytical check for small curvature.py`
- Inventory SHA-256 prefix: `bf0445ff3631`

Characteristics:

- Dependencies: NumPy and Matplotlib
- External inputs: none
- Generated output: `Perturbative_Stability_Check.png`
- Purpose: compare the full effective-resolution expression against its first-order perturbative expansion over `epsilon = 0..0.2`

The source was preserved as supplied in the conversation. Its plotted `Stability: PASS` annotation is hard-coded by the historical script and is not treated here as an independently evaluated acceptance result.

## 2. Delta-physical stress test

Confirmed original locations:

- `/mnt/e/my theory/delta_phys_stress_test.py`
- `/mnt/e/Downloads/delta_phys_stress_test.py`

Both inventory entries have the same SHA-256:

`2d6965cc31ad60913eda73f3c934251592b2e988b7e3400c9bcf655a2773cdbe`

Canonical provenance location:

- `/mnt/e/my theory/delta_phys_stress_test.py`

The complete source text of this script was not pasted into the analyzed conversation segment, so no reconstructed repository copy has been invented. It should be copied from the canonical workspace path in a later source-ingestion pass.

## Excluded false-positive stress tests

The following artifacts appeared only because of the broad filename term `stress_test`. Their membership in the delta-physical experiment was not established, so they were not uploaded as relevant tests:

- `mapping_stress_test.py` — SHA-256 prefix `40b9483466a8`
- `stress_tester.py` — SHA-256 prefix `701fef7d1afd`
- `ultimate_stress_test.py` — SHA-256 prefix `ce3a33bc8927`

These files occur repeatedly in active trees, recovered backups, and reproduction sandboxes, but path duplication alone does not establish scientific relevance to this test unit.
