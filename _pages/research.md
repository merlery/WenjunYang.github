---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

## Doctoral Research: User-Centric Local Differential Privacy

**September 2022 – Present** | University of Washington  
Advisor: Dr. Eyhab Al-Masri · In collaboration with Oak Ridge National Laboratory (Dr. Olivera Kotevska)

### LLM Agents for Secure Differential Privacy Configuration
*With Dr. Tianhao Wang (University of Virginia) and Dr. Eyhab Al-Masri · Manuscript in preparation, targeting IEEE S&P 2027*

- Designed a two-layer verifier (deterministic code checks plus an LLM checklist isolated from user input) that cut policy-violating privacy configurations on adversarial-pressure episodes from 4.6% to 0% across 9 frontier LLMs.
- Built **DPConfig-Bench**, a red-teaming benchmark for LLM agents configuring differential privacy: 52 scenarios, including 12 adversarial-pressure scenarios spanning 6 manipulation tactics (authority, urgency, policy doubt, precedent, emotional, reframing). Correct answers (minimal ε) are computed analytically and validated by Monte Carlo simulation.
- Deploying the agent as a ChatGPT plugin that gives users verified privacy-budget (ε) recommendations; public release in progress.
- First-author poster at USENIX Security 2026.

### LDP-MIC: Federated Learning without a Trusted Aggregator
*Under review at IEEE Transactions on Information Forensics and Security*

- Clients apply correlation-adaptive local differential privacy before sharing federated-learning updates. LDP-MIC matched DP-SGD-level protection against gradient leakage attacks while keeping 5–8% higher accuracy, cutting reconstruction SSIM from 0.92 to 0.16 (an 83% reduction). Experiments used Opacus on ORNL's Frontier exascale supercomputer.
- Engineered a batched federated-learning simulator in PyTorch that executed 15.5K FL training runs (1.55M federated rounds) in about 4.5 hours on a 2-core CPU, validated against a NumPy reference with 37 unit tests, with pre-registered hypotheses and Holm-corrected paired tests.

### MIC-DP: Correlation-Aware Differential Privacy
*IEEE Transactions on Privacy, 2025*

- Allocates the per-feature privacy budget by maximal information coefficient (MIC) scores, outperforming uniform-noise differential privacy: in a 30-trial follow-up evaluation, ROC-AUC on the Adult dataset rose from 0.799 to 0.820 at ε = 5 and from 0.801 to 0.823 at ε = 10.
- Follow-up work derived a bounded-sensitivity fixed-grid MIC estimator that reduces the noise needed to privately release correlation scores 650-fold.
- Open-source Python package: `pip install mic-dp` ([PyPI](https://pypi.org/project/mic-dp/)). Poster at USENIX Security 2025.

### Participatory AI and Conversational Agents for Privacy Decisions
*ACM CHI 2025 Workshop*

- Proposed a participatory, human-centered AI framework that lets citizens shape differential privacy settings for public-sector AI through conversation.
- Designed **PrivAgent** (dissertation chapter), a conversational LLM agent grounded in bounded rationality that elicits users' privacy preferences.
- Designed and deployed an IRB-exempt online user study (N = 200 participants on Prolific); results are reported in the dissertation.

### ULDP: User-Centric Privacy-Budget Optimization
*IEEE AIIoT 2024*

- Automated privacy-budget (ε) selection for local differential privacy in edge computing with a TOPSIS-based multi-criteria optimization method that balances privacy, accuracy, and compute cost.

---

## Research Collaboration with Microsoft: MigrationRouter

**September 2021 – June 2022** | Ph.D. research project with Dr. Minjia Zhang (Microsoft)

- Built MigrationRouter, a reinforcement learning (Q-learning) agent that routes compute tasks across edge base stations, with an MDP formulation and a reward that trades off computational cost (CPU cycles) against migration cost (distance).
- Trained on Microsoft's Philly GPU-cluster traces: cleaned 117K DNN-training jobs to 102,666, joined them with real base-station locations, and processed the data in Google BigQuery.
- Reached 88% route accuracy (91% best-of-5) on 100-node networks and 99% route availability at 250+ nodes; built a web interface that maps the routes.

---

## Earlier Projects

### StreetSmarter: IoT Smart Parking System
**2019** | Team lead (team of 4) · First Prize, University of Washington Hackathon (judged by the Microsoft Azure team)

- An end-to-end IoT system that routes drivers to open parking spots: Raspberry Pi sensors, a Python (Flask) and SQLite back end, and IBM Watson cloud.
- Owned the system architecture, split the work across hardware, back-end, and cloud tracks, and led the final pitch.

---

Interested in collaborating? Please [get in touch]({{ "/contact/" | relative_url }}).
