# Milot Motors: Enterprise Architecture 🏎️🛡️

## Executive Overview
This project serves as the Master Security Blueprint for the Milot Motors ecosystem. It applies the **NIST Risk Management Framework (RMF)** to a multi-dimensional luxury brand, ensuring that every business component—from physical showrooms to proprietary software—is "Secure by Design."

## Project Status: 🟠 Phase 1 (Categorization)
*Currently aligning business assets with NIST SP 800-60 standards.*

## Framework Roadmap
1. **Prepare:** Organization-level security readiness.
2. **Categorize:** [IN PROGRESS] Defining high-impact data and assets.
3. **Select:** Choosing baseline security controls (MFA, Encryption, Biometrics).
4. **Implement:** Documenting the deployment of software and physical locks.
5. **Assess:** Verifying if controls work as intended.
6. **Authorize:** Executive risk acceptance.
7. **Monitor:** Continuous SOC oversight.



# RMF Step 1: Asset Categorization

According to **FIPS 199**, we categorize Milot Motors assets based on the impact to the business if Confidentiality, Integrity, or Availability is lost.

### 🔴 High Impact (The Crown Jewels)
* **Stakeholder PII:** Customer financial data and executive contracts.
* **Proprietary Code:** The "Balune" engine and Milot Motors ERP source code.
* **Encryption Keys:** Digital keys used to secure the vehicle network.

### 🟡 Moderate Impact (Operational Assets)
* **Logistics & Inventory:** Real-time location of vehicles and supply chain parts.
* **Internal Communication:** Employee email and project management platforms.

### 🟢 Low Impact (Public Assets)
* **Public Website:** Marketing materials and showroom hours.
