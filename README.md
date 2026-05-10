# Verifiable Task Chains Benchmark

This repository contains the artefacts accompanying the paper *“Evaluating Long‑Horizon Reasoning and Self‑Correction in Large Language Models with Verifiable Task Chains”*.  It provides everything needed to **understand, inspect, and reproduce** the core evaluation components:

- Exact prompts for every task chain step
- Full `pytest` unit‑test suites for all steps
- Aggregated results from the paper

The benchmark measures sequential Python code generation and single‑attempt self‑correction under conditions where earlier code is extended or refactored at every step, and all previous tests are re‑run (cumulative regression).

The results are from a benchmark run in November 2025. The prices listed are the exact prices returned by the OpenRouter API for each model run. Model names in this repository are based on the naming scheme used by OpenRouter, with the exception of the provider name.