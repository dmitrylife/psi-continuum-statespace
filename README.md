# Psi–Continuum State-Space Diagnostics

This repository will host state-space diagnostic tools for the
Psi–Continuum cosmology framework.

The project provides a macroscopic state-space representation of
late-time cosmic expansion, constructed as a derived diagnostic
using the frozen Psi–Continuum v2 background API.

## Scope

This package implements **diagnostic state-space analysis only**.
It does not introduce new cosmological models, modify the Psi–Continuum
v2 API, or perform parameter fitting.

All results are derived exclusively from the frozen background-level
functions provided by Psi–Continuum v2.

The package is designed to support fully reproducible state-space diagnostics.

🚧 **Work in progress**

The API and documentation are still stabilizing.

## Current status

- Core state-space diagnostics implemented
- Interactive command-line interface available
- Reproducible numerical metrics and figures supported

## Quick start (development)

```bash
python -m psi_continuum_statespace.cli interactive
```
