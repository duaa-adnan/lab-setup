#  Blue Team Internship. ITSimplera Institute

**Week 1 Task: SIEM Deployment & File Integrity Monitoring with Wazuh**

[![Internship](https://img.shields.io/badge/Internship-ITSimplera%20Institute-0A66C2)](#)
[![Track](https://img.shields.io/badge/Track-Blue%20Team%20%2F%20SOC-1E90FF)](#)
[![Tool](https://img.shields.io/badge/SIEM-Wazuh-red)](#)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen)](#)

**Author:** Duaa Bint E Adnan

---

##  Overview

This repository documents my work as a **Blue Team Intern** at **ITSimplera Institute**, undertaken as part of a hands-on Security Operations Center (SOC) internship program. The goal of the internship is to build practical, industry-relevant skills in defensive cybersecurity by working directly with the tools and workflows used in real-world SOC environments.

This README covers **Week 1**, in which I deployed and configured a fully functional SIEM environment using **Wazuh**, connected endpoint agents, and validated security alerting through File Integrity Monitoring (FIM).

---
## 📑 Table of Contents

- Week 1 – Task Brief
- Objective
- Lab Environment
- Architecture
- What I Implemented
- Deployment Screenshots
- Challenges & Troubleshooting
- Tools & Technologies
- Skills Demonstrated
- Lessons Learned
- Outcome
- Documentation
---

##  Week 1 — Task Brief

| Detail | Info |
|---|---|
| **Task Type** | Setup + Exploration |
| **Role** | Blue Team Intern |

### Objective
Deploy and configure the **Wazuh SIEM** platform to establish a centralized security monitoring environment, connect endpoints via the Wazuh Agent, configure **File Integrity Monitoring (FIM)**, and validate that security alerts are generated and captured correctly, laying the foundation for future Blue Team operations.

---

##  Lab Environment

| Component | Details |
|-----------|----------|
| Host Machine | Windows 11 |
| Hypervisor | VMware Workstation |
| Wazuh Server | Ubuntu Server 22.04 LTS |
| SIEM Platform | Wazuh |
| Endpoint 1 | Windows |
| Endpoint 2 | Ubuntu |
| Monitoring | File Integrity Monitoring |

##  What I Implemented

- ✅ Deployed the **Wazuh Virtual Appliance** and configured the **Wazuh Manager**
- ✅ Installed and registered the **Wazuh Agent on a Windows endpoint**
- ✅ Installed and registered the **Wazuh Agent on a Linux endpoint**
- ✅ Configured **File Integrity Monitoring (FIM)** to track file/directory changes in real time
- ✅ Simulated file-level changes to **trigger and validate security alerts**
- ✅ Verified end-to-end alert flow on the **Wazuh Dashboard**
- ✅ Documented every step of the deployment process with supporting screenshots

---
##  Challenges & Troubleshooting

### Challenge

The Wazuh Dashboard installation failed during the first deployment attempt.

### Cause

The virtual machine was allocated only 2 GB RAM, which was insufficient.

### Resolution

- Increased RAM to 4 GB
- Updated Ubuntu packages
- Reinstalled Wazuh

### Result

The installation completed successfully and all services became operational.

##  Tools & Technologies

- **Wazuh** (Manager, Agent, and Dashboard)
- **VirtualBox / Virtual Appliance** for the Wazuh server
- **Windows** endpoint (agent installation & registration)
- **Linux (Ubuntu)** endpoint (agent installation & registration)
- **File Integrity Monitoring (FIM)** module
- Command-line administration for agent configuration and registration

---

##  Skills Demonstrated

- Hands-on understanding of **SIEM architecture** and centralized log management
- Practical experience deploying and hardening a security monitoring stack from scratch
- Configuring **File Integrity Monitoring** to detect unauthorized or unexpected file changes
- Reading, interpreting, and validating **security alerts** the way a SOC analyst would
- Cross-platform endpoint management (Windows + Linux) within a single SIEM pane
- Structuring technical work into clear, professional documentation for stakeholders

---
##  Lessons Learned

- Proper VM resource allocation is essential before deploying SIEM platforms.
- File Integrity Monitoring effectively detects unauthorized file modifications.
- Successful endpoint registration is critical for centralized monitoring.
- Troubleshooting and documentation are key parts of SOC operations.

Each screenshot corresponds to a discrete stage of the deployment, from spinning up the Wazuh appliance, through agent registration on both operating systems, to the final alert generated and captured after a monitored file was modified.

---

##  Outcome

By the end of Week 1, I had a fully operational SIEM pipeline: endpoints reporting into a central Wazuh Manager, File Integrity Monitoring actively watching designated paths, and verified alerts flowing through to the dashboard in real time, the essential building block for every SOC workflow that follows.

---

##  Resources

📄 Full Technical Report

📷 Screenshots

💼 LinkedIn Post: https://www.linkedin.com/posts/duaa-adnan_it-simplera-week-1-report-set-up-exploration-ugcPost-7479186025689391104-5hum/?utm_source=share&utm_medium=member_desktop&rcm=ACoAADZXX2kBVoIL7tdPW2-3qH6yuAHAwQAOOec

---
##  Future Improvements

- Integrate Sysmon logging
- Configure email alerting
- Create custom detection rules
- Monitor additional endpoints
- Expand the SIEM environment

<p align="center"><i>Part of my ongoing journey into Blue Team & SOC operations, building this repository one task at a time.</i></p>

<p align="center"><b>Duaa Bint E Adnan</b> · Blue Team Intern @ ITSimplera Institute</p>
