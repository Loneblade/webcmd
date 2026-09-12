# 🏥 AarogyaRoute: Autonomous Medical Logistics Agent
> **A Deterministic Browser Agent Daemon built on the Webcmd Architecture**  
> *Autonomous Specialist Discovery • Proximity Post-Op Lodging • Multi-Modal Transit Coordination • Mandatory HITL Governance*

[![Runtime](https://img.shields.io/badge/Runtime-Node.js%20v18%2B-339933?logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Automation](https://img.shields.io/badge/Automation-Playwright%20Chromium-45ba4b?logo=playwright&logoColor=white)](https://playwright.dev/)
[![Telemetry](https://img.shields.io/badge/Telemetry-Server--Sent%20Events%20(SSE)-orange)](#)
[![Compliance](https://img.shields.io/badge/Governance-Mandatory%20HITL%20Enforced-critical)](#)
[![Origin Hub](https://img.shields.io/badge/Origin%20Hub-Bhopal%20(BPL%2FBHO%2FRKMP)-purple)](#)

---

## 📌 Executive Summary

Every year, millions of patients from Tier-2 and Tier-3 hubs in India travel inter-state for tertiary and quaternary healthcare. Coordinating accredited specialists, post-operative wheelchair-accessible lodging, and transit schedules (flights and medical quota trains) takes **4 to 6 hours of fragmented, high-friction manual tab switching**.

Generic chatbots hallucinate medical availability and consultation pricing. Multimodal vision-based agents burn upwards of **90,000 tokens per workflow on raw screenshot scraping**, resulting in fragile execution and high latency.

**AarogyaRoute** is an autonomous browser agent daemon designed to solve medical travel logistics. It executes deterministic accessibility tree navigation, live DOM manipulation, and dynamic budget calculations, while strictly adhering to **Mandatory Human-in-the-Loop (HITL) Authorization** before executing ticket dispatch or compiling official clinical dossiers.

---

## 🏗️ System Architecture

AarogyaRoute implements an agentic daemon pattern over the core **Webcmd execution specification**:

```text
[ Natural Language Clinical Query ]
                │
                ▼
┌────────────────────────────────────────────────────────┐
│  AarogyaRoute ReAct Orchestration Engine               │
│  • Plan: Synthesizes procedure, budget cap & hub       │
│  • Thought: Selects DOM traversal strategies           │
└───────────────────────┬────────────────────────────────┘
                        │
                        ▼
┌────────────────────────────────────────────────────────┐
│  Playwright Visual Headed Chromium Worker              │
│  • Anti-Bot Fingerprint Masking                        │
│  • Human Keystroke Emulation (40ms typing slowMo)      │
│  • Visual Agent Bounding Box Injection                 │
│  • Accessibility Tree Traversal (Zero Vision Tokens)   │
└───────────────────────┬────────────────────────────────┘
                        │
                        ▼
┌────────────────────────────────────────────────────────┐
│  Hybrid Resilient Cache & Route Resolver               │
│  • Specialist Portals (Practo / Google)                │
│  • Proximity Lodgings (≤ 2km from clinical facility)   │
│  • Transit Matrix Originating from Bhopal Hub          │
└───────────────────────┬────────────────────────────────┘
                        │
                        ▼
┌────────────────────────────────────────────────────────┐
│  ⚠️ MANDATORY HUMAN-IN-THE-LOOP CHECKPOINT              │
│  • Autonomous execution freezes cold                   │
│  • Operator customizes Surgeon, Stay & Transit         │
│  • Real-time package recomputation                     │
└───────────────────────┬────────────────────────────────┘
                        │ [Operator Confirms Dispatch]
                        ▼
┌────────────────────────────────────────────────────────┐
│  Artifact Generation & Audit Trail                     │
│  • Timestamped PDF Medical Travel Dossier              │
│  • Full-page DOM Proof Screenshot (receipt.png)        │
└────────────────────────────────────────────────────────┘
