# Domain 2: Information Security Risk Management (20%)

## A. Information security risk assessment

### Emerging risk and threat landscape

- **Threats:** natural, human (intentional or accidental), technical, environmental.
- **Threat sources:** nation-states, organized crime, hacktivists, insiders, third parties.
- **Emerging risks:**
  - AI-enabled attacks
  - ransomware
  - supply chain compromise
  - cloud misconfiguration
  - IoT/OT exposure
  - quantum computing's impact on cryptography
- **Threat intelligence:** strategic, operational and tactical. Feeds risk assessments.

### Vulnerability and control deficiency analysis

- **Vulnerability:** a weakness that a threat can exploit.
- **Sources:** vulnerability scans, penetration tests, audits, control self-assessments, incident data.
- **Control deficiency:** a missing or ineffective control. Identified through **gap analysis** and **control testing.**

### Risk assessment and analysis

- **Risk** = likelihood × impact of a threat exploiting a vulnerability.
- **Risk management process:**
  1. Establish **context** (scope, criteria, risk appetite).
  2. **Identify** risks.
  3. **Analyze** risks.
  4. **Evaluate** risks against appetite and tolerance.
  5. **Treat** risks.
  6. **Monitor and review.**
  7. **Communicate and consult.**
- **Analysis approaches:**
  - **Qualitative:** high/medium/low; fast; subjective.
  - **Semi-quantitative:** numeric scales.
  - **Quantitative:** monetary values.
    - **SLE** = AV × EF.
    - **ALE** = SLE × ARO.
- **Asset identification and valuation:** based on business value and impact, not just replacement cost.
- **Business impact analysis (BIA):** identifies critical processes and the impact of disruption over time. Drives RTO, RPO and recovery priorities.
- **Frameworks:**
  - **ISO/IEC 27005** (information security risk)
  - **ISO 31000** (enterprise risk)
  - **NIST SP 800-30** (risk assessments)
  - **NIST RMF (SP 800-37)**
  - **COBIT 2019** / **Risk IT**
  - **FAIR** (quantitative risk analysis)
- **Risk scenarios:** realistic descriptions of how a risk could happen; useful for communicating with executives.
- **Inherent risk** (before controls) vs **residual risk** (after controls).

> **Exam tip:** Risk assessments should be **ongoing**, and repeated after significant changes such as new systems, mergers, new regulations or major incidents.

## B. Information security risk response

### Risk treatment / risk response options

| Option | Meaning | Example |
|--------|---------|---------|
| **Mitigate (reduce)** | Implement controls to lower likelihood or impact | MFA, encryption, patching |
| **Transfer (share)** | Shift financial impact to another party | Cyber insurance, outsourcing |
| **Avoid** | Stop the activity causing the risk | Not launching a risky product |
| **Accept** | Knowingly retain the risk | Within appetite; documented and approved by the risk owner |

- **Accountability can't be transferred.** The organization still owns the risk even when it's insured or outsourced.
- Risk acceptance must be **formal**, **documented** and approved by the right **risk owner**, with periodic review.
- **Cost-benefit analysis:** a control's cost shouldn't exceed the value of the risk reduction.

### Risk and control ownership

- **Risk owner:** the business manager accountable for a risk and its treatment.
- **Control owner:** responsible for operating a specific control.
- The **information security manager** facilitates and advises; doesn't own business risk.

### Risk monitoring and reporting

- **Risk register:** records risks, owners, ratings, treatment plans, status.
- **Key risk indicators (KRIs):** early warning metrics, e.g., number of unpatched critical systems.
- **Reporting:** tailored to the audience. Boards want business impact and trends; technical teams want details.
- **Continuous monitoring:** risks change, so reassess regularly.
- **Risk heat maps** for executive communication.

> **Exam tip:** When a risk exceeds appetite, the security manager's job is to **present options and their costs to the risk owner/management** for a decision, not to decide alone.

## Key terms

| Term | Definition |
|------|-----------|
| Threat / vulnerability / risk | Potential harm / weakness / likelihood × impact |
| Control deficiency | Missing or ineffective control |
| Qualitative / quantitative analysis | Ratings-based / money-based |
| SLE / ALE | AV × EF / SLE × ARO |
| BIA | Business impact analysis |
| FAIR | Factor Analysis of Information Risk (quantitative model) |
| Inherent / residual risk | Before / after controls |
| Mitigate / transfer / avoid / accept | Risk treatment options |
| Risk owner | Business manager accountable for a risk |
| Risk register | Central record of risks and treatment |
| KRI | Key risk indicator (early warning) |
| Risk appetite / tolerance | Amount accepted / acceptable variation |

## Questions to review

1. What determines whether a risk needs treatment?
2. Who should formally accept a residual risk?
3. A company buys cyber insurance. Which risk response is this, and does it remove accountability?
4. What's the main output of a BIA?
5. When should a risk assessment be repeated?
6. Which metric gives early warning that risk is increasing?
7. A control would cost $80,000 a year to reduce an ALE of $50,000. What should the security manager recommend?
8. What's the best way to present risk to the board?

<details>
<summary>Show answers</summary>

1. Whether it **exceeds the organization's risk appetite/tolerance.**
2. The **risk owner** (business owner / senior management).
3. **Transfer**; **no**, accountability stays with the organization.
4. The **impact of disruption on critical processes over time**, which drives recovery priorities (RTO/RPO).
5. **Regularly, and after significant changes** (new systems, regulations, incidents, mergers).
6. A **key risk indicator (KRI).**
7. The control **isn't cost-justified**; consider cheaper alternatives or present acceptance/transfer options to the risk owner.
8. In **business terms**, such as impact, trends, and risk against appetite, using risk scenarios or heat maps.

</details>
