# ISO/IEC 27001 Lead Auditor Training Course: The Complete Guide

## Module 4: Support and Operation of the ISMS

### Learning Objectives
By the end of this module, you will be able to:
1. Understand the requirements for providing resources, ensuring competence, and promoting awareness (Clauses 7.1, 7.2, 7.3).
2. Explain the requirements for managing documented information (Clause 7.5).
3. Describe how an organization must plan and control its operations to meet information security requirements (Clause 8.1).
4. Understand the requirements for executing information security risk assessments and risk treatment plans at planned intervals (Clauses 8.2 and 8.3).

### 4.1 Support (Clause 7)
Even the best-planned ISMS will fail if it is not supported by adequate resources, competent personnel, and clear communication. Clause 7 outlines the "enablers" of the ISMS.

#### 4.1.1 Resources (Clause 7.1)
The organization must determine and provide the resources needed for the establishment, implementation, maintenance, and continual improvement of the ISMS. This includes:
- Financial resources (budget for security tools, audits, training).
- Human resources (sufficient personnel to manage security operations).
- Infrastructure (secure facilities, hardware, software).

*Auditor Tip:* Look for evidence of resource constraints causing security failures, such as a backlog of unpatched critical vulnerabilities due to a lack of IT staff.

#### 4.1.2 Competence (Clause 7.2)
Information security relies heavily on the people managing it. The organization must:
- Determine the necessary competence of persons doing work under its control that affects its information security performance.
- Ensure these persons are competent on the basis of appropriate education, training, or experience.
- Where applicable, take actions to acquire the necessary competence (e.g., providing training or hiring consultants) and evaluate the effectiveness of those actions.
- Retain appropriate documented information as evidence of competence.

*Auditor Tip:* When interviewing a firewall administrator, an auditor will look for evidence of their competence (e.g., vendor certifications, training records, or demonstrable experience) to manage that specific technology securely.

#### 4.1.3 Awareness (Clause 7.3)
While only specific personnel need deep technical *competence*, everyone working under the organization's control needs security *awareness*. Persons doing work under the organization's control must be aware of:
- The information security policy.
- Their contribution to the effectiveness of the ISMS, including the benefits of improved information security performance.
- The implications of not conforming with the ISMS requirements.

*Auditor Tip:* Awareness is typically verified through interviews with general staff (e.g., asking a receptionist how they report a suspicious email) and reviewing records of security awareness training completion.

#### 4.1.4 Communication (Clause 7.4)
The organization must determine the need for internal and external communications relevant to the ISMS, including:
- On what to communicate.
- When to communicate.
- With whom to communicate.
- How to communicate.

#### 4.1.5 Documented Information (Clause 7.5)
The ISMS must include documented information required by ISO/IEC 27001 and documented information determined by the organization as necessary for the effectiveness of the ISMS.
- **Creating and updating:** Documents must have appropriate identification (title, date, author, reference number), format, and be reviewed and approved for suitability and adequacy.
- **Control of documented information:** Documents must be available and suitable for use, where and when needed, and adequately protected (e.g., from loss of confidentiality, improper use, or loss of integrity). This includes controlling version history and managing the distribution, access, retrieval, and use of documents.

### 4.2 Operation (Clause 8)
Clause 8 is where the planning from Clause 6 becomes reality. It is the "Do" phase of the PDCA cycle.

#### 4.2.1 Operational planning and control (Clause 8.1)
The organization must plan, implement, and control the processes needed to meet information security requirements, and to implement the actions determined in Clause 6.
The organization must:
- Establish criteria for the processes.
- Implement control of the processes in accordance with the criteria.
- Keep documented information to the extent necessary to have confidence that the processes have been carried out as planned.

Crucially, the organization must also control planned changes and review the consequences of unintended changes, taking action to mitigate any adverse effects. Furthermore, the organization must ensure that externally provided processes, products, or services that are relevant to the ISMS are controlled.

*Auditor Tip:* If an organization outsources its data hosting to a cloud provider, Clause 8.1 requires the organization to have controls in place to manage the security risks associated with that provider (e.g., reviewing the provider's SOC 2 reports or ISO 27001 certificate, establishing strict SLAs).

#### 4.2.2 Information security risk assessment (Clause 8.2)
Risk is not static; the threat landscape changes daily. Therefore, the organization must perform information security risk assessments at planned intervals or when significant changes are proposed or occur.
- The assessments must follow the methodology established in Clause 6.1.2.
- The organization must retain documented information of the results of these risk assessments.

#### 4.2.3 Information security risk treatment (Clause 8.3)
Following the execution of risk assessments (8.2), the organization must implement the information security risk treatment plan (developed in 6.1.3).
- The organization must retain documented information of the results of the risk treatment.

*Auditor Tip:* Clauses 8.2 and 8.3 verify that the risk management process is a continuous cycle, not a one-off exercise conducted just to get certified.

### Knowledge Check
**Question 1:** An organization has a comprehensive Information Security Policy, but during an audit, you discover that the policy is stored on a hidden intranet page that employees cannot access, and several employees interviewed have never heard of it. Which clause is primarily being violated?
A) Clause 5.2 (Policy)
B) Clause 7.3 (Awareness)
C) Clause 8.1 (Operational planning and control)
D) Clause 6.1.2 (Risk assessment)
*Answer: B. The employees lack awareness of the policy and their contribution to the ISMS.*

**Question 2:** An organization's risk assessment methodology states that risks must be reassessed annually. During an audit in November 2025, the auditor notes that the last risk assessment was completed in August 2024. What is the auditor's finding?
A) Conformity, because a risk assessment was completed.
B) Nonconformity against Clause 8.2, because the organization failed to perform the risk assessment at the planned interval (annually).
C) Opportunity for Improvement.
D) Nonconformity against Clause 7.5, because the document is old.
*Answer: B. The organization failed to execute its planned operational process for risk assessment.*

### References
[1] ISO/IEC. (2022). ISO/IEC 27001:2022 Information security, cybersecurity and privacy protection -- Information security management systems -- Requirements. https://www.iso.org/standard/82875.html
