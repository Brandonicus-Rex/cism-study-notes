# Domain 4: Incident Management (29%)

## A. Incident management readiness

### Incident response plan (IRP)

- **Incident management:** the overall capability (people, process, technology) to detect, respond to and recover from incidents. **Incident response** is the operational part.
- **IRP contents:**
  - purpose and scope
  - definitions and **severity/classification** criteria
  - roles and responsibilities
  - escalation paths
  - communication plans
  - procedures/playbooks
  - legal and regulatory reporting requirements
- **Incident response team:** a CSIRT/CIRT with members from security, IT, legal, HR, communications/PR and business units.
- **Senior management** approves the IRP and supports it with resources.
- **Playbooks/runbooks:** step-by-step responses to specific incident types, such as ransomware, data breach or DDoS.
- **Communication:** internal, external, customers, regulators, law enforcement and media. Use pre-approved templates and a **single spokesperson.**

### Business impact analysis (BIA)

- Identifies **critical business processes**, their dependencies, and the impact of disruption over time.
- **Outputs:**
  - **MTD / MTPD:** maximum tolerable downtime / period of disruption.
  - **RTO:** time to restore.
  - **RPO:** acceptable data loss.
  - **Recovery priorities.**
- The BIA is the **foundation** for BCP and DRP.

### Business continuity plan (BCP)

- Keeps **critical business functions** running during and after a disruption.
- Covers people, facilities, processes, suppliers and communications.
- **Business continuity** is broader than IT recovery.

### Disaster recovery plan (DRP)

- Restores **IT systems and data** after a disruption.
- **Recovery sites:**
  - **Hot:** ready within hours.
  - **Warm:** ready in days.
  - **Cold:** space only.
  - **Mobile.**
  - **Reciprocal.**
  - **Cloud.**
- **Backups and replication** sized to the RPO; recovery capability sized to the RTO.
- **Testing**, from least to most disruptive:
  1. checklist review
  2. tabletop/walkthrough
  3. simulation
  4. parallel
  5. full interruption

> **Exam tip:** **BIA comes first.** It drives the BCP and DRP by identifying what's critical and how quickly it must be restored.

### Readiness: tools, training, and testing

- **Detection capability:** SIEM, EDR/XDR, IDS/IPS, log management, threat intelligence.
- **Training and exercises:** tabletop exercises with executives, technical drills, purple teaming.
- **Insurance:** cyber insurance terms can affect response, such as approved vendors and notification requirements.
- **Retainers:** pre-arranged forensic and IR firms, legal counsel.
- Update the plan after tests, incidents and major changes.

## B. Incident management operations

### Incident management tools and techniques

- **Event vs incident:** an **event** is any observable occurrence. An **incident** is an event that harms or threatens the organization's information assets or operations.
- **Triage:** confirm, classify, prioritize by business impact and severity.
- **Tools:**
  - SIEM
  - SOAR (automation/orchestration)
  - EDR
  - forensic tools
  - ticketing systems
  - threat intelligence platforms

### Incident investigation and evaluation

- **Response phases** (NIST SP 800-61 style):
  1. **Preparation.**
  2. **Detection and analysis.**
  3. **Containment, eradication and recovery.**
  4. **Post-incident activity.**
- **Evidence handling:**
  - **chain of custody**
  - **order of volatility**
  - forensic imaging
  - hashing
  - legal hold
- **Escalation:** defined by severity; notify senior management for significant incidents.
- **Legal and regulatory notifications:**
  - **GDPR:** 72 hours to the supervisory authority.
  - Sector rules such as HIPAA and SEC disclosure rules.
  - Contractual notification obligations.
- Involve **legal counsel** early, especially for possible breaches.

### Incident containment methods

- **Short-term containment:** isolate affected systems, block malicious IPs, disable compromised accounts.
- **Long-term containment:** temporary fixes while preparing a clean rebuild.
- Consider **business impact** of containment, e.g., taking a revenue system offline, and **evidence preservation.**
- **Eradication:** remove malware, close vulnerabilities, reset credentials.
- **Recovery:** restore from clean backups, monitor closely, return to normal operations in stages.

> **Exam tip:** After detection and confirmation, the **first priority is containment**, to limit damage. Eradication and recovery follow.

### Incident response communications

- Stick to the communication plan: who says what, to whom and when.
- Keep executives informed in business terms.
- Coordinate external messaging through legal and PR.

### Post-incident review practices

- **Lessons learned meeting:** soon after the incident, with all stakeholders.
- **Root cause analysis:** why it happened, not just what happened.
- **Outputs:**
  - updated IRP and playbooks
  - new controls
  - training needs
  - metrics
- **Metrics:**
  - **MTTD:** mean time to detect.
  - **MTTR:** mean time to respond or recover.
  - **Dwell time.**
  - Number of incidents by type and severity.
- Report results to senior management and feed findings into **risk management.**

> **Exam tip:** The main purpose of a post-incident review is to **improve** the response process and prevent recurrence, not to assign blame.

## Key terms

| Term | Definition |
|------|-----------|
| Incident management / response | Overall capability / operational response |
| IRP | Incident response plan |
| CSIRT | Computer security incident response team |
| Playbook | Step-by-step guide for a specific incident type |
| BIA | Identifies critical processes and impact over time |
| MTD / RTO / RPO | Max downtime / time to restore / acceptable data loss |
| BCP / DRP | Business continuity / IT disaster recovery |
| Event / incident | Any occurrence / harmful or threatening event |
| Triage | Classifying and prioritizing incidents |
| Chain of custody | Record of evidence handling |
| Containment / eradication / recovery | Limit / remove / restore |
| Root cause analysis | Finding why an incident occurred |
| MTTD / MTTR | Mean time to detect / respond or recover |

## Questions to review

1. What should be completed first to support BCP and DRP development?
2. Who should approve the incident response plan?
3. What's the difference between an event and an incident?
4. After confirming an incident, what's the first priority?
5. When should legal counsel be involved in a possible data breach?
6. What is the main goal of a post-incident review?
7. RTO must be shorter than or equal to what?
8. Which DR test is the most realistic but also the most disruptive?

<details>
<summary>Show answers</summary>

1. The **business impact analysis (BIA).**
2. **Senior management.**
3. An **event** is any observable occurrence; an **incident** harms or threatens the organization.
4. **Containment.**
5. **Early**, as soon as a breach is suspected.
6. To **improve the response process and prevent recurrence** (lessons learned, root cause).
7. The **MTD** (maximum tolerable downtime).
8. A **full interruption** test.

</details>
