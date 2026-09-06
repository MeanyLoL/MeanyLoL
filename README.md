# Daniel Kosatka

Cybersecurity student focused on internships and entry-level roles in security operations, digital forensics, incident response, vulnerability analysis, and secure systems administration.

---

## About Me

Cybersecurity student at the University of Central Lancashire with practical experience across digital forensics, Linux-based vulnerability work, information security management, network infrastructure, and secure software development.

Current work is centred on building the technical and analytical skills needed for entry-level cybersecurity roles, with particular interest in SOC, DFIR, vulnerability management, and security-focused infrastructure support.

---

## Areas of Focus

- Digital forensics and incident response, including evidence handling, chain of custody, acquisition planning, artifact recovery, and investigation workflows
- Cloud security detection engineering, including AWS CloudTrail log analysis, event normalization, and detection-as-code mapped to MITRE ATT&CK
- Vulnerability analysis and attack simulation using Linux-based environments, reconnaissance, mitigation testing, and defensive control evaluation
- Information security management, including governance, risk assessment, standards, controls, and BYOD security strategy
- Network and systems administration, including authentication, DNS, DHCP, deployment, monitoring, VPN access, and infrastructure documentation
- Secure software development in C++ with object-oriented design, inheritance, polymorphism, and maintainable system architecture

---

## Technical Skills

- **Security:** incident response, digital evidence handling, forensic analysis, vulnerability assessment, OWASP mapping, risk assessment, control selection
- **Cloud:** AWS CloudTrail analysis, boto3, detection-as-code (YAML rules), MITRE ATT&CK mapping, DuckDB, Terraform
- **Systems:** Windows Server, Active Directory, DNS, DHCP, deployment workflows, monitoring, VPN, backup planning, remote administration
- **Development:** Python, C++, object-oriented programming, design patterns, CLI applications, input validation, maintainable code design
- **Tooling & Controls:** EnCase workflows, WAF-style prevention, MFA concepts, access control, filtering, and logging-focused defensive measures

---

## Featured Projects

### CloudTrail Sentinel — AWS Detection Pipeline (In Progress)

A detection pipeline for AWS CloudTrail logs, built to explore cloud security detection engineering. It ingests control-plane audit events, normalizes them into a consistent schema, and evaluates them against version-controlled detection rules mapped to MITRE ATT&CK. Designed to be offline-first, running end-to-end on bundled sample logs without AWS credentials.

**Highlights:**
- Ingests CloudTrail records from local disk or S3 (plain and gzip-compressed) via boto3
- Normalizes inconsistent CloudTrail event formats into a unified 16-field schema
- Detection rules written as version-controlled YAML mapped to MITRE ATT&CK techniques, following a detection-as-code approach (8 rules planned, including root account abuse, CloudTrail tampering, and GuardDuty disabling)
- Embedded DuckDB chosen over Elasticsearch for zero-config, single-command setup
- pytest test suite with GitHub Actions CI

Status: Phase 1 of 4 complete (ingestion and normalization); detection engine and dashboard in development.

[View Repository](https://github.com/danielkosatka/cloudtrail-sentinel)

### Enterprise School Network Infrastructure — Active Directory & Security Lab

A full end-to-end Windows Server network deployment simulating a real-world primary school IT environment. The project covers identity management, web security, automated deployment, infrastructure monitoring, and remote access — all built and documented from scratch.

**Highlights:**
- Dual domain controller setup (PDC + BDC) with AD replication, DNS, and DHCP
- Web proxy with LDAP-authenticated content filtering tied to user roles
- Automated bulk user provisioning via a custom Python script
- Nagios XI monitoring with service checks and login auditing
- Application deployment via Group Policy and RDP access restricted by role

[View Repository](https://github.com/MeanyLoL/enterprise-network-deployment)

---

## Projects

| Project | Description | Skills |
|---|---|---|
| [CloudTrail Sentinel](https://github.com/danielkosatka/cloudtrail-sentinel) | AWS CloudTrail detection pipeline — normalizes control-plane logs and evaluates them against MITRE ATT&CK-mapped YAML rules (in progress) | Python, AWS, boto3, DuckDB, MITRE ATT&CK, Terraform |
| [Enterprise School Network Lab](https://github.com/MeanyLoL/enterprise-network-deployment) | Full Windows Server AD environment with proxy, monitoring, and automated deployment | Active Directory, Python, Nagios XI, GPO, Networking |
| [Smart Campus Manager](https://github.com/MeanyLoL/iot-device-management-cpp) | Command-line C++ application for managing smart campus devices across rooms and shared spaces | C++, OOP, Factory Method pattern, CLI design, input validation |

*More projects coming soon.*

---

## What I'm Looking For

Interested in cybersecurity internships and entry-level roles in areas such as cloud security, SOC analysis, digital forensics, incident response, vulnerability management, junior security engineering, and security-focused systems administration.

---

## Interests

- Digital forensics and incident response
- Vulnerability research and defensive security
- Linux and Windows system security
- Secure infrastructure and access control
- Security operations and monitoring
- C++ and low-level systems development
