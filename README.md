# A-CSM

**AI Contextual Safety Matrix**

[![ORCID](https://img.shields.io/badge/ORCID-0009--0002--6597--7245-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0002-6597-7245)
[![IEEE](https://img.shields.io/badge/IEEE-Member_No.102124292-00629B?style=for-the-badge&logo=ieee&logoColor=white)](https://www.ieee.org)
[![APA](https://img.shields.io/badge/APA-Member_2026-2A5CAA?style=for-the-badge)](https://www.apa.org)
[![License](https://img.shields.io/badge/License-Apache_2.0-orange?style=for-the-badge)](LICENSE)

---

An 8-stage pipeline for evaluating safety risks in human-AI conversational interaction, developed by [Valyrx Labs](https://github.com/valyrx-labs).

## Overview

A-CSM is a verifiable, context-aware risk evaluation framework designed to assess safety risks that emerge during human-AI interaction. Unlike output-focused safety tools, A-CSM evaluates **user-side contextual dynamics** — how conversational context shifts, how users interpret AI responses, and where hidden risks arise from context misalignment.

The framework integrates three theoretical layers:

- **CXC-7** — The Seven Core Dimensions of Conversational Context, modeling how context is structured and maintained across dialogue turns
- **CXOD-7 + Coh(G)** — A Contextual Offense and Defense Evaluation Framework with a coherence metric for quantifying contextual alignment in AI safety
- **USCI** — User-Side Contextual Interaction Assessment, a methodology specification for post-interaction contextual risk evaluation

## Published Research

| # | Paper | DOI | Source | Year |
|---|-------|-----|--------|------|
| 1 | User-Side Contextual Hallucination in Human-AI Interaction: A Framework Built Upon the CXC-7 and CXOD-7 Conversational Context Models | [![DOI](https://img.shields.io/badge/DOI-10.2139%2Fssrn.6135732-blue?style=flat-square)](https://doi.org/10.2139/ssrn.6135732) | SSRN | 2026 |
| 2 | User-Side Contextual Interaction Assessment (USCI): A Methodology Specification for Post-Interaction Contextual Risk Assessment in Human-AI Interaction | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.18678458-blue?style=flat-square)](https://doi.org/10.5281/zenodo.18678458) | Zenodo | 2026 |
| 3 | The Seven Core Dimensions of Conversational Context (CXC-7): A Framework Proposal for AI and Large Language Models | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17247637-blue?style=flat-square)](https://doi.org/10.5281/zenodo.17247637) | Zenodo | 2025 |
| 4 | CXOD-7 and Coh(G): A Contextual Offense and Defense Evaluation Framework for AI Safety | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17136790-blue?style=flat-square)](https://doi.org/10.5281/zenodo.17136790) | Zenodo | 2025 |

## Architecture

```
Input Conversation
│
▼
┌─────────────────────────────────────────────┐
│ A-CSM Orchestrator │
│ │
│ Stage 1 → Context Extraction (CXC-7) │
│ Stage 2 → Dimensional Analysis │
│ Stage 3 → Coherence Scoring (Coh(G)) │
│ Stage 4 → Offense/Defense Mapping (CXOD-7) │
│ Stage 5 → User-State Modeling │
│ Stage 6 → Semantic Anchor Detection │
│ Stage 7 → Risk Signal Aggregation │
│ Stage 8 → USCI Assessment Output │
│ │
└─────────────────────────────────────────────┘
│
▼
Risk Evaluation Report
```

## Getting Started
```bash

git clone https://github.com/valyrx-labs/a-csm.git
cd a-csm
```
Full documentation and usage instructions coming soon.


## Author

**ZON RZVN**
Founder, [Valyrx Labs](https://github.com/valyrx-labs)  
Independent AI Safety Researcher

- ORCID: [0009-0002-6597-7245](https://orcid.org/0009-0002-6597-7245)
- IEEE Member (No. 102124292)
- APA Member 2026 (No. C2505666474)

## License

This project is licensed under the [Apache License 2.0](LICENSE).

```text
Copyright 2026 Valyrx Labs (ZON RZVN)
```
