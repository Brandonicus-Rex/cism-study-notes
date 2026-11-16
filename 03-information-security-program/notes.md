# Domain 3: Information Security Program (33%)

## A. Information security program development

### Information security architecture (new in the 2026 outline)

- **Security architecture:** the design of security controls and how they fit together across the enterprise.
- Must align with **enterprise architecture** and business requirements.
- **Principles:**
  - defense in depth
  - least privilege
  - Zero Trust
  - secure by design
  - segmentation
  - resilience
- **Reference architectures and frameworks:** SABSA, NIST Zero Trust Architecture (SP 800-207), cloud security reference architectures.
- Architecture decisions should be **risk-based** and support business agility.

### Program resources

- **People:** roles, skills, staffing, training, outsourcing.
- **Processes:** policies, standards, procedures.
- **Technology:** security tools and platforms.
- **Budget:** justified through business cases and aligned with risk priorities.
- **Program charter:** establishes the program's authority, scope and responsibilities, approved by senior management.

### Information asset identification and classification

- **Asset inventory:** hardware, software, data, people, processes, third-party services.
- **Classification:** by sensitivity and criticality, set by the **data owner.**
- **Valuation:** based on business impact.
- Classification drives the level of protection, handling, retention and destruction requirements.

### Control design and selection

- **Control categories:** administrative, technical, physical.
- **Control types:** preventive, detective, corrective, deterrent, compensating, recovery.
- **Selection factors:**
  - risk reduction
  - cost-effectiveness
  - business impact
  - regulatory needs
  - integration with existing controls
- **Control frameworks:** ISO 27002, NIST SP 800-53, CIS Controls, COBIT.
- **Baselines:** minimum security configurations, e.g., CIS Benchmarks.
- **Compensating controls:** used when a primary control isn't feasible.

> **Exam tip:** Controls should be chosen based on **risk and business requirements**, not because a technology is popular. The most cost-effective control that brings risk within appetite is usually the best answer.

## B. Information security program management

### Control implementation and integration

- **Integration:** embed security into business processes, the SDLC, procurement, change management and HR.
- **Security in the SDLC:** requirements, design reviews, secure coding, testing, approval before production.
- **Change management:** security reviews changes for risk impact.
- **Configuration management:** secure baselines, drift detection.
- **Identity and access management:** provisioning, access reviews, privileged access management.
- **Cloud security:** shared responsibility model, CSPM, contracts.

### Control testing and evaluation

- **Methods:**
  - **control self-assessments (CSA)**
  - **vulnerability assessments**
  - **penetration tests**
  - **internal audits**
  - **external audits**
  - **continuous control monitoring**
- **Effectiveness vs efficiency:** does the control work, and is it cost-effective?
- **Metrics:** KPIs (program performance), KRIs (risk trends), KGIs (goal achievement).
- **Security program maturity:** CMMI-style assessments to show improvement over time.
- **Audit findings:** the security manager coordinates remediation with control owners and tracks closure.

### Information security awareness and training

- **Awareness:** everyone; recognize and report threats.
- **Training:** role-specific skills, e.g., developers, admins.
- **Education:** deeper professional development.
- **Methods:** onboarding, annual refreshers, phishing simulations, microlearning, security champions.
- **Measure effectiveness:** phishing click and report rates, incident reports, quiz results, behavior change.
- Tailor content to the audience and refresh it as threats change.

### Management of external services

- **Third-party risk management (TPRM):**
  1. **Due diligence** before onboarding: questionnaires, SOC 2 reports, certifications, financial stability.
  2. **Contract requirements:**
     - security requirements
     - **right to audit**
     - breach notification
     - data handling and return/destruction
     - SLAs
     - subcontractor terms
  3. **Ongoing monitoring:** periodic assessments, performance against SLAs.
  4. **Offboarding:** revoke access, retrieve or destroy data.
- **Cloud providers:** shared responsibility; review SOC reports and certifications (ISO 27001, FedRAMP).
- **Fourth-party risk:** your vendor's vendors.
- **Accountability for protecting data stays with the organization**, even when outsourced.

> **Exam tip:** The best time to add security requirements for a vendor is **before signing the contract.** After signing, you lose leverage.

## Key terms

| Term | Definition |
|------|-----------|
| Security architecture | Design of how security controls fit together |
| Zero Trust architecture | Never trust, always verify (NIST SP 800-207) |
| Program charter | Document establishing the program's authority |
| Asset classification | Labeling assets by sensitivity and criticality |
| Control baseline | Minimum required security configuration |
| Compensating control | Alternative when the primary control isn't feasible |
| Control self-assessment | Control owners evaluate their own controls |
| KPI / KRI / KGI | Performance / risk / goal indicators |
| Security champion | Employee who promotes security within a team |
| TPRM | Third-party risk management |
| Right to audit | Contract clause allowing vendor audits |
| Fourth-party risk | Risk from your vendor's suppliers |

## Questions to review

1. What document gives the security program its authority?
2. Who determines an information asset's classification?
3. What's the main factor when selecting a security control?
4. When should security be integrated into a new application project?
5. Which assessment method has control owners evaluate their own controls?
6. What's a good measure of whether awareness training is working?
7. When is the best time to define security requirements for a new vendor?
8. A cloud provider suffers a breach of your customer data. Who is accountable to your customers?

<details>
<summary>Show answers</summary>

1. The **program charter** (approved by senior management).
2. The **data/information owner.**
3. **Risk reduction relative to cost**, aligned with business requirements.
4. **At the start**, during requirements and design.
5. A **control self-assessment (CSA).**
6. **Behavior change**, such as lower phishing click rates and higher reporting rates.
7. **Before the contract is signed** (during due diligence and negotiation).
8. **Your organization** (accountability can't be outsourced).

</details>
