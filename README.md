# Alpar Arman

I build AI tools for security operations, and the guardrails that stop attackers from steering them.

- **Now:** sole engineer behind an AI triage platform for SIEM alerts at DQ, a managed security provider. The model's claims are checked against the evidence before an analyst sees them.
- **Background:** MEng in Telecommunications and Information Security (University of Victoria), BSc in Cybersecurity, ISC2 CC.
- **Research:** enforcing safety for LLM agents at the tool boundary (MCP), in progress. Co-author of an [IEEE SIST 2024 paper](https://doi.org/10.1109/SIST61555.2024.10629481) on NLP for university admissions.
- **Languages:** English, Kazakh, Russian, Chinese.
- **Looking for:** AI engineering and AI security roles in Canada. Open work permit (PGWP), no sponsorship needed. [Email](mailto:armanalpar157@gmail.com) · [LinkedIn](https://www.linkedin.com/in/alpar-arman/)

**Stack**
- **AI:** Python · Anthropic, OpenAI and Azure OpenAI APIs · Azure AI Foundry · RAG and hybrid retrieval · Pydantic · PyTorch · scikit-learn · Hugging Face · ONNX
- **Security:** IBM QRadar SIEM and SOAR (AQL) · Splunk (SPL) · Entra ID and M365 · MITRE ATT&CK
- **Engineering:** FastAPI · PostgreSQL and pgvector · Docker · GitHub Actions · Linux

## Start here

### [Catch the Fly](https://github.com/Alpi157/internet-vs-one-fly) · [play it](https://alpi157.github.io/internet-vs-one-fly/)

[![A fly escapes a swat, then the replay shows its escape neuron firing inside a brain rebuilt from real wiring](https://raw.githubusercontent.com/Alpi157/internet-vs-one-fly/main/docs/media/game-hero.gif)](https://alpi157.github.io/internet-vs-one-fly/)

A fruit fly brain simulated from its measured wiring. Whether it escapes your swat depends on spikes moving through the network, not on a script. The experiments are preregistered, the raw data is on Zenodo, and the model gives bit-identical results across Python, Numba, TypeScript and three browser engines. One of my own controls overturned part of my headline result, and the README says so.

### [memory-service](https://github.com/Alpi157/memory-service)

Memory for AI agents. It turns conversations into typed, time-stamped beliefs, settles contradictions when they're written, and packs a token-budgeted context for the agent's next turn. FastAPI, Postgres with pgvector, 44 tests.

### [Identity threat detection lab](https://github.com/Alpi157/sentinel-entra-identity-detection-response)

Seven Microsoft Sentinel detections for Entra ID attacks, mapped to MITRE ATT&CK, with an offline harness that runs the whole detect, investigate and ticket loop without an Azure subscription.

<details>
<summary><b>More security work</b> (7 labs)</summary>

- [SecureText](https://github.com/Alpi157/securetext-security-lab): an insecure Python messenger hardened in three stages, ending with MFA and end-to-end encryption
- [SOC lab in Splunk](https://github.com/Alpi157/soc-threat-detection-repo): Sysmon and Apache logs, simulated brute force and web enumeration, SPL detections, dashboards and an incident response playbook
- [Palo Alto NGFW](https://github.com/Alpi157/paloalto-ngfw-lab): segmented zones, App-ID, TLS inspection and URL filtering, with IPS tested against an MS17-010 exploit
- [Network pentest and defense](https://github.com/Alpi157/network-pentest-defence): recon and a Samba RCE, then Snort detection and firewall hardening
- [DFIR case](https://github.com/Alpi157/dfir-artifact-recovery-lab): a blackmail investigation across Windows and Android images
- [Memory forensics](https://github.com/Alpi157/forensic-memory-analysis): Volatility analysis of a compromised Windows machine
- [Entra ID security lab](https://github.com/Alpi157/azure-security-lab): RBAC, MFA, Conditional Access design and incident playbooks on a free-tier tenant

</details>

<details>
<summary><b>More AI and ML</b> (4 projects)</summary>

- [PhishGuard](https://github.com/Alpi157/phishguard_extension): a browser extension that flags phishing pages with an on-device ONNX model
- [Two-stage IoT intrusion detection](https://github.com/Alpi157/ECE572_FinalProject): an Isolation Forest gate and a LightGBM classifier on the CIC IoT-DIAD 2024 dataset
- [ForteShield](https://github.com/Alpi157/ForteShieldAI): a hackathon anti-fraud pipeline with a model ensemble, real-time scoring and SHAP explanations
- [P2P overlay security](https://github.com/Alpi157/security-for-kademlia-P2P): a Kademlia network simulator with attack detection and reinforcement-learning mitigation

</details>
