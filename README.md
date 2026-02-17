
# Meghana Gorripati — Publications & Research Systems Work

Graduate Researcher | Cloud Systems | Explainable AI | Distributed Systems Engineering  

My research focuses on building stable, scalable, and interpretable ML systems for large-scale cloud environments. The work below emphasizes system robustness, pipeline design, and production-oriented experimentation.

---

## 📚 Publications Overview

| Title | Venue | Status | Research Focus | Links |
|-------|-------|--------|---------------|-------|
| Optimizing ML-Based Cloud-Native Autoscaling Models with XAI-Driven Variable Selection | IEEE ICC 2026 | Accepted | SHAP-based feature selection for stable cloud autoscaling | PDF (coming soon) |
| Trust Enforced Computational Offloading for Health Care Applications in Fog Computing | Wireless Personal Communications (WPC) | Published | Trust-aware fog offloading for healthcare workloads | https://doi.org/10.1007/s11277-021-08285-7 |

---


# 1️⃣ Optimizing ML-Based Cloud-Native Autoscaling Models with XAI-Driven Variable Selection  
**Accepted — IEEE ICC 2026**

## Problem

ML-based autoscaling systems often degrade in production due to:

- Noisy workload spikes  
- Feature instability across time windows  
- Poor interpretability of scaling decisions  
- Sensitivity to transient system behavior  

This leads to unpredictable scaling and inefficient resource allocation in cloud-native systems.

---

## System-Oriented Contribution

I designed a **SHAP-driven feature stability pipeline** to improve robustness of autoscaling prediction models.

### Key Engineering Components

- Feature stability scoring across sliding windows
- SHAP-based importance aggregation
- Filtering of transient or spike-driven inputs
- Comparative evaluation against baseline feature sets
- End-to-end evaluation using large-scale cloud trace data

---

## Why This Matters 

This work directly aligns with:

- Production stability under burst workloads  
- Noise-resistant signal extraction  
- Reliable resource prediction under scale  
- System observability through explainability  

The framework reduces sensitivity to transient signals and prioritizes stable predictors — improving predictability in scaling behavior.

In large-scale networks and datacenter environments, stability > raw accuracy.  
This work focuses explicitly on that tradeoff.

---

From a software engineering perspective, this project required:

- Designing a repeatable feature selection pipeline
- Building modular evaluation workflows
- Implementing systematic experimentation across model configurations
- Comparing performance metrics across controlled ablations
- Measuring tradeoffs between interpretability and predictive performance

The emphasis was on structured experimentation, not just model training.

---

## Technical Themes

- Algorithmic feature selection  
- Stability-aware ML design  
- Experimental evaluation frameworks  
- Large-scale dataset handling  
- Model robustness analysis  

---

# 2️⃣ Trust Enforced Computational Offloading for Health Care Applications in Fog Computing  
**Published — Wireless Personal Communications (Springer)**  
DOI: https://doi.org/10.1007/s11277-021-08285-7  

---

## Problem

In fog computing, task offloading decisions often ignore trust characteristics of nodes, leading to:

- Security risks  
- Reliability degradation  
- Increased latency under malicious or unstable nodes  

---

## Engineering Contribution

We designed a trust-aware offloading framework that:

- Models node trust dynamically  
- Integrates trust metrics into task scheduling decisions  
- Evaluates performance against traditional latency-only approaches  
- Improves reliability in healthcare-sensitive environments  

---

## Systems Relevance

This work emphasizes:

- Distributed decision systems  
- Reliability-aware orchestration  
- Multi-parameter scheduling logic  
- Secure resource allocation  

The design parallels real-world distributed infrastructure where reliability signals must inform orchestration decisions.

---

# Core Research Themes

Across both works:

- Stability over raw performance  
- Signal filtering in distributed systems  
- Algorithmic decision-making under uncertainty  
- Production-oriented ML evaluation  
- Observability and interpretability in large-scale systems  

