# Third-Party Vendor Risk Assessment

## Overview

This project is a simulated Third-Party Risk Management (TPRM) assessment of CloudLedger Technologies Ltd., a fictional SaaS vendor being evaluated by Meridian Trust Bank plc.

CloudLedger provides a cloud-based loan origination and document management service that processes sensitive customer and financial information.

The assessment evaluates the vendor's security controls, operational resilience, data protection, compliance, fourth-party risk, and overall residual risk.

---

## Project Objective

The objective of this assessment is to determine whether the vendor's risk profile is acceptable under Meridian Trust Bank's third-party risk requirements and to provide a risk-based recommendation.

The assessment follows the TPRM lifecycle:

**Scope → Tier → Assess → Rate → Report → Monitor**

---

## Assessment Methodology

The vendor is assessed across multiple security and risk domains using four control verdicts:

| Verdict | Description |
|---|---|
| **Met** | The control exists and supporting evidence demonstrates that it operates effectively. |
| **Partially Met** | The control exists but has a weakness, limitation, or incomplete implementation. |
| **Not Met** | The control is absent or the vendor's claim is not supported by sufficient evidence. |
| **N/A** | The control genuinely does not apply. |

Risk findings are assessed using:

**Likelihood × Impact**

Risk ratings are categorized as:

- **Low:** 1–4
- **Medium:** 5–9
- **High:** 10–14
- **Critical:** 15–25

The assessment distinguishes between:

- **Inherent Risk** — risk before considering controls
- **Residual Risk** — risk remaining after considering controls

---

## Assessment Areas

The assessment covers the following domains:

1. Governance, Risk & Security Policy
2. Access Control & Identity
3. Data Protection & Encryption
4. Vulnerability & Patch Management
5. Secure Development & Change Management
6. Logging, Monitoring & Incident Response
7. Business Continuity, Disaster Recovery & Resilience
8. Fourth-Party / Subcontractor Management
9. Compliance, Certifications & Assurance
10. Physical & Personnel Security

---

## Project Structure

```text
Third-Party-Vendor-Risk-Assessment/
│
├── README.md
│
├── Original-Materials/
│   ├── Vendor_Risk_Assessment_Workbook.xlsx
│   └── Meridian_TPRM_Assessment_Pack.pdf
│
├── Completed-Assessment/
│   ├── Completed_Vendor_Risk_Assessment.xlsx
│   └── TPRM_Assessment_Report.pdf
│
├── Evidence/
│   ├── SOC2/
│   ├── Penetration-Test/
│   ├── DR-BCP/
│   └── Contract-DPA/
│
└── Risk-Analysis/
    └── Risk-Matrix.png
