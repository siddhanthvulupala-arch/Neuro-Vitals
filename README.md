# Neuro Vitals — Orbital Biomedical & BCI Command Console

**NASA Space Apps Challenge 2026** | *Create Health Monitoring Software for Astronauts on Space Missions*  
**Team:** Neuro Vitals (Hyderabad, India)

---

## Overview
During long-duration deep-space missions to the Moon and Mars, communication delays with Earth (up to 14–22 minutes one-way) prevent real-time flight-surgeon intervention. Astronauts must self-monitor complex physiological risks—including Spaceflight Associated Neuro-ocular Syndrome (SANS), hypercapnia, solar particle radiation, bone mineral density loss, and cognitive fatigue—while operating under extreme workload.

**Neuro Vitals** is an autonomous, flight-grade biomedical telemetry and non-invasive Brain-Computer Interface (BCI) clinical decision-support console designed to help crews detect anomalies early, execute hands-free life-support countermeasures, and maintain peak mission readiness.

---

## Key Features
* **6-Node Anatomical Diagnostic Scanner:** Interactive biometric silhouette covering **BCI / fNIRS Cortex**, **SANS / Ocular**, **Pulmonary ($pCO_2$ / $SpO_2$)**, **Cardiovascular**, **Radiation Dosimetry**, and **Femoral BMD**, complete with pathophysiology notes, `NASA-STD-3001` permissible exposure limits, and step-by-step astronaut self-exam checklists.
* **Real-Time 3-Channel Clinical Oscilloscope:** Live 60fps telemetry rendering **Lead II ECG**, **Prefrontal BCI ($Fp1\text{–}Fp2$ µV)**, and **Sidestream Capnography ($ETCO_2$)** alongside Theta/Alpha/Beta/rSO₂ spectral readouts and trace-freeze caliper inspection.
* **Autonomous Triage & Hands-Free BCI Command Decoder:** Evaluates multi-sensor telemetry locally onboard to recommend countermeasures and trigger life-support actions (e.g., EVA Suit $O_2$ LiOH Purge, Storm Shelter Ingress) via motor-imagery BCI intent—even if an astronaut is incapacitated.
* **Multi-Scenario Mission Simulator:** Built-in clinical test profiles (*Nominal Orbital Transit*, *EVA $CO_2$ Washout & Hypoxia*, *G4 Solar Particle Storm*, and *SANS Grade II & Circadian Desynchrony*) to validate alert thresholds and autonomous recovery.
* **Daily Countermeasure Readiness Tracker:** Gamified protocol tracking for ARED resistive loading, ocular OCT self-scans, circadian lighting, and cognitive baseline drills.

---

## NASA Data & Clinical Standards Alignment
* **NASA-STD-3001 (Volume 1 & 2):** Spaceflight Human-System Standard thresholds for cabin/suit $pCO_2$, acute radiation exposure limits, and cardiovascular deconditioning.
* **NASA Open Science Data Repository (OSDR) & Inspiration4 Biomedical Benchmarks:** Physiological response modeling for microgravity fluid shifts, neuro-ocular pressure changes, and immune/circadian stress markers.
* **NASA Human Research Program (HRP):** Risk mitigation protocols for SANS, behavioral health, and autonomous crew medical operations.

---

## Running Locally
No build step or external dependencies required:
1. Clone or download this repository.
2. Open `index.html` in any modern desktop or tablet browser.
