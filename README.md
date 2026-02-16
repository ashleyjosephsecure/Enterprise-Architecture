# Milot Motors: Enterprise Architecture 🏎️🛡️

**Executive Architect:** Seth Milot  
**Framework:** NIST Risk Management Framework (RMF)  
**Industry:** Luxury Automotive & Secure Logistics

---

## 🏛️ Phase 1: Categorization (High-to-Low)
*Identifying the "Crown Jewels" of the Milot Motors Ecosystem.*

| Asset | Security Impact | Rationale |
| :--- | :--- | :--- |
| **Stakeholder & Customer PII** | 🔴 HIGH | HIPAA/GDPR Compliance & Brand Trust. |
| **Proprietary Code (Balune/ERP)** | 🔴 HIGH | Intellectual Property & Core Business Logic. |
| **Vehicle Telemetry & GPS** | 🟡 MODERATE | Operational safety and anti-theft logistics. |
| **Public Showroom Website** | 🟢 LOW | Informational only; non-critical to operations. |

---

## 🛠️ Phase 3: Control Selection (The "Locks")
*Choosing NIST 800-53 controls to mitigate identified risks.*

* **AC-2 (Account Management):** Centralized IAM for HHA/Lab/Corporate divisions.
* **IA-2 (MFA):** Mandatory Hardware/Biometric authentication for all Admin levels.
* **SC-28 (Encryption at Rest):** AES-256 standards for all customer and stakeholder data.
* **PE-3 (Physical Access):** Biometric hardening of Showrooms and server rooms.

---

## 🚀 Phase 4: Implementation (The Build)
*Translating policy into technical and physical reality.*

### 🖥️ Software Layer
* **Identity:** Integration of **Auth0** for secure, multi-tenant employee login.
* **Encryption:** Implementation of **AWS KMS** for automated key rotation for the Balune database.

### 🏢 Physical Layer
* **Access Control:** Installation of **HID Signo Biometric Readers** at HQ and Lab entrances.
* **Surveillance:** Deployment of AI-driven CCTV that triggers SOC alerts for after-hours breaches (e.g., Post-8PM M-Th).

### 🚛 Logistics Layer
* **Communication:** End-to-end TLS 1.3 encryption for all vehicle-to-cloud telemetry.

---
*Status: 🟠 Moving to Phase 5: Assessment & Audit Verification.*
