# AI-IDRS: AI-Driven Intrusion Detection & Response System

> **Showcase repository.** This repo documents the project (architecture, design decisions, results). The source code is private; walkthroughs and code review are available on request.

**Context:** BSc (Hons) Cyber Security final-year project and extended build (2025 to 2026)

## What it is
A hybrid detection and response platform that fuses several signals into a single confidence score.

## Detection pipeline
- Zeek and Suricata network telemetry
- Threat intelligence (53,000+ indicators)
- Isolation Forest anomaly detection
- XGBoost multi-class attack classification
- Signature rules
- RabbitMQ / Logstash / Filebeat ingestion

## Explainable, human-in-the-loop
- Per-alert explanations and feature importance (SHAP)
- Active learning: analyst true-positive / false-positive feedback triggers retraining
- SOAR engine with 9 response policies, in simulation or active mode

## Tech stack
Python · Flask / Bootstrap dashboard · Docker · automated test suites

## Links
Portfolio: https://mashkur.denimography.co.uk · LinkedIn: https://linkedin.com/in/mashkur-alam-76330252
