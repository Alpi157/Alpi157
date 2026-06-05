# Hi, I'm Alpar Arman 👋

### AI & Security Engineer — I build production-minded AI systems and the security around them.

MEng graduate (University of Victoria, *Telecommunications & Information Security*) and Cybersecurity BSc. I ship two kinds of things: **AI/ML systems** (agent memory infrastructure, LLM apps, applied ML) and **security engineering** (detection, identity, AppSec, DFIR) — and I care most about where they meet: making AI agents **safe, observable, and trustworthy**.

<p>
  <a href="https://www.linkedin.com/in/alpar-arman/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white&style=flat-square" alt="LinkedIn"></a>
  <a href="mailto:armanalpar157@gmail.com"><img src="https://img.shields.io/badge/Email-armanalpar157@gmail.com-EA4335?logo=gmail&logoColor=white&style=flat-square" alt="Email"></a>
  <a href="https://www.researchgate.net/publication/383163802"><img src="https://img.shields.io/badge/Publication-ResearchGate-00CCBB?logo=researchgate&logoColor=white&style=flat-square" alt="ResearchGate"></a>
  <img src="https://img.shields.io/badge/Open%20to-AI%20%26%20Security%20roles%20(Canada%20%2F%20Remote)-2EA44F?style=flat-square" alt="Open to work">
</p>

---

## 🚀 Currently building

