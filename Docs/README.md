# Ransomware Simulation & Recovery Strategies for Small Businesses

## Project Overview

This cybersecurity capstone project investigates ransomware recovery strategies for small businesses using a controlled virtual lab environment. The project evaluates the effectiveness of three backup and recovery tools — Restic, Duplicati, and UrBackup — against a simulated ransomware attack.

The objective of the project is to identify cost-effective and reliable backup solutions that improve cyber resilience, reduce downtime, and support business continuity for small and medium-sized businesses (SMBs).

---

# Project Objectives

* Simulate a ransomware attack in a safe virtual environment
* Configure and evaluate backup and recovery systems
* Measure recovery performance using RTO and integrity validation
* Compare Restic, Duplicati, and UrBackup
* Analyse recovery speed and recovery success rates
* Demonstrate Agile project management using Jira and GitHub

---

# Technologies & Tools Used

## Virtualization & Infrastructure

* Windows 10 Virtual Machine
* Ubuntu Backup Server
* Oracle VirtualBox

## Backup & Recovery Tools

* Restic
* Duplicati
* UrBackup

## Cybersecurity & Testing

* PowerShell ransomware simulation
* SHA256 integrity validation

## Project Management & Collaboration

* Jira Software
* GitHub

## Data Analysis & Reporting

* Python (Matplotlib)
* Microsoft Excel
* Microsoft PowerPoint
* Canva

---

# System Architecture

```text
Windows VM (Victim)
        ↓
Ransomware Simulation
        ↓
Shared Network Folder
        ↓
Ubuntu Backup Server
   ↙        ↓         ↘
Restic   Duplicati   UrBackup
        ↓
Recovery Validation
        ↓
SHA256 Integrity Check
```

---

# Key Findings

| Metric                | Result |
| --------------------- | ------ |
| Recovery Success Rate | 100%   |
| Data Loss             | 0%     |
| Fastest Recovery Tool | Restic |
| Integrity Validation  | Passed |
| Files Restored        | 75+    |

---

# Features of the Project

Ransomware attack simulation
Recovery testing and validation
Recovery dashboard metrics
Agile sprint tracking using Jira
GitHub version control workflow
SHA256 integrity verification
Visual dashboards and graphs
Professional documentation and presentation materials

---

# Repository Structure

```text
cybersecurity-backup-recovery-lab/
│
├── docs/
├── diagrams/
├── screenshots/
├── graphs/
├── jira/
├── presentation/
├── scripts/
└── README.md
```

---

# Folder Descriptions

| Folder       | Description                                   |
| ------------ | --------------------------------------------- |
| docs         | Final reports and documentation               |
| diagrams     | Architecture diagrams and workflows           |
| screenshots  | Recovery testing evidence                     |
| graphs       | Performance charts and dashboards             |
| jira         | Jira sprint updates and dashboard screenshots |
| presentation | Final PowerPoint presentation                 |
| scripts      | PowerShell ransomware simulation scripts      |

---

# Agile Workflow

The project followed an Agile Scrum methodology using Jira and GitHub integration.

Workflow:

```text
Backlog → Sprint Planning → Development → Testing → Review → Documentation → Submission
```

GitHub branches were linked directly to Jira sprint issues to support professional DevOps workflow management.

---

# Team Members

| Team Member   | Role                                                |
| ------------- | --------------------------------------------------- |
| Maureen Gitau | Documentation, Analysis & Project Coordination Lead |
| Ajit Subedi   | Implementation & Deployment Lead                    |
| Raju Shrestha | Threat Modelling & Security Testing Lead            |
| Jiwan Kandel  | Backup Infrastructure & Recovery Systems Lead       |

---

# Supervisor

Associate Professor John Ayoade

---

# Project Highlights

* Recovery Time Dashboard
* Before vs After Ransomware Attack Visual
* Jira + GitHub Workflow Integration
* Backup Validation Framework
* Recovery Testing Evidence
* Comparative Tool Analysis

---

# References

Atlassian. (2026). Jira software. https://www.atlassian.com/software/jira

GitHub Inc. (2026). GitHub. https://github.com/

Restic Contributors. (2026). Restic backup program. https://restic.net/

Duplicati Team. (2026). Duplicati backup software. https://www.duplicati.com/

UrBackup. (2026). UrBackup client/server backup system. https://www.urbackup.org/

---

# Project Outcome

This project successfully demonstrated that open-source backup and recovery solutions can provide effective ransomware recovery for small businesses when combined with structured backup strategies, recovery validation, and Agile project management practices.

