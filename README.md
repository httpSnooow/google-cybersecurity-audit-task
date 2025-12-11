# Botium Toys: Internal Security Audit 🛡️

![Status](https://img.shields.io/badge/Status-Completed-success)
![Security Audit](https://img.shields.io/badge/Focus-Security%20Audit-red)
![Framework](https://img.shields.io/badge/Framework-NIST%20CSF-blue)

## 📄 Project Overview
This project is part of the **Google Cybersecurity Professional Certificate**. 

**Scenario:** Botium Toys is a small U.S. business that sells toys and has a growing online presence. As an IT Associate, I conducted an internal security audit to assess the company's security posture. The goal was to identify risks, evaluate current controls, and ensure compliance with regulations like **PCI DSS**, **GDPR**, and **SOC**.

---

## 🔍 Scope and Goals

* **Scope:** The audit covers the entire security program at Botium Toys, including assets (employee equipment, internal network, systems), controls, and compliance practices.
* **Goals:** Assess existing assets, complete a controls and compliance checklist, and identify gaps to improve the security posture.

---

## ⚠️ Risk Assessment
**Current Risk Score:** **8/10 (High)**

The risk score is high due to a lack of controls and adherence to compliance best practices.
* **Critical Issue:** All employees currently have access to internally stored data (including cardholder data and PII).
* **Critical Issue:** Encryption is not used for data stored locally.

---

## 🛠️ Controls Assessment Checklist

| Control | Status |
| :--- | :---: |
| **Least Privilege** | ❌ No |
| **Disaster Recovery Plans** | ❌ No |
| **Password Policies** | ⚠️ Partial |
| **Separation of Duties** | ❌ No |
| **Firewall** | ✅ Yes |
| **Intrusion Detection System (IDS)** | ❌ No |
| **Backups** | ❌ No |
| **Antivirus Software** | ✅ Yes |
| **Legacy System Maintenance** | ⚠️ Partial |
| **Encryption** | ❌ No |
| **Password Management System** | ❌ No |
| **Physical Locks** | ✅ Yes |
| **CCTV Surveillance** | ✅ Yes |
| **Fire Detection** | ✅ Yes |

---

## ⚖️ Compliance Checklist

### Payment Card Industry Data Security Standard (PCI DSS)
| Best Practice | Status |
| :--- | :---: |
| Authorized Access Only | ❌ No |
| Secure Storage/Transmission | ❌ No |
| Data Encryption | ❌ No |
| Secure Password Policies | ❌ No |

### General Data Protection Regulation (GDPR)
| Best Practice | Status |
| :--- | :---: |
| E.U. Data Privacy | ❌ No |
| 72h Breach Notification | ✅ Yes |
| Data Classification | ❌ No |
| Privacy Policies | ✅ Yes |

### System and Organizations Controls (SOC)
| Best Practice | Status |
| :--- | :---: |
| User Access Policies | ❌ No |
| Sensitive Data Confidentiality | ❌ No |
| Data Integrity | ✅ Yes |
| Data Availability | ✅ Yes |

---

## 🚀 Recommendations

Based on the audit findings, the following controls must be prioritized to reduce risk:

1.  **Implement Access Controls:** Enforce **Least Privilege** and **Separation of Duties** to restrict access to sensitive data (PCI DSS requirement).
2.  **Deploy Encryption:** Implement encryption for customer credit card data and PII to ensure confidentiality (PCI DSS & GDPR requirement).
3.  **Disaster Recovery & Backups:** Create a plan and regular backup schedule to ensure business continuity.
4.  **Password Management:** Adopt a centralized password management system and enforce strong password complexity rules.
5.  **IDS Implementation:** Install an Intrusion Detection System to monitor for malicious activity.

---
*Disclaimer: This is a fictional case study completed for educational purposes.*
