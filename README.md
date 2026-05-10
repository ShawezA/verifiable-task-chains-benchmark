# Verifiable Task Chains Benchmark

This repository contains the artefacts accompanying the paper *“Evaluating Long‑Horizon Reasoning and Self‑Correction in Large Language Models with Verifiable Task Chains”*.  It provides everything needed to **understand, inspect, and reproduce** the core evaluation components:

- Exact prompts for every task chain step
- Full `pytest` unit‑test suites for all steps
- Model specifications (versions, run dates, and cost assumptions)
- Aggregated results from the paper

The benchmark measures sequential Python code generation and single‑attempt self‑correction under conditions where earlier code is extended or refactored at every step and all previous tests are re‑run (cumulative regression).
