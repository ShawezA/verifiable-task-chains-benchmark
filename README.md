# Verifiable Task Chains Benchmark

This repository contains the artefacts accompanying the paper
*"Evaluating Long-Horizon Reasoning and Self-Correction in Large Language
Models with Verifiable Task Chains"* to appear at PACIS 2026.

It provides everything needed to **understand, inspect, and replicate** the
benchmark artefacts and reported metrics:

- Exact prompts for every task chain step
- Full `pytest` unit-test suites for all steps
- Aggregated results from the paper

The benchmark measures sequential Python code generation and single-attempt
self-correction under conditions where earlier code is extended or refactored
at every step, and all previous tests are re-run (cumulative regression).

Pilot development runs were conducted from 2025-08-17. The actual model
evaluation runs reported in the paper were conducted on October 12–14 and
November 21, 2025. Reported API costs reflect the USD values returned by the
OpenRouter API at the time of each run. Model names follow the OpenRouter
naming scheme.

## Models

| Paper Name       | OpenRouter ID                        |
|------------------|--------------------------------------|
| GPT-5            | openai/gpt-5-2025-08-07              |
| GPT-5 Mini       | openai/gpt-5-mini-2025-08-07         |
| GPT-5 Nano       | openai/gpt-5-nano-2025-08-07         |
| Grok 4 Fast      | x-ai/grok-4-fast                     |
| Gemini 2.5 Pro   | google/gemini-2.5-pro                |
| Gemini 2.5 Flash | google/gemini-2.5-flash              |
| Kimi K2          | moonshotai/kimi-k2-0905              |
| GLM 4.6          | z-ai/glm-4.6                         |
| DeepSeek V3.1    | deepseek/deepseek-v3.1-terminus      |
| Qwen3 Coder      | qwen/qwen3-coder-480b-a35b-07-25     |