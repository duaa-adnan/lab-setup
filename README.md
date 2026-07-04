# 🛡️ Blue Team Internship — ITSimplera Institute

**Week 1 Task: SIEM Deployment & File Integrity Monitoring with Wazuh**

[![Internship](https://img.shields.io/badge/Internship-ITSimplera%20Institute-0A66C2)](#)
[![Track](https://img.shields.io/badge/Track-Blue%20Team%20%2F%20SOC-1E90FF)](#)
[![Tool](https://img.shields.io/badge/SIEM-Wazuh-red)](#)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen)](#)

**Author:** Duaa Bint E Adnan

---

## 📖 Overview

This repository documents my work as a **Blue Team Intern** at **ITSimplera Institute**, undertaken as part of a hands-on Security Operations Center (SOC) internship program. The goal of the internship is to build practical, industry-relevant skills in defensive cybersecurity by working directly with the tools and workflows used in real-world SOC environments.

This README covers **Week 1**, in which I deployed and configured a fully functional SIEM environment using **Wazuh**, connected endpoint agents, and validated security alerting through File Integrity Monitoring (FIM).

---

## 🏢 About the Internship

**ITSimplera Institute** runs a structured, project-based internship program designed to simulate the day-to-day responsibilities of a SOC analyst. Interns are evaluated across four dimensions each week:

| Component | Description | Weight |
|---|---|---|
| 📄 Documentation | Step-by-step write-up with screenshots and technical explanations | 10% |
| 💼 LinkedIn Submission | A professional post summarizing the project and its outcomes | 50% |
| 💻 GitHub Repository | A well-documented repository showcasing the implementation | 10% |
| 🎤 Technical Interview | A live evaluation of understanding, implementation, and problem-solving | 30% |

---

## 🎯 Week 1 — Task Brief

| Detail | Info |
|---|---|
| **Task Type** | Setup + Exploration |
| **Difficulty** | Beginner |
| **Released** | June 27, 2026 |
| **Deadline** | July 4, 2026 |
| **Role** | Blue Team Intern |

### Objective
Deploy and configure the **Wazuh SIEM** platform to establish a centralized security monitoring environment, connect endpoints via the Wazuh Agent, configure **File Integrity Monitoring (FIM)**, and validate that security alerts are generated and captured correctly — laying the foundation for future Blue Team operations.

---

## 🔧 What I Implemented

- ✅ Deployed the **Wazuh Virtual Appliance** and configured the **Wazuh Manager**
- ✅ Installed and registered the **Wazuh Agent on a Windows endpoint**
- ✅ Installed and registered the **Wazuh Agent on a Linux endpoint**
- ✅ Configured **File Integrity Monitoring (FIM)** to track file/directory changes in real time
- ✅ Simulated file-level changes to **trigger and validate security alerts**
- ✅ Verified end-to-end alert flow on the **Wazuh Dashboard**
- ✅ Documented every step of the deployment process with supporting screenshots

---

## 🖥️ Tools & Technologies

- **Wazuh** (Manager, Agent, and Dashboard)
- **VirtualBox / Virtual Appliance** for the Wazuh server
- **Windows** endpoint (agent installation & registration)
- **Linux (Ubuntu)** endpoint (agent installation & registration)
- **File Integrity Monitoring (FIM)** module
- Command-line administration for agent configuration and registration

---

## 🧠 Skills Gained

- Hands-on understanding of **SIEM architecture** and centralized log management
- Practical experience deploying and hardening a security monitoring stack from scratch
- Configuring **File Integrity Monitoring** to detect unauthorized or unexpected file changes
- Reading, interpreting, and validating **security alerts** the way a SOC analyst would
- Cross-platform endpoint management (Windows + Linux) within a single SIEM pane
- Structuring technical work into clear, professional documentation for stakeholders

---

## 📂 Repository Contents

```
IT Simplera Screenshots/
├── Week 1 Task for SOC Interns.pdf     # Official task brief
├── Screenshot 2026-06-25 ...           # Wazuh appliance deployment
├── Screenshot 2026-06-26 ...           # Wazuh Manager configuration
├── Screenshot 2026-06-28 ...           # Agent installation, FIM setup & alert validation
├── Screenshot 2026-06-29 ...           # Final dashboard verification
└── WhatsApp Image ...                  # Mentor/cohort discussions & task coordination
```

Each screenshot corresponds to a discrete stage of the deployment — from spinning up the Wazuh appliance, through agent registration on both operating systems, to the final alert generated and captured after a monitored file was modified.

---

## 🚀 Outcome

By the end of Week 1, I had a fully operational SIEM pipeline: endpoints reporting into a central Wazuh Manager, File Integrity Monitoring actively watching designated paths, and verified alerts flowing through to the dashboard in real time — the essential building block for every SOC workflow that follows.

---

## 🔗 Submissions

- 📄 **Documentation:** included in this repository
- 💼 **LinkedIn Post:** *[link here]*
- 💻 **GitHub Repository:** *this repository*

---

<p align="center"><i>Part of my ongoing journey into Blue Team & SOC operations — building this repository one task at a time.</i></p>

<p align="center"><b>Duaa Bint E Adnan</b> · Blue Team Intern @ ITSimplera Institute</p>
