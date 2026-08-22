# ASA-AI: VoIP Threat Sentinel & Fraud-Block

Empowering SOC Teams with Real-Time SIP Threat Detection, Risk Scoring, and Automated Fraud Enforcement.**

Overview
**ASA-AI (VoIP Threat Sentinel & Fraud-Block)** is an enterprise-grade security orchestration and telemetry platform built to assist **SOC (Security Operations Center)** analysts in monitoring critical voice infrastructures.

---
## 🎬 Platform Demo in Action
Watch the full demonstration of the real-time detection and Fraud-Block engine in action:

[![Watch the video demo on YouTube](https://img.youtube.com/vi/za9NfKaPgqw/0.jpg)](https://www.youtube.com/watch?v=za9NfKaPgqw)
---

Telephony environments face relentless automated threats such as toll fraud, PBX exploitation, registration brute-forcing, and malicious SIP scanning. ASA-AI bridges the gap between telecom layers and SOC operations by delivering instant attack detection, dynamic risk evaluation, and automated mitigation loops.

## 🔍 Core Capabilities for SOC Teams
Real-Time Attack Detection:** Instantly identifies malicious SIP patterns, unauthorized INVITE floods, suspicious REGISTER attempts, and automated scanning tools.
Dynamic Risk Scoring:** Continuously evaluates real-time telemetry to assign precise risk percentages, flagging anomalous user-agents, international traffic spikes, and protocol mismatches.
Automated Fraud-Block & Enforcement:** Empowers security teams with flexible enforcement modes—ranging from dry-run simulations (Shadow Block) to active interception loops (ALLOW, BLOCK, REVIEW).
Unified Observability:** Provides high-visibility Grafana dashboards tailored for security operators to instantly correlate voice events with system performance.

SOC Workflow: How It Works
1.Ingestion & Parsing:** Captures real-time SIP traffic and Homer/Hepify telemetry streams from enterprise telephony infrastructure.
2. Analysis & Intelligence:** The machine learning and analytics engine inspects traffic behaviors, calculates ongoing risk levels, and correlates anomalies.
3. Decision & Mitigation:** The Fraud-Block engine classifies events and triggers defensive actions to secure the communications grid without disrupting legitimate callers.

🏗️ Technical Stack
Telemetry & Capture:** Asterisk, Homer, Hepify, Node Exporter
Analytics & AI:** Custom ML pipeline for anomaly scoring and risk assessment
Visualization:** Prometheus & Grafana operational dashboards
Enforcement:** Automated decision engine (ALLOW / BLOCK / REVIEW)

Getting Started
1. Clone the repository:**
   ```bash
   git clone [https://github.com/khemegha/ASA-AI-VoIP-Threat-Sentinel.git](https://github.com/khemegha/ASA-AI-VoIP-Threat-Sentinel.git)