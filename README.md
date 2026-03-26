# Awesome Cloud Security ⚡

> A curated list of cloud security tools, frameworks, blogs, certifications, and learning resources — with a special focus on **OCI, AWS, Azure, and GCP**.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Maintained](https://img.shields.io/badge/Maintained-yes-green.svg)](https://github.com/CyberAI-Agency/awesome-cloud-sec)
[![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](LICENSE)

Maintained by [@nvsaigeetham](https://github.com/nvsaigeetham) · [CyberAI Agency](https://github.com/CyberAI-Agency)

---

## Contents

- [CSPM & Posture Management](#cspm--posture-management)
- [IAM & Identity Security](#iam--identity-security)
- [Vulnerable-by-Design Labs](#vulnerable-by-design-labs)
- [Red Team / Offensive Tools](#red-team--offensive-tools)
- [Blue Team / Defensive Tools](#blue-team--defensive-tools)
- [AI-Powered Security Tools](#ai-powered-security-tools)
- [Threat Intelligence](#threat-intelligence)
- [IaC Security](#iac-security)
- [Container & Kubernetes Security](#container--kubernetes-security)
- [Secrets Management](#secrets-management)
- [OCI-Specific Resources](#oci-specific-resources)
- [AWS-Specific Resources](#aws-specific-resources)
- [Azure-Specific Resources](#azure-specific-resources)
- [GCP-Specific Resources](#gcp-specific-resources)
- [SIEM & Log Management](#siem--log-management)
- [Compliance & GRC](#compliance--grc)
- [CTF & Practice Labs](#ctf--practice-labs)
- [Certifications](#certifications)
- [Blogs & News](#blogs--news)
- [Conferences & Communities](#conferences--communities)

---

## CSPM & Posture Management

- **[Prowler](https://github.com/prowler-cloud/prowler)** — Open-source CSPM for AWS, Azure, GCP, Kubernetes. 300+ CIS checks. ![Stars](https://img.shields.io/github/stars/prowler-cloud/prowler?style=flat-square)
- **[ScoutSuite](https://github.com/nccgroup/ScoutSuite)** — Multi-cloud security auditing tool. Supports OCI, AWS, Azure, GCP, Alibaba. ![Stars](https://img.shields.io/github/stars/nccgroup/ScoutSuite?style=flat-square)
- **[CloudSploit](https://github.com/aquasecurity/cloudsploit)** — Cloud security configuration scanner by Aqua Security. ![Stars](https://img.shields.io/github/stars/aquasecurity/cloudsploit?style=flat-square)
- **[CloudCustodian](https://github.com/cloud-custodian/cloud-custodian)** — Rules engine for cloud security, cost, and compliance. ![Stars](https://img.shields.io/github/stars/cloud-custodian/cloud-custodian?style=flat-square)
- **[Steampipe](https://github.com/turbot/steampipe)** — SQL-based cloud configuration querying across all major providers. ![Stars](https://img.shields.io/github/stars/turbot/steampipe?style=flat-square)
- **[CloudQuery](https://github.com/cloudquery/cloudquery)** — Cloud asset inventory framework using PostgreSQL. ![Stars](https://img.shields.io/github/stars/cloudquery/cloudquery?style=flat-square)
- **[CSPMlite](https://github.com/CyberAI-Agency/CSPMlite)** ⚡ — Lightweight CSPM dashboard with React UI and AI finding summarizer.

---

## IAM & Identity Security

- **[pMapper](https://github.com/nccgroup/PMapper)** — AWS IAM privilege escalation path mapper using graph analysis. ![Stars](https://img.shields.io/github/stars/nccgroup/PMapper?style=flat-square)
- **[Cloudsplaining](https://github.com/salesforce/cloudsplaining)** — AWS IAM security assessment tool identifying least-privilege violations. ![Stars](https://img.shields.io/github/stars/salesforce/cloudsplaining?style=flat-square)
- **[policy_sentry](https://github.com/salesforce/policy_sentry)** — AWS IAM least privilege policy generator. ![Stars](https://img.shields.io/github/stars/salesforce/policy_sentry?style=flat-square)
- **[AirIAM](https://github.com/bridgecrewio/AirIAM)** — AWS IAM least privilege enforcement tool. ![Stars](https://img.shields.io/github/stars/bridgecrewio/AirIAM?style=flat-square)
- **[CloudSentinel](https://github.com/CyberAI-Agency/CloudSentinel)** ⚡ — Multi-cloud IAM auditor (OCI · AWS · Azure · GCP) with AI remediation.
- **[IAMAnalyzerAI](https://github.com/CyberAI-Agency/IAMAnalyzerAI)** ⚡ — AI agent for IAM privilege escalation path analysis using Neo4j.
- **[MFAWatch](https://github.com/CyberAI-Agency/MFAWatch)** ⚡ — MFA gap auditor across OCI, AWS, and Azure with AI remediation emails.
- **[OCI-PAR-Tracker](https://github.com/CyberAI-Agency/OCI-PAR-Tracker)** ⚡ — Privileged Access Review tracker for OCI (Classic IAM + IDCS) with risk scoring.

---

## Vulnerable-by-Design Labs

- **[CloudGoat-OCI](https://github.com/CyberAI-Agency/CloudGoat-OCI)** ⚡ — First vulnerable-by-design OCI environment. IAM privesc, IDCS takeover, IMDS theft, VCN escape. **No other tool like this exists.**
- **[CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat)** — Rhino Security Labs' vulnerable-by-design AWS deployment tool. ![Stars](https://img.shields.io/github/stars/RhinoSecurityLabs/cloudgoat?style=flat-square)
- **[Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat)** — Vulnerable-by-design Kubernetes cluster for K8s security training. ![Stars](https://img.shields.io/github/stars/madhuakula/kubernetes-goat?style=flat-square)
- **[WrongSecrets](https://github.com/OWASP/wrongsecrets)** — OWASP vulnerable app demonstrating secrets management mistakes. ![Stars](https://img.shields.io/github/stars/OWASP/wrongsecrets?style=flat-square)
- **[flaws.cloud](http://flaws.cloud)** — AWS security challenges teaching through CTF-style flaws.
- **[flaws2.cloud](http://flaws2.cloud)** — Sequel to flaws.cloud with attacker and defender paths.

---

## Red Team / Offensive Tools

- **[Pacu](https://github.com/RhinoSecurityLabs/pacu)** — AWS exploitation framework for offensive security testing. ![Stars](https://img.shields.io/github/stars/RhinoSecurityLabs/pacu?style=flat-square)
- **[MicroBurst](https://github.com/NetSPI/MicroBurst)** — PowerShell scripts for Azure security assessment and exploitation. ![Stars](https://img.shields.io/github/stars/NetSPI/MicroBurst?style=flat-square)
- **[GCPBucketBrute](https://github.com/RhinoSecurityLabs/GCPBucketBrute)** — GCP bucket enumeration and privilege escalation. ![Stars](https://img.shields.io/github/stars/RhinoSecurityLabs/GCPBucketBrute?style=flat-square)
- **[Stormspotter](https://github.com/Azure/Stormspotter)** — Azure AD attack graph tool for mapping identity paths. ![Stars](https://img.shields.io/github/stars/Azure/Stormspotter?style=flat-square)
- **[enumerate-iam](https://github.com/andresriancho/enumerate-iam)** — Brute force enumeration of AWS IAM permissions. ![Stars](https://img.shields.io/github/stars/andresriancho/enumerate-iam?style=flat-square)
- **[PHANTOMBREACH](https://github.com/nvsaigeetham/PHANTOMBREACH)** ⚡ — Cyberpunk penetration testing platform with AI attack chain planner.
- **[CloudRaider](https://github.com/CyberAI-Agency/CloudRaider)** ⚡ — MITRE ATT&CK mapped cloud attack simulation for OCI, AWS, Azure.
- **[IMDSThief](https://github.com/CyberAI-Agency/IMDSThief)** ⚡ — Multi-cloud IMDS credential theft educational demo with defensive mitigations.

---

## Blue Team / Defensive Tools

- **[Falco](https://github.com/falcosecurity/falco)** — Cloud-native runtime security for containers and Kubernetes. ![Stars](https://img.shields.io/github/stars/falcosecurity/falco?style=flat-square)
- **[Cartography](https://github.com/lyft/cartography)** — Infrastructure relationship mapper using Neo4j. AWS focus. ![Stars](https://img.shields.io/github/stars/lyft/cartography?style=flat-square)
- **[CloudMapper](https://github.com/duo-labs/cloudmapper)** — AWS environment visualization and network analysis tool. ![Stars](https://img.shields.io/github/stars/duo-labs/cloudmapper?style=flat-square)
- **[SIEMForge](https://github.com/CyberAI-Agency/SIEMForge)** ⚡ — Cloud log normalizer converting OCI/AWS/Azure logs to ECS format.
- **[SecBaseline](https://github.com/CyberAI-Agency/SecBaseline)** ⚡ — CIS benchmark auto-checker with delta tracking and PDF/Excel output.
- **[CloudGuardExporter](https://github.com/CyberAI-Agency/CloudGuardExporter)** ⚡ — OCI Cloud Guard problem exporter with AI-generated executive reports.

---

## AI-Powered Security Tools

- **[CloudGuardianAI](https://github.com/CyberAI-Agency/CloudGuardianAI)** ⚡ — Autonomous 24/7 cloud posture monitoring agent built on Claude.
- **[ThreatHunterAI](https://github.com/CyberAI-Agency/ThreatHunterAI)** ⚡ — AI-driven SIEM threat hunting with MITRE ATT&CK mapping.
- **[SOCAnalystAI](https://github.com/CyberAI-Agency/SOCAnalystAI)** ⚡ — AI L1 SOC analyst for alert triage, enrichment, and ticketing.
- **[PromptGuardAI](https://github.com/nvsaigeetham/PromptGuardAI)** ⚡ — LLM prompt injection and jailbreak detector with MCP server scanning.
- **[ThreatModelAI](https://github.com/CyberAI-Agency/ThreatModelAI)** ⚡ — AI threat modeling from architecture diagrams using STRIDE + PASTA.
- **[PhishSenseAI](https://github.com/CyberAI-Agency/PhishSenseAI)** ⚡ — LLM phishing email analyzer and IOC extractor.
- **[CyberOpsOrchestrator](https://github.com/CyberAI-Agency/CyberOpsOrchestrator)** ⚡ — Master AI coordinator routing security tasks across all specialist agents.

---

## Threat Intelligence

- **[CVEResearcherAI](https://github.com/CyberAI-Agency/CVEResearcherAI)** ⚡ — 24/7 CVE monitor with AI enrichment and auto-publishing to 6 platforms.
- **[OpenCTI](https://github.com/OpenCTI-Platform/opencti)** — Open-source cyber threat intelligence platform. ![Stars](https://img.shields.io/github/stars/OpenCTI-Platform/opencti?style=flat-square)
- **[MISP](https://github.com/MISP/MISP)** — Malware Information Sharing Platform for threat intelligence. ![Stars](https://img.shields.io/github/stars/MISP/MISP?style=flat-square)
- **[TheHive](https://github.com/TheHive-Project/TheHive)** — Scalable security incident response platform. ![Stars](https://img.shields.io/github/stars/TheHive-Project/TheHive?style=flat-square)
- **[CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)** — Known Exploited Vulnerabilities catalog — essential daily reading.
- **[NVD](https://nvd.nist.gov/)** — NIST National Vulnerability Database — official CVE source.

---

## IaC Security

- **[Checkov](https://github.com/bridgecrewio/checkov)** — IaC static analysis for Terraform, CloudFormation, Kubernetes. ![Stars](https://img.shields.io/github/stars/bridgecrewio/checkov?style=flat-square)
- **[tfsec](https://github.com/aquasecurity/tfsec)** — Terraform security scanner. Fast, focused, CI/CD friendly. ![Stars](https://img.shields.io/github/stars/aquasecurity/tfsec?style=flat-square)
- **[Terrascan](https://github.com/tenable/terrascan)** — Static code analyzer for Terraform, K8s, Helm, Dockerfile. ![Stars](https://img.shields.io/github/stars/tenable/terrascan?style=flat-square)
- **[KICS](https://github.com/Checkmarx/kics)** — Keeping Infrastructure as Code Secure — multi-format IaC scanner. ![Stars](https://img.shields.io/github/stars/Checkmarx/kics?style=flat-square)
- **[CloudDriftDetector](https://github.com/CyberAI-Agency/CloudDriftDetector)** ⚡ — Detects drift between Terraform state and live cloud configuration.

---

## Container & Kubernetes Security

- **[Trivy](https://github.com/aquasecurity/trivy)** — Comprehensive vulnerability scanner for containers, IaC, and filesystems. ![Stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=flat-square)
- **[Grype](https://github.com/anchore/grype)** — Fast vulnerability scanner for container images. ![Stars](https://img.shields.io/github/stars/anchore/grype?style=flat-square)
- **[Kube-bench](https://github.com/aquasecurity/kube-bench)** — Checks Kubernetes clusters against CIS Kubernetes Benchmark. ![Stars](https://img.shields.io/github/stars/aquasecurity/kube-bench?style=flat-square)
- **[Kube-hunter](https://github.com/aquasecurity/kube-hunter)** — Kubernetes penetration testing tool. ![Stars](https://img.shields.io/github/stars/aquasecurity/kube-hunter?style=flat-square)
- **[Falco](https://github.com/falcosecurity/falco)** — Runtime security monitoring for containers and Kubernetes. ![Stars](https://img.shields.io/github/stars/falcosecurity/falco?style=flat-square)

---

## Secrets Management

- **[TruffleHog](https://github.com/trufflesecurity/trufflehog)** — Scans git history and filesystems for leaked credentials. ![Stars](https://img.shields.io/github/stars/trufflesecurity/trufflehog?style=flat-square)
- **[Gitleaks](https://github.com/gitleaks/gitleaks)** — Fast, lightweight secret scanner for git repos and files. ![Stars](https://img.shields.io/github/stars/gitleaks/gitleaks?style=flat-square)
- **[detect-secrets](https://github.com/Yelp/detect-secrets)** — Secret detection focused on reducing false positives. ![Stars](https://img.shields.io/github/stars/Yelp/detect-secrets?style=flat-square)
- **[HashiCorp Vault](https://github.com/hashicorp/vault)** — Secrets management, encryption-as-a-service, and privileged access. ![Stars](https://img.shields.io/github/stars/hashicorp/vault?style=flat-square)
- **[SecretScannerAI](https://github.com/CyberAI-Agency/SecretScannerAI)** ⚡ — AI-powered cloud storage secret scanner (OCI Object Storage, S3, Azure Blob).

---

## OCI-Specific Resources

### Tools
- **[CloudGoat-OCI](https://github.com/CyberAI-Agency/CloudGoat-OCI)** ⚡ — Vulnerable-by-design OCI CTF lab. First and only of its kind.
- **[OCI-PAR-Tracker](https://github.com/CyberAI-Agency/OCI-PAR-Tracker)** ⚡ — Privileged Access Review tracker for OCI Classic IAM + IDCS.
- **[VCN-SecurityAudit](https://github.com/CyberAI-Agency/VCN-SecurityAudit)** ⚡ — OCI VCN security list and NSG auditor across all regions and compartments.
- **[OCIAttackGraph](https://github.com/CyberAI-Agency/OCIAttackGraph)** ⚡ — OCI privilege escalation path mapper using Neo4j.
- **[ScoutSuite](https://github.com/nccgroup/ScoutSuite)** — Only major OSS multi-cloud auditor with OCI support (limited coverage).

### Official Documentation
- **[OCI Security Architecture](https://www.oracle.com/security/cloud-security/)** — Oracle's official OCI security documentation.
- **[OCI CIS Benchmark](https://www.cisecurity.org/benchmark/oracle_cloud)** — CIS benchmark for Oracle Cloud Infrastructure.
- **[OCI Cloud Guard Docs](https://docs.oracle.com/en-us/iaas/cloud-guard/)** — Native OCI security monitoring service documentation.
- **[OCI Security Checklist](https://github.com/CyberAI-Agency/oci-security-checklist)** ⚡ — Community-maintained comprehensive OCI hardening checklist.

### Learning
- **[OCI Security Learning Path](https://learn.oracle.com/ols/learning-path/become-an-oci-security-professional/35644/98057)** — Official Oracle OCI security certification learning path.
- **[OCI CTF Write-ups](https://github.com/nvsaigeetham/ctf-notes)** ⚡ — Real OCI attack scenarios from Wiz CTF competitions.

---

## AWS-Specific Resources

### Tools
- **[Prowler](https://github.com/prowler-cloud/prowler)** — Industry standard AWS/Azure/GCP security auditing tool.
- **[CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat)** — Vulnerable-by-design AWS deployment tool by Rhino Security Labs.
- **[Pacu](https://github.com/RhinoSecurityLabs/pacu)** — AWS exploitation framework.
- **[pMapper](https://github.com/nccgroup/PMapper)** — AWS IAM privilege escalation path analyzer.

### Learning
- **[flaws.cloud](http://flaws.cloud)** — Free AWS security CTF challenges.
- **[AWS Security Workshops](https://workshops.aws/categories/Security)** — Official AWS security hands-on workshops.

---

## Azure-Specific Resources

### Tools
- **[MicroBurst](https://github.com/NetSPI/MicroBurst)** — PowerShell toolkit for Azure security assessments.
- **[Stormspotter](https://github.com/Azure/Stormspotter)** — Azure AD and resource attack graph tool.
- **[ROADrecon](https://github.com/dirkjanm/ROADtools)** — Azure AD exploration and enumeration framework.
- **[JWTAnalyzer](https://github.com/CyberAI-Agency/JWTAnalyzer)** ⚡ — Cloud JWT weakness detector including Azure AD tokens.

### Learning
- **[Azure Security Benchmark](https://docs.microsoft.com/en-us/security/benchmark/azure/)** — Microsoft's security best practices for Azure.

---

## GCP-Specific Resources

- **[GCPBucketBrute](https://github.com/RhinoSecurityLabs/GCPBucketBrute)** — GCP bucket enumeration and privilege escalation.
- **[Forseti Security](https://github.com/forseti-security/forseti-security)** — GCP security monitoring and enforcement.
- **[ScoutSuite](https://github.com/nccgroup/ScoutSuite)** — Multi-cloud auditor with GCP support.

---

## SIEM & Log Management

- **[Wazuh](https://github.com/wazuh/wazuh)** — Open-source XDR and SIEM for host monitoring and threat detection. ![Stars](https://img.shields.io/github/stars/wazuh/wazuh?style=flat-square)
- **[Graylog](https://github.com/Graylog2/graylog2-server)** — Open-source log management and SIEM platform. ![Stars](https://img.shields.io/github/stars/Graylog2/graylog2-server?style=flat-square)
- **[Sigma](https://github.com/SigmaHQ/sigma)** — Generic signature format for SIEM detection rules. ![Stars](https://img.shields.io/github/stars/SigmaHQ/sigma?style=flat-square)
- **[ElastAlert](https://github.com/Yelp/elastalert)** — Alerting framework for Elasticsearch SIEM use cases. ![Stars](https://img.shields.io/github/stars/Yelp/elastalert?style=flat-square)
- **[SIEMForge](https://github.com/CyberAI-Agency/SIEMForge)** ⚡ — Cloud log normalizer to ECS format for any SIEM. OCI · AWS · Azure.

---

## Compliance & GRC

- **[CyberPolicyAI](https://github.com/nvsaigeetham/CyberPolicyAI)** ⚡ — NIST SP 800-53 Rev5 Excel generator — 14 sheets, 29K+ live formulas.
- **[ComplianceCopilotAI](https://github.com/CyberAI-Agency/ComplianceCopilotAI)** ⚡ — AI GRC copilot for NIST, CIS, ISO 27001, FedRAMP.
- **[OpenSCAP](https://github.com/OpenSCAP/openscap)** — Open-source SCAP toolkit for compliance automation. ![Stars](https://img.shields.io/github/stars/OpenSCAP/openscap?style=flat-square)
- **[CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks)** — Industry-standard security configuration guidelines.
- **[NIST SP 800-53](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)** — NIST security and privacy controls for federal information systems.

---

## CTF & Practice Labs

- **[CloudGoat-OCI](https://github.com/CyberAI-Agency/CloudGoat-OCI)** ⚡ — OCI vulnerable-by-design CTF lab. First of its kind.
- **[CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat)** — AWS vulnerable-by-design CTF lab by Rhino Security Labs.
- **[Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat)** — Kubernetes security CTF lab.
- **[Wiz CTF](https://www.wiz.io/lp/wiz-ctf)** — Cloud security CTF competitions by Wiz.
- **[HackTheBox](https://www.hackthebox.com/)** — Cloud security challenges on HackTheBox platform.
- **[TryHackMe](https://tryhackme.com/)** — Guided cloud security learning paths and labs.
- **[CTF Write-ups](https://github.com/nvsaigeetham/ctf-notes)** ⚡ — Wiz CTF wins: Game of Pods (CVE-2024-3177), Container Escape, Azure OAuth Abuse, and more.

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
| **CEH** | EC-Council | Intermediate | Ethical hacking |
| **OSCP** | Offensive Security | Advanced | Penetration testing |

---

## Blogs & News

- **[CyberAI Agency Blog](https://cyberai.agency/blog)** ⚡ — Cloud security tools, AI agents, and threat intelligence.
- **[Rhino Security Labs](https://rhinosecuritylabs.com/blog/)** — AWS/cloud penetration testing research.
- **[Wiz Research](https://www.wiz.io/blog/tag/research)** — Cloud security vulnerability research.
- **[Christophe Tafani-Dereeper](https://blog.christophetd.fr/)** — Cloud security attack techniques and research.
- **[NCC Group Research](https://research.nccgroup.com/)** — Security research including cloud and AI security.
- **[The Hacker News](https://thehackernews.com/)** — Breaking cybersecurity news and vulnerability coverage.
- **[CISA Advisories](https://www.cisa.gov/news-events/cybersecurity-advisories)** — US government cybersecurity advisories.
- **[Krebs on Security](https://krebsonsecurity.com/)** — Investigative cybersecurity journalism.

---

## Conferences & Communities

- **[DEF CON Cloud Village](https://cloud-village.org/)** — Annual cloud security track at DEF CON.
- **[CloudSecNext](https://cloudsecnext.com/)** — Dedicated cloud security conference.
- **[BSides](https://www.securitybsides.com/)** — Community-driven security conferences worldwide.
- **[RSA Conference](https://www.rsaconference.com/)** — Major enterprise security conference.
- **[r/netsec](https://reddit.com/r/netsec)** — Reddit's technical network security community.
- **[r/blueteamsec](https://reddit.com/r/blueteamsec)** — Reddit's defensive security community.
- **[CyberAI Agency Discord](https://discord.gg/cyberai-agency)** ⚡ — Community for cloud security professionals.

---

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) first.

- Add tools with a brief one-line description and GitHub link
- Maintain alphabetical order within sections
- Verify all links are working before submitting a PR
- ⚡ marks tools built by CyberAI Agency

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [CyberAI Agency](https://github.com/CyberAI-Agency) has waived all copyright and related rights to this work.
