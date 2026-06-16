# The Token Economy Model

An interactive, single-page Fermi model of the global AI compute stack heading into 2030. Tune how fast token demand grows and watch it flow through the physics — **tokens → GPUs → HBM → power** — surfacing the constraint that actually gates the buildout at each step.

**Live demo:** https://mol2017.github.io/token-economy-model/

## What it models

- **§0 Assumptions** — the two load-bearing premises (mandatory "Red Queen" AI adoption; no breakthrough in video/physical AI).
- **§1 Token demand** — one growth dial (1–50×) projects 2026 → 2030 against reported 2023–25 actuals and the Goldman Sachs 24× benchmark, on an animated chart with hoverable data points.
- **§2 GPUs + HBMs** — converts demand into GPU counts, derived HBM stacks, and **time-to-build** for H100 / B200 / Rubin, using each chip's real TSMC packaging and HBM-stacking throughput. Flags whether each fleet is HBM- or GPU-limited.
- **§3 Power** — turns the fleet into facility power draw (GW), annual energy (TWh), and build-out lead time across four energy sources (Bloom fuel cells, solar+wind, natural gas, nuclear).

A binding-constraint verdict ties it together.

## Notes

This is a back-of-the-envelope teaching tool, not a forecast. Inputs are tunable and approximate; figures are drawn from public reporting (Goldman Sachs, Google/OpenRouter token disclosures, NVIDIA/TSMC/HBM supply-chain estimates, EIA grid data) and clearly-stated assumptions. "Claude Fable 5" is a hypothetical 2030 frontier model used to anchor the active-parameter size.

## Run locally

It's a single self-contained file — just open `index.html` in any browser.
