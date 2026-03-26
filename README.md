# Awesome Cloud Security ⚡

> A curated collection of cloud security tools, learning resources, frameworks,
> certifications, and references — built and maintained by
> [CyberAI Agency](https://github.com/CyberAI-Agency).

[![Maintained](https://img.shields.io/badge/Maintained-yes-green.svg)](https://github.com/CyberAI-Agency/awesome-cloud-sec)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](LICENSE)
[![CyberAI Agency](https://img.shields.io/badge/By-CyberAI_Agency-4D148C?style=flat-square)](https://github.com/CyberAI-Agency)

Maintained by [@nvsaigeetham](https://github.com/nvsaigeetham) · 15+ years enterprise multi-cloud security

---

## Contents

- [CyberAI Agency Tools](#cyberai-agency-tools)
- [OCI Security](#oci-security)
- [AWS Security](#aws-security)
- [Azure Security](#azure-security)
- [GCP Security](#gcp-security)
- [AI Security](#ai-security)
- [Threat Intelligence](#threat-intelligence)
- [Compliance & GRC](#compliance--grc)
- [CTF & Practice Labs](#ctf--practice-labs)
- [Certifications](#certifications)
- [Official Documentation](#official-documentation)
- [Blogs & Research](#blogs--research)
- [Conferences & Communities](#conferences--communities)

---

## CyberAI Agency Tools

> Open-source security tools built by practitioners for practitioners.
> All tools are free, MIT licensed, and built from real enterprise security work.

### Cloud Security & CSPM

| Tool | Description |
|---|---|
| [CloudGoat-OCI](https://github.com/CyberAI-Agency/CloudGoat-OCI) | Vulnerable-by-design OCI environment — 8 CTF scenarios covering IAM privesc, IDCS takeover, IMDS theft, VCN escape, Cloud Guard bypass. **First and only OCI CTF lab.** |
| [CloudSentinel](https://github.com/CyberAI-Agency/CloudSentinel) | Multi-cloud IAM auditor for OCI · AWS · Azure · GCP. Detects non-federated users, MFA gaps, overpermissioned policies, stale credentials. AI remediation included. |
| [CSPMlite](https://github.com/CyberAI-Agency/CSPMlite) | Lightweight CSPM dashboard with React UI, persistent finding history, and AI-powered finding summarizer. |
| [VCN-SecurityAudit](https://github.com/CyberAI-Agency/VCN-SecurityAudit) | OCI VCN security list and NSG auditor across all regions and compartments. Auto-generates Terraform remediation for open rules. |
| [PolicyScorer](https://github.com/CyberAI-Agency/PolicyScorer) | IAM policy risk scoring engine. Detects wildcards, cross-account trust abuse, and privilege escalation paths. AI explanation per finding. |
| [MFAWatch](https://github.com/CyberAI-Agency/MFAWatch) | MFA gap auditor for OCI Classic IAM + IDCS, AWS, and Azure. AI-generated remediation emails and Slack alerting. |
| [TagHunter](https://github.com/CyberAI-Agency/TagHunter) | Cross-cloud resource tag compliance scanner. Supports EAI tag frameworks. Terraform remediation PR generator. |
| [SecBaseline](https://github.com/CyberAI-Agency/SecBaseline) | CIS Level 1 & 2 benchmark auto-checker with delta tracking between scan runs. PDF and Excel output. |
| [CloudInventoryAI](https://github.com/CyberAI-Agency/CloudInventoryAI) | AI-enhanced multi-cloud resource inventory with cost anomaly detection and topology mapping. |
| [CloudDriftDetector](https://github.com/CyberAI-Agency/CloudDriftDetector) | Detects configuration drift between Terraform IaC state and live cloud resources. Alerts on unauthorized manual changes. |
| [OCIAttackGraph](https://github.com/CyberAI-Agency/OCIAttackGraph) | OCI privilege escalation path mapper using Neo4j. Finds shortest path to admin across all IAM policies in a tenancy. |
| [OCI-PAR-Tracker](https://github.com/CyberAI-Agency/OCI-PAR-Tracker) | Privileged Access Review tracker for OCI Classic IAM + IDCS with risk scoring and reviewer workflow. |
| [CloudGuardExporter](https://github.com/CyberAI-Agency/CloudGuardExporter) | OCI Cloud Guard problem exporter with AI-generated executive reports and trend analysis. |
| [OCI Security Checklist](https://github.com/CyberAI-Agency/oci-security-checklist) | Comprehensive OCI security hardening checklist — IAM, VCN, Compute, Storage, Logging, Cloud Guard, Compliance. |

### AI Security Agents

| Agent | Description |
|---|---|
| [CyberOpsOrchestrator](https://github.com/CyberAI-Agency/CyberOpsOrchestrator) | Master AI coordinator that routes security tasks to specialist agents, manages parallel execution, and aggregates findings into unified reports. |
| [CloudGuardianAI](https://github.com/CyberAI-Agency/CloudGuardianAI) | Autonomous 24/7 cloud posture monitoring agent. Detects misconfigs, generates Terraform fixes, alerts via Slack/Teams, creates Jira tickets. |
| [ThreatHunterAI](https://github.com/CyberAI-Agency/ThreatHunterAI) | AI-driven SIEM threat hunting agent. Hunts for IOCs, lateral movement, and anomalies. 100% MITRE ATT&CK mapped. |
| [IAMAnalyzerAI](https://github.com/CyberAI-Agency/IAMAnalyzerAI) | IAM privilege escalation path agent using Neo4j graph analysis across OCI, AWS, and Azure. |
| [SOCAnalystAI](https://github.com/CyberAI-Agency/SOCAnalystAI) | AI L1 SOC analyst — triages alerts, enriches with threat intel, determines severity, creates tickets automatically. |
| [CVEResearcherAI](https://github.com/CyberAI-Agency/CVEResearcherAI) | 24/7 CVE monitoring agent with AI enrichment and auto-publishing to LinkedIn, Reddit, X, Discord, and Telegram. |
| [ComplianceCopilotAI](https://github.com/CyberAI-Agency/ComplianceCopilotAI) | AI GRC copilot for NIST 800-53, CIS, ISO 27001, and FedRAMP. Gap analysis, policy templates, and audit evidence generation. |
| [PenTestAgentAI](https://github.com/CyberAI-Agency/PenTestAgentAI) | Autonomous red team agent with strict scope enforcement and human approval gates. |

### Red Team Tools

| Tool | Description |
|---|---|
| [PHANTOMBREACH](https://github.com/nvsaigeetham/PHANTOMBREACH) | Cyberpunk penetration testing platform with AI attack chain planner and built-in report generator. |
| [CloudRaider](https://github.com/CyberAI-Agency/CloudRaider) | MITRE ATT&CK mapped cloud attack simulation for OCI, AWS, and Azure. Safe, scoped purple team scenarios. |
| [IMDSThief](https://github.com/CyberAI-Agency/IMDSThief) | Multi-cloud IMDS credential theft educational demo. Covers OCI, AWS IMDSv1/v2, and Azure. Includes defensive mitigations. |
| [JWTAnalyzer](https://github.com/CyberAI-Agency/JWTAnalyzer) | Cloud JWT token weakness detector. Algorithm confusion, weak secrets, missing claims. OCI IDCS, AWS Cognito, Azure AD. |

### Blue Team & Defensive Tools

| Tool | Description |
|---|---|
| [SIEMForge](https://github.com/CyberAI-Agency/SIEMForge) | Cloud log normalizer converting OCI Audit, AWS CloudTrail, and Azure Monitor logs to ECS format for any SIEM. |
| [SecretScannerAI](https://github.com/CyberAI-Agency/SecretScannerAI) | AI-powered cloud storage secret scanner for OCI Object Storage, S3, and Azure Blob. LLM validation reduces false positives. |

### AI Security Tools

| Tool | Description |
|---|---|
| [PromptGuardAI](https://github.com/nvsaigeetham/PromptGuardAI) | LLM prompt injection and jailbreak detector with MCP server scanning. OWASP Agentic Top 10 checks. |
| [ThreatModelAI](https://github.com/CyberAI-Agency/ThreatModelAI) | AI threat modeling from architecture diagrams. STRIDE + PASTA methodology. Outputs attack trees and MITRE mappings. |
| [CVEChat](https://github.com/CyberAI-Agency/CVEChat) | Conversational interface over live NVD and CISA KEV. Ask plain-English questions about current vulnerabilities. |
| [PhishSenseAI](https://github.com/CyberAI-Agency/PhishSenseAI) | LLM phishing email analyzer. Scores probability, extracts IOCs, identifies techniques, generates training points. |
| [CyberPolicyAI](https://github.com/nvsaigeetham/CyberPolicyAI) | NIST SP 800-53 Rev5 policy generator — 14 sheets, 29K+ live formulas, risk heat maps, gap analysis, cloud provider mapping. |
| [WizExportAnalyzer](https://github.com/CyberAI-Agency/WizExportAnalyzer) | AI-enhanced vulnerability export analyzer. Groups by application, scores by exploitability, generates executive summaries. |

### Education & Community

| Resource | Description |
|---|---|
| [OCI Security Checklist](https://github.com/CyberAI-Agency/oci-security-checklist) | Comprehensive OCI hardening checklist — the definitive community reference for OCI security. |
| [CTF Notes](https://github.com/nvsaigeetham/ctf-notes) | Full write-ups from Wiz CTF competitions: Needle in a Haystack, Game of Pods (CVE-2024-3177), Container Escape, Azure OAuth Abuse, Malware Busters. |
| [CloudSec Interview Prep](https://github.com/CyberAI-Agency/cloudsec-interview-prep) | 500+ cloud security interview questions covering IAM, CSPM, IR, and architecture across OCI, AWS, Azure, and GCP. |
| [Threat Intel Portal](https://cyberai.agency) | Live CVE feed with AI-powered summaries and cloud-specific advisories — updated continuously. |

---

## OCI Security

### Learning & Documentation
- [OCI Security Architecture](https://www.oracle.com/security/cloud-security/) — Official Oracle OCI security documentation
- [OCI CIS Benchmark](https://www.cisecurity.org/benchmark/oracle_cloud) — CIS benchmark for Oracle Cloud Infrastructure
- [OCI Cloud Guard Documentation](https://docs.oracle.com/en-us/iaas/cloud-guard/) — Native OCI security monitoring service
- [OCI IAM Documentation](https://docs.oracle.com/en-us/iaas/Content/Identity/home.htm) — OCI Identity and Access Management
- [OCI Security Learning Path](https://learn.oracle.com/ols/learning-path/become-an-oci-security-professional/35644/98057) — Official Oracle certification learning path

### OCI Security Practice
- [CloudGoat-OCI](https://github.com/CyberAI-Agency/CloudGoat-OCI) ⚡ — Hands-on OCI attack scenarios
- [OCI Security Checklist](https://github.com/CyberAI-Agency/oci-security-checklist) ⚡ — Hardening reference
- [CTF Notes — OCI Scenarios](https://github.com/nvsaigeetham/ctf-notes) ⚡ — Real attack write-ups

---

## AWS Security

### Learning & Documentation
- [AWS Security Documentation](https://docs.aws.amazon.com/security/) — Official AWS security guides
- [AWS Well-Architected Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html) — AWS security best practices
- [AWS CloudTrail Documentation](https://docs.aws.amazon.com/cloudtrail/) — AWS audit logging reference
- [AWS IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html) — Official IAM guidance
- [flaws.cloud](http://flaws.cloud) — Free AWS security CTF challenges
- [flaws2.cloud](http://flaws2.cloud) — AWS attacker and defender paths

### AWS Security Practice
- [CloudSentinel](https://github.com/CyberAI-Agency/CloudSentinel) ⚡ — Multi-cloud IAM auditor including AWS
- [ThreatHunterAI](https://github.com/CyberAI-Agency/ThreatHunterAI) ⚡ — AWS CloudTrail threat hunting
- [IMDSThief](https://github.com/CyberAI-Agency/IMDSThief) ⚡ — AWS IMDS educational demo
- [CTF Notes — MCRTA AWS Labs](https://github.com/nvsaigeetham/ctf-notes) ⚡ — AWS SSRF and IAM privesc overviews

---

## Azure Security

### Learning & Documentation
- [Azure Security Documentation](https://docs.microsoft.com/en-us/azure/security/) — Official Microsoft Azure security docs
- [Azure Security Benchmark](https://docs.microsoft.com/en-us/security/benchmark/azure/) — Microsoft security best practices
- [Entra ID Documentation](https://docs.microsoft.com/en-us/azure/active-directory/) — Azure AD / Entra ID reference
- [Azure Key Vault Best Practices](https://docs.microsoft.com/en-us/azure/key-vault/general/best-practices) — Secrets management guidance
- [Microsoft Defender for Cloud Docs](https://docs.microsoft.com/en-us/azure/defender-for-cloud/) — Native Azure CSPM

### Azure Security Practice
- [CloudSentinel](https://github.com/CyberAI-Agency/CloudSentinel) ⚡ — Multi-cloud IAM auditor including Azure
- [JWTAnalyzer](https://github.com/CyberAI-Agency/JWTAnalyzer) ⚡ — Azure AD JWT token weakness detector
- [CTF Notes — Breaking The Barriers](https://github.com/nvsaigeetham/ctf-notes) ⚡ — Azure OAuth Entra ID write-up

---

## GCP Security

### Learning & Documentation
- [GCP Security Documentation](https://cloud.google.com/security) — Official Google Cloud security docs
- [GCP Security Best Practices](https://cloud.google.com/security/best-practices) — Google Cloud security guidance
- [GCP IAM Documentation](https://cloud.google.com/iam/docs) — GCP Identity and Access Management reference
- [GCP Cloud Audit Logs](https://cloud.google.com/logging/docs/audit) — GCP audit logging reference

### GCP Security Practice
- [CloudSentinel](https://github.com/CyberAI-Agency/CloudSentinel) ⚡ — Multi-cloud IAM auditor including GCP
- [ThreatHunterAI](https://github.com/CyberAI-Agency/ThreatHunterAI) ⚡ — GCP audit log threat hunting

---

## AI Security

### Learning & Documentation
- [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/) — Top 10 risks for LLM applications
- [OWASP Agentic AI Top 10](https://owasp.org/www-project-top-10-for-agentic-ai/) — Top 10 risks for AI agents
- [MITRE ATLAS](https://atlas.mitre.org/) — Adversarial threat landscape for AI systems
- [NIST AI Risk Management Framework](https://www.nist.gov/system/files/documents/2023/01/26/NIST.AI.100-1.pdf) — AI security and governance guidance

### AI Security Practice
- [PromptGuardAI](https://github.com/nvsaigeetham/PromptGuardAI) ⚡ — LLM prompt injection detector
- [ThreatModelAI](https://github.com/CyberAI-Agency/ThreatModelAI) ⚡ — AI threat modeling tool
- [PhishSenseAI](https://github.com/CyberAI-Agency/PhishSenseAI) ⚡ — AI phishing analyzer

---

## Threat Intelligence

### Sources & Feeds
- [CISA KEV Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) — US government Known Exploited Vulnerabilities
- [NVD — NIST](https://nvd.nist.gov/) — National Vulnerability Database — official CVE source
- [MITRE ATT&CK Cloud Matrix](https://attack.mitre.org/matrices/enterprise/cloud/) — Cloud attack technique framework
- [CyberAI Threat Intel Portal](https://cyberai.agency) ⚡ — Live CVE feed with AI summaries and cloud advisories

---

## Compliance & GRC

### Frameworks & Standards
- [NIST SP 800-53 Rev5](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final) — Security and privacy controls
- [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks) — Security configuration guidelines for all major platforms
- [ISO 27001](https://www.iso.org/isoiec-27001-information-security.html) — Information security management standard
- [CSA Cloud Controls Matrix](https://cloudsecurityalliance.org/research/cloud-controls-matrix/) — Cloud security controls framework
- [FedRAMP](https://www.fedramp.gov/) — US federal cloud security authorization framework

### GRC Practice
- [CyberPolicyAI](https://github.com/nvsaigeetham/CyberPolicyAI) ⚡ — NIST 800-53 policy generator
- [ComplianceCopilotAI](https://github.com/CyberAI-Agency/ComplianceCopilotAI) ⚡ — AI GRC copilot
- [OCI Security Checklist](https://github.com/CyberAI-Agency/oci-security-checklist) ⚡ — OCI CIS benchmark reference

---

## CTF & Practice Labs

| Resource | Description |
|---|---|
| [CloudGoat-OCI](https://github.com/CyberAI-Agency/CloudGoat-OCI) ⚡ | OCI vulnerable-by-design CTF lab — first of its kind |
| [CTF Notes](https://github.com/nvsaigeetham/ctf-notes) ⚡ | Real CTF write-ups — Wiz CTF, MCRTA, MCBTA |
| [Wiz CTF](https://www.wiz.io/lp/wiz-ctf) | Cloud security CTF competitions by Wiz |
| [flaws.cloud](http://flaws.cloud) | Free AWS security CTF challenges |
| [HackTheBox](https://www.hackthebox.com/) | Cloud security challenges platform |
| [TryHackMe](https://tryhackme.com/) | Guided cloud security learning paths |

---

## Certifications

| Certification | Provider | Level | Focus |
|---|---|---|---|
| **CCSP** | ISC2 | Advanced | Cloud security architecture |
| **CCSK** | CSA | Intermediate | Cloud security knowledge |
| **AWS Security Specialty** | AWS | Advanced | AWS security services |
| **Azure Security Engineer (AZ-500)** | Microsoft | Advanced | Azure security |
| **GCP Professional Cloud Security** | Google | Advanced | GCP security |
| **OCI Security Professional** | Oracle | Advanced | OCI security |
| **CASP+** | CompTIA | Advanced | Enterprise security |
| **MCRTA** | Cyberwarfare Labs | Intermediate | Multi-cloud red team |
| **MCBTA** | Cyberwarfare Labs | Intermediate | Multi-cloud blue team |
| **OSCP** | Offensive Security | Advanced | Penetration testing |

---

## Official Documentation

| Provider | Link |
|---|---|
| Oracle OCI | [docs.oracle.com/iaas](https://docs.oracle.com/en-us/iaas/Content/home.htm) |
| AWS | [docs.aws.amazon.com](https://docs.aws.amazon.com/) |
| Azure | [docs.microsoft.com/azure](https://docs.microsoft.com/en-us/azure/) |
| GCP | [cloud.google.com/docs](https://cloud.google.com/docs) |
| NIST | [csrc.nist.gov](https://csrc.nist.gov/) |
| CISA | [cisa.gov](https://www.cisa.gov/) |

---

## Blogs & Research

- [CyberAI Agency Blog](https://cyberai.agency/blog) ⚡ — Cloud security tools, AI agents, and threat intelligence
- [Wiz Research](https://www.wiz.io/blog/tag/research) — Cloud security vulnerability research
- [CISA Advisories](https://www.cisa.gov/news-events/cybersecurity-advisories) — US government cybersecurity advisories
- [Oracle Security Blog](https://blogs.oracle.com/cloudsecurity/) — OCI security updates and guidance
- [AWS Security Blog](https://aws.amazon.com/blogs/security/) — Official AWS security blog
- [Microsoft Security Blog](https://www.microsoft.com/en-us/security/blog/) — Official Microsoft security blog
- [Google Cloud Security Blog](https://cloud.google.com/blog/products/identity-security) — GCP security updates

---

## Conferences & Communities

- [DEF CON Cloud Village](https://cloud-village.org/) — Annual cloud security track at DEF CON
- [CloudSecNext](https://cloudsecnext.com/) — Dedicated cloud security conference
- [BSides](https://www.securitybsides.com/) — Community-driven security conferences worldwide
- [RSA Conference](https://www.rsaconference.com/) — Major enterprise security conference
- [r/netsec](https://reddit.com/r/netsec) — Technical network security community
- [r/blueteamsec](https://reddit.com/r/blueteamsec) — Defensive security community
- [CyberAI Agency Discord](https://discord.gg/cyberai-agency) ⚡ — Cloud security community

---

## Contributing

Contributions welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) first.

- Suggested additions: official documentation, learning resources, certifications, and practice labs
- Keep descriptions concise — one line per entry
- ⚡ marks tools and resources built by CyberAI Agency

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [CyberAI Agency](https://github.com/CyberAI-Agency) has waived all copyright and related rights to this work.
