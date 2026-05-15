# Phase-Change Numerical Benchmarks

A community-maintained catalog of verification and validation benchmarks for
numerical methods for phase-change problems.

The goal is to provide clear, reproducible benchmark definitions for:

- Stefan problems
- melting and solidification
- evaporation and condensation
- boiling flows
- vapor bubble growth
- phase change with hydrodynamics
- sharp-interface and diffuse-interface methods
- front-tracking, level-set, VOF, enthalpy, cut-cell and immersed methods

This organization follows the spirit of the historical [interface-tracking
test-case collections](http://test.interface.free.fr/) : one benchmark, one clear document, one stable identifier.

## Main repository

- `benchmarks`: benchmark definitions, reference data, contribution guidelines.

## Benchmark status

Each benchmark is marked as:

- `draft`: incomplete definition
- `ready`: problem fully specified
- `reference-data`: reference curves or datasets available
- `community-tested`: several codes have reported results
- `archived`: kept for traceability but not actively maintained

## How to contribute

You can contribute by:

1. proposing a new benchmark,
2. improving an existing definition,
3. adding reference data,
4. submitting numerical results,
5. reporting ambiguity in a case definition.

See `CONTRIBUTING.md` in the main repository.