- **🧠 [memory-service](https://github.com/Alpi157/memory-service)** — *just shipped.* A memory layer for AI agents: ingests conversation turns, extracts typed & time-stamped beliefs, resolves contradictions deterministically at write time, and packs a token-budgeted context block for the next turn. Python 3.12 · FastAPI · PostgreSQL 16 (pgvector HNSW + FTS + a claim graph in one transactional plane). **100% on its recall eval, 43 passing tests.**
- **🔒 Provable Safety for LLM Agents over MCP** — *in progress, public soon.* A non-bypassable **reference-monitor** for LLM agents acting over the Model Context Protocol: OPA/Rego policy enforcement at the tool boundary, provenance labeling, capability checks, an **Alloy** model for formal safety properties, and evaluation against prompt injection with **AgentDojo**. Enforces safety at the tool boundary instead of trusting the model to self-police.

---

## ⭐ Start here (recruiter quick-eval)

The fastest way to see how I build, across both tracks:

| Project | What it demonstrates |
|---|---|
| 🧠 [memory-service](https://github.com/Alpi157/memory-service) | Production-grade **AI infrastructure** — bi-temporal memory store, RRF hybrid retrieval, intent routing, multi-hop over a Postgres claim graph (no Neo4j), graceful degradation with zero API keys. |
| 💳 [ForteShield AI](https://github.com/Alpi157/ForteShieldAI) | End-to-end **applied ML** anti-fraud platform — multi-model ensemble, real-time scoring, SHAP explanations, an LLM analyst assistant, and a champion/challenger governance loop with shadow mode and retraining. |
| 🛡️ [Identity Threat Detection & Response](https://github.com/Alpi157/sentinel-entra-identity-detection-response) | **SOC / detection engineering** — 7 KQL detections mapped to MITRE ATT&CK, SOAR-safe ticketing, human-in-the-loop triage. Offline-first, so you can run the whole pipeline locally **with no Azure subscription**. |
| 🎣 [PhishGuard](https://github.com/Alpi157/phishguard_extension) | **AI security in practice** — browser extension + local server doing on-device phishing classification (fine-tuned ONNX model), privacy-aware GPT explanations, HTML/JS analysis, and SOC-style incident logging. |

---

## 🧰 Tech stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white&style=flat-square)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white&style=flat-square)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white&style=flat-square)
![KQL](https://img.shields.io/badge/KQL-0078D4?logo=microsoftazure&logoColor=white&style=flat-square)

**AI / ML**
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?logo=openai&logoColor=white&style=flat-square)
![Anthropic](https://img.shields.io/badge/Anthropic-D97757?logo=anthropic&logoColor=white&style=flat-square)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?logo=huggingface&logoColor=black&style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white&style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white&style=flat-square)
![ONNX](https://img.shields.io/badge/ONNX-005CED?logo=onnx&logoColor=white&style=flat-square)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white&style=flat-square)

> RAG · embeddings · vector search · agentic workflows · MCP · prompt engineering · structured outputs · guardrails · LLM evaluation · CatBoost · SHAP

**Backend & Data**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white&style=flat-square)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white&style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white&style=flat-square)

**Security & Cloud**
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?logo=microsoft&logoColor=white&style=flat-square)
![Splunk](https://img.shields.io/badge/Splunk-000000?logo=splunk&logoColor=white&style=flat-square)
![Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-0067B8?logo=microsoftazure&logoColor=white&style=flat-square)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white&style=flat-square)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black&style=flat-square)

> SIEM & detection (Sentinel/KQL, Splunk/SPL, Sysmon) · DFIR (Autopsy, FTK Imager) · IAM & Zero Trust (Entra ID, MFA, RBAC, JML) · NGFW & IDS (Palo Alto, Snort) · applied crypto (ECDH, HKDF, AES-GCM) · MITRE ATT&CK · OPA/Rego

---

## 🤖 AI / ML projects

| Project | Summary |
|---|---|
| 🧠 [memory-service](https://github.com/Alpi157/memory-service) | Agent memory layer: typed/time-stamped beliefs, write-time contradiction resolution, hybrid retrieval (dense + FTS + claim graph), token-budgeted context assembly. FastAPI + Postgres 16. |
| 💳 [ForteShield AI](https://github.com/Alpi157/ForteShieldAI) | Multi-layer anti-fraud platform — model ensemble, real-time velocity features, SHAP, LLM SAR-draft assistant, model registry, champion/challenger + shadow mode. |
| 🎣 [PhishGuard](https://github.com/Alpi157/phishguard_extension) | Hybrid anti-phishing extension with on-device ONNX (RuBERT) classification, GPT explanations, and SOC dashboard. Multilingual (EN/RU/KZ), privacy-aware, on-prem deployable. |
| 🕸️ [ML-Enhanced Security in P2P Overlays](https://github.com/Alpi157/security-for-kademlia-P2P) | Kademlia overlay simulator with DDoS/Sybil/Eclipse/poisoning attacks, Random Forest detection, and **reinforcement-learning** adaptive mitigation + live dashboard. |
| 📡 [DDoS Detection System](https://github.com/Alpi157/ddos_detection_system) | ML-based DDoS detection with Markov-chain mitigation modeling. |
| 📊 [Phishing Dataset Analysis](https://github.com/Alpi157/phishing_dataset_analysis) | Exploratory analysis of phishing emails to surface behavioral indicators. |
| 🧬 [Evolving Plasticity Sim](https://github.com/Alpi157/evolving-plasticity-sim) | Neuroevolution research: how within-lifetime learning co-evolves with genetic behavior in non-stationary environments (Baldwin effect). PyTorch. |

---

## 🛡️ Security projects

| Project | Summary |
|---|---|
| 🛡️ [Identity Threat Detection & Response](https://github.com/Alpi157/sentinel-entra-identity-detection-response) | Offline-first Sentinel + Entra ID lab — 7 KQL detections, investigation workbook, SOAR-safe playbooks, MITRE mapping, human-in-the-loop AI triage. |
| 🔎 [SOC Threat Detection (Splunk)](https://github.com/Alpi157/soc-threat-detection-repo) | Mini-SOC homelab — Sysmon + Apache ingest, simulated attacks, SPL detections, dashboards, alerts, and an IR playbook. |
| 💬 [SecureText Security Lab](https://github.com/Alpi157/securetext-security-lab) | Hardens an insecure messenger end to end: bcrypt, HMAC, TOTP MFA, OAuth, RBAC/Zero Trust, and E2EE (ECDH + HKDF + AES-GCM). |
| 🧨 [Network Pentest & Defense](https://github.com/Alpi157/network-pentest-defence) | Full red-then-blue assessment: recon → exploitation (incl. Samba RCE) → Snort IDS detection → firewall prevention + hardening. |
| 🧱 [Palo Alto NGFW Lab](https://github.com/Alpi157/paloalto-ngfw-lab) | Segmented Zero Trust topology with App-ID, TLS inspection, URL filtering, AV, and IPS — validated against an MS17-010 simulation. |
| 🔬 [DFIR: Blackmail Investigation](https://github.com/Alpi157/dfir-artifact-recovery-lab) | End-to-end forensics on Windows + Android images: hash validation, masquerading detection, timeline analysis, carving, cross-device correlation. |
| 🆔 [Azure Entra ID Security Lab](https://github.com/Alpi157/azure-security-lab) | Enterprise IAM simulation — users/groups/RBAC, MFA, Conditional Access design, administrative units, hybrid identity, incident playbooks. |
| 🧠 [Forensic Memory Analysis](https://github.com/Alpi157/forensic-memory-analysis) | Memory forensics of a compromised Windows machine. |

> All offensive work is performed in **authorized, isolated lab environments** and shared for educational purposes.

---

## 💼 Experience

- **IT Administrator (Co-op), Carbon Engineering — Squamish, BC** *(Sep 2025 – Apr 2026)*
  Identity & access operations in **Entra ID / M365** (onboarding, offboarding, JML, MFA, account recovery), access-request documentation and SOPs, and testing/troubleshooting a **Copilot service-desk chatbot** plus SharePoint knowledge-retrieval workflows.
- **AI Solutions Developer — Freelance** *(2023 – 2024)*
  Designed and deployed multilingual (EN/RU/KZ) LLM chatbots for client organizations across web, Telegram, and WhatsApp — requirements through deployment, with safety constraints and handover docs.
- **Researcher (NLP / ML), Astana IT University** *(2023)*
  Built an NLP admissions Q&A system; owned the evaluation loop (95.3% accuracy / 94.4% precision); published the work.

---

## 🎓 Education

- **MEng, Telecommunications & Information Security** — University of Victoria, BC *(2024 – 2026)*
- **BSc, Cybersecurity** — Astana IT University, Kazakhstan *(2021 – 2024)*

## 📜 Certifications

**ISC2 Certified in Cybersecurity (CC)** · **Microsoft Applied Skills: Secure AI Solutions in the Cloud** (Defender for Cloud, Azure AI Foundry) · Cisco CyberOps Associate · Cisco Network Security · Cisco CCNAv7 (SRWE)

## 📄 Publication

*Systemic approach to optimizing natural language processing technologies in Astana IT University's admissions process* (2024) — [ResearchGate](https://www.researchgate.net/publication/383163802_Systemic_approach_to_optimizing_natural_language_processing_technologies_in_Astana_IT_University%27s_admissions_process)

---

## 📫 Get in touch

🌐 Languages: English · Kazakh · Russian · Chinese  
📧 **armanalpar157@gmail.com** · 💼 [LinkedIn](https://www.linkedin.com/in/alpar-arman/)
