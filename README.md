<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->
# Awesome Z3

Learn to express a constraint, ask for a model and examine what changes when you strengthen the constraint.

- [Online Z3 Guide](https://microsoft.github.io/z3guide/) — Try the interactive examples in the arithmetic or bit-vector section.
- [Programming Z3](https://theory.stanford.edu/~nikolaj/programmingz3.html) — Study incremental solving, assumptions and unsatisfiable cores after your first model.
- [Source and releases](https://github.com/Z3Prover/z3) — Install a release and inspect examples for your chosen API. Use the issue tracker for reproducible solver defects.
- [SMT-LIB](https://smt-lib.org/) — Check the logic, theory and command definitions when sharing a solver-independent input.

## A first exercise

In the online guide declare an integer x, assert x > 0 and request a model after check-sat. Add x < 0 and check again. Compare the two results.

## Curation

Stuff of Awe starter collection, assembled 3 November 2026. Original annotations link to the authors' resources. Our initial GitHub name search found no dedicated awesome list for this tool. Suggestions for upstream collections are welcome. The exercise is a reading or practice prompt and has not been execution-tested here. Open an issue or PR here for corrections, version caveats or additions. [Editorial guidance](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/MAINTENANCE.adoc).