# 📋 ISO 27001 Control Mapping Toolkit

**A practical framework for mapping controls, assets, and processes to ISO/IEC 27001:2022 standards**

![Version](https://img.shields.io/badge/version-1.0-blue)
![Standards](https://img.shields.io/badge/standard-ISO%2027001%3A2022-green)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 🎯 Overview

The **ISO 27001 Control Mapping Toolkit** is a professional-grade resource designed to simplify the complex process of aligning organizational security controls with the **ISO/IEC 27001:2022** standard. This toolkit provides the templates and methodology needed to build a robust **Statement of Applicability (SoA)**, map Annex A controls to business assets, and prepare for certification audits.

**Designed for:**
- 🔐 Information Security Managers
- 📊 Compliance Analysts
- 📝 IT Auditors
- 🏢 Organizations seeking ISO 27001 certification

---

## 💼 Business Value

| Outcome | Benefit |
|---------|----------|
| **Certification Readiness** | Accelerate your path to ISO 27001:2022 certification with pre-structured templates |
| **Control Gap Analysis** | Identify exactly where your current security posture falls short of the standard |
| **Resource Efficiency** | Reduce documentation time by 40-60% using standardized mapping models |
| **Asset-Based Protection** | Ensure critical business assets are mapped to specific security controls |
| **Audit Confidence** | Provide clear, evidence-linked documentation to external auditors |

---

## ⭐ Key Features

✅ **ISO 27001:2022 Annex A Mapping** – Complete list of all 93 controls across 4 themes  
✅ **Statement of Applicability (SoA) Template** – Professional Excel template with justification fields  
✅ **Asset-to-Control Matrix** – Link your hardware, software, and data to required controls  
✅ **Theme-Based Organization** – Controls grouped by Organizational, People, Physical, and Technological themes  
✅ **Implementation Guidance** – Step-by-step instructions for each control objective  
✅ **Evidence Checklist** – Recommended evidence types for each Annex A control  
✅ **Maturity Scoring** – Assess control implementation level (0-5 scale)  

---

## 📦 Repository Structure

```
ISO27001-Control-Mapping-Toolkit/
│
├── README.md                                    ← This file
│
├── Templates/
│   ├── Statement-of-Applicability-Master.xlsx   ← Core SoA document
│   ├── Asset-Control-Mapping-Matrix.xlsx        ← Link assets to controls
│   ├── Control-Gap-Analysis-Template.xlsx       ← Identify missing controls
│   └── Implementation-Roadmap-Plan.xlsx         ← Project plan for certification
│
├── Documentation/
│   ├── ISO27001-2022-Transition-Guide.md        ← Changes from 2013 to 2022
│   ├── Annex-A-Control-Descriptions.md          ← Detailed control explanations
│   ├── Evidence-Collection-Best-Practices.md    ← How to gather audit evidence
│   └── SoA-Development-Methodology.md           ← Step-by-step SoA guide
│
├── Examples/
│   ├── SaaS-Company-Sample-SoA.xlsx             ← Real-world SoA example
│   ├── IT-Service-Provider-Mapping.xlsx         ← Industry-specific sample
│   └── Audit-Evidence-Sample-Package/           ← Folder of sample evidence docs
│
└── Tools/
    ├── control_maturity_calculator.py           ← Auto-calculate maturity scores
    └── gap_analysis_reporter.py                 ← Generate gap reports
```

---

## 📊 Control Themes (ISO 27001:2022)

The 2022 version of the standard organizes 93 controls into 4 main themes:

| Theme | Controls | Focus Area |
|-------|----------|------------|
| **5. Organizational** | 37 Controls | Policies, roles, external parties, asset management |
| **6. People** | 8 Controls | Remote working, screening, confidentiality, training |
| **7. Physical** | 14 Controls | Physical security, monitoring, maintenance, disposal |
| **8. Technological** | 34 Controls | Authentication, encryption, logging, network security |

---

## 🚀 Getting Started

### Quick Start (30 minutes)

1. **Download** `Statement-of-Applicability-Master.xlsx`
2. **Review** the list of 93 Annex A controls
3. **Determine Applicability** for each control based on your risk assessment
4. **Document Justification** for why a control is included or excluded
5. **Score Maturity** for currently implemented controls

### Full Certification Path (6-12 months)

1. **Month 1:** Define ISMS scope and conduct risk assessment
2. **Month 2-3:** Populate the SoA using this toolkit
3. **Month 4-6:** Implement missing controls and remediate gaps
4. **Month 7-9:** Collect evidence and perform internal audits
5. **Month 10-12:** External certification audit

---

## 📖 How to Use

### Step 1: Define Scope
Before mapping controls, clearly define the boundaries of your Information Security Management System (ISMS).

### Step 2: Conduct Risk Assessment
Identify risks to your information assets. This toolkit works best when integrated with the [Enterprise-Risk-Register-Framework](../Enterprise-Risk-Register-Framework).

### Step 3: Develop the Statement of Applicability (SoA)
- For each control in the SoA template:
  - Is it applicable? (Yes/No)
  - Why/Why not? (Justification)
  - Current status (Implemented/In Progress/Not Started)
  - Link to specific policy or procedure

### Step 4: Map Assets to Controls
Use the `Asset-Control-Mapping-Matrix.xlsx` to ensure every critical asset (Server, Database, Employee Data) is covered by appropriate Annex A controls.

### Step 5: Gather Evidence
Refer to `Evidence-Collection-Best-Practices.md` for a list of artifacts auditors typically look for, such as:
- Access logs
- Change management records
- Security training attendance
- Physical access records

---

## 🔧 Maturity Scoring Model

Use this model in the SoA to track your progress:

| Level | Name | Description |
|-------|------|-------------|
| **0** | **Non-Existent** | No control in place |
| **1** | **Initial** | Control exists but is undocumented and ad-hoc |
| **2** | **Repeatable** | Control is documented but not consistently followed |
| **3** | **Defined** | Control is fully documented and consistently followed |
| **4** | **Managed** | Control is measured and monitored for effectiveness |
| **5** | **Optimized** | Continuous improvement of the control based on data |

---

## 🤝 Contact & Support

**Author:** Rohith D  
**Role:** GRC Analyst | ISO 27001 Implementation Specialist  
**Email:** rohithd300900@gmail.com  
**LinkedIn:** [linkedin.com/in/rohith-d-a46aaa288](https://www.linkedin.com/in/rohith-d-a46aaa288/)

---

## 📜 License

This project is licensed under the MIT License - feel free to use and adapt.

---

**⭐ If this toolkit helped your certification journey, please star this repository!**

---

## 🎯 Related Toolkits

- [NIST-CSF-Implementation-Guide](../NIST-CSF-Implementation-Guide)
- [Enterprise-Risk-Register-Framework](../Enterprise-Risk-Register-Framework)
- [Compliance-Audit-Preparation-Toolkit](../Compliance-Audit-Preparation-Toolkit)
