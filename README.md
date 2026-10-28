# Alpar Arman

I build AI tools for security operations, and the guardrails that stop attackers from steering them.

I'm an AI engineer at DQ, a managed security provider in Astana, where I work on AI-assisted alert investigation for the SOC. Both my degrees are in information security: an MEng in Telecommunications and Information Security from the University of Victoria and a BSc in Cybersecurity from Astana IT University. Before DQ I did an IT admin co-op at Carbon Engineering in Squamish, BC.

I'm looking for AI engineering and security roles in Canada, and I hold an open work permit (PGWP), so no sponsorship is needed.

armanalpar157@gmail.com · [LinkedIn](https://www.linkedin.com/in/alpar-arman/)

## Start here

### [Catch the Fly](https://github.com/Alpi157/internet-vs-one-fly) · [play it in your browser](https://alpi157.github.io/internet-vs-one-fly/)

A fruit fly brain simulated from its measured wiring. Try to swat the fly. There is no escape script, so whether it gets away depends on how spikes travel through the network. Afterwards you can replay the spikes and look inside its head.

Behind the game is a small research project. I preregistered the comparisons, published the raw records on Zenodo with a DOI, and checked that the Python, Numba and TypeScript versions of the model give bit-identical results, including in three browser engines. One of my own preregistered controls overturned part of my headline result, and the README reports it.

### [memory-service](https://github.com/Alpi157/memory-service)

A memory layer for AI agents. It turns conversation turns into typed, time-stamped beliefs, settles contradictions when they are written rather than when they are read, and packs a token-budgeted context block for the agent's next turn. FastAPI and Postgres with pgvector, 44 tests, and `docker compose up` brings it up with or without API keys.

### [Identity threat detection lab](https://github.com/Alpi157/sentinel-entra-identity-detection-response)

Seven KQL detections for Entra ID attacks, from a run of failed sign-ins ending in a success to OAuth consent grants and MFA method changes, mapped to MITRE ATT&CK. An offline harness runs the whole detect, investigate and ticket loop, so you can try it without an Azure subscription.

## Security labs

- [SecureText](https://github.com/Alpi157/securetext-security-lab): an insecure Python messenger hardened in three stages, ending with MFA and end-to-end encryption (ECDH, HKDF, AES-GCM)
- [SOC lab in Splunk](https://github.com/Alpi157/soc-threat-detection-repo): Sysmon and Apache logs, simulated brute-force and web enumeration, SPL detections, dashboards and an incident response playbook
- [Palo Alto NGFW](https://github.com/Alpi157/paloalto-ngfw-lab): segmented zones, App-ID, TLS inspection and URL filtering, with IPS tested against an MS17-010 exploit
- [Network pentest and defense](https://github.com/Alpi157/network-pentest-defence): recon and exploitation, including a Samba RCE, then Snort detection and firewall hardening
- [DFIR case](https://github.com/Alpi157/dfir-artifact-recovery-lab): a blackmail investigation across a Windows image and an Android image
- [Memory forensics](https://github.com/Alpi157/forensic-memory-analysis): Volatility analysis of a compromised Windows machine
- [Entra ID security lab](https://github.com/Alpi157/azure-security-lab): RBAC, MFA, Conditional Access design and incident playbooks on a free-tier tenant

## AI and ML

- [PhishGuard](https://github.com/Alpi157/phishguard_extension): a browser extension that flags phishing pages with an ONNX model running on the user's device
- [Two-stage IoT intrusion detection](https://github.com/Alpi157/ECE572_FinalProject): an Isolation Forest gate followed by a LightGBM classifier on the CIC IoT-DIAD 2024 dataset
- [ForteShield](https://github.com/Alpi157/ForteShieldAI): a hackathon anti-fraud pipeline with a model ensemble, real-time scoring and SHAP explanations
- [P2P overlay security](https://github.com/Alpi157/security-for-kademlia-P2P): a Kademlia network simulator with attack detection and reinforcement-learning mitigation

**Paper**: [Systemic approach to optimizing natural language processing technologies in Astana IT University's admissions process](https://www.researchgate.net/publication/383163802_Systemic_approach_to_optimizing_natural_language_processing_technologies_in_Astana_IT_University%27s_admissions_process), IEEE SIST 2024.

I work mostly in Python, plus SQL, KQL and SPL. I speak English, Kazakh, Russian and Chinese.
