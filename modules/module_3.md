# ISO/IEC 27001 Lead Auditor Training Course: The Complete Guide

## Module 3: Planning and Risk Management

### Learning Objectives
By the end of this module, you will be able to:
1. Understand the requirements for addressing risks and opportunities (Clause 6.1).
2. Explain the process of Information Security Risk Assessment (Clause 6.1.2).
3. Describe the Information Security Risk Treatment process (Clause 6.1.3).
4. Understand the purpose and content of the Statement of Applicability (SoA).
5. Evaluate how organizations establish and plan to achieve Information Security Objectives (Clause 6.2).

### 3.1 Planning to Address Risks and Opportunities
Clause 6 is the engine room of the ISMS. Information security is fundamentally about managing risk. Clause 6.1.1 requires the organization to consider the issues referred to in Clause 4.1 (Context) and the requirements referred to in Clause 4.2 (Interested Parties) and determine the risks and opportunities that need to be addressed to:
- Ensure the ISMS can achieve its intended outcomes.
- Prevent, or reduce, undesired effects (e.g., data breaches, system downtime).
- Achieve continual improvement.

### 3.2 Information Security Risk Assessment (Clause 6.1.2)
The standard does not prescribe a specific risk assessment methodology (e.g., OCTAVE, NIST SP 800-30, or ISO 27005), but it does mandate specific criteria that the chosen methodology must meet. The organization must define and apply an information security risk assessment process that:

1. **Establishes Risk Criteria:** The organization must establish criteria for accepting risks and criteria for performing information security risk assessments. (e.g., "We will accept any risk rated 'Low', but 'High' risks require immediate mitigation.")
2. **Ensures Consistency:** The process must produce consistent, valid, and comparable results. If two different people assess the same risk using the methodology, they should arrive at roughly the same conclusion.
3. **Identifies Risks:** The organization must identify risks associated with the loss of confidentiality, integrity, and availability for information within the scope of the ISMS. They must also identify the *owners* of these risks.
4. **Analyzes Risks:** The organization must assess the potential consequences if the risks materialize and assess the realistic likelihood of the occurrence.
5. **Evaluates Risks:** The organization must compare the results of the risk analysis with the established risk criteria and prioritize the analyzed risks for risk treatment.

*Auditor Tip:* When auditing this clause, you are looking for a documented risk assessment methodology and evidence (such as a completed risk register) that the methodology has been applied consistently across the ISMS scope.

### 3.3 Information Security Risk Treatment (Clause 6.1.3)
Once risks are identified and evaluated, the organization must decide what to do about them. This is the risk treatment process. The organization must:

1. **Select Risk Treatment Options:** For each prioritized risk, the organization must choose an appropriate treatment option. The common options are:
 - **Modify (Mitigate):** Apply controls to reduce the likelihood or consequence (e.g., installing a firewall).
 - **Retain (Accept):** Accept the risk because it falls within the acceptable risk criteria, or the cost of mitigation exceeds the potential loss.
 - **Avoid:** Stop the activity that causes the risk (e.g., deciding not to collect certain sensitive customer data).
 - **Share (Transfer):** Transfer the risk to another party (e.g., purchasing cyber insurance or outsourcing a process).

2. **Determine Necessary Controls:** The organization must determine all controls that are necessary to implement the chosen risk treatment options.

3. **Compare with Annex A:** The organization must compare the controls determined in step 2 with the reference controls in Annex A of ISO/IEC 27001 to verify that no necessary controls have been omitted. Annex A serves as a comprehensive "sanity check."

4. **Produce a Statement of Applicability (SoA):** The SoA is one of the most critical documents in an ISMS audit. It must contain:
 - The necessary controls.
 - Justification for their inclusion.
 - Whether they are implemented or not.
 - Justification for excluding any of the Annex A controls.

5. **Formulate a Risk Treatment Plan:** A documented plan detailing how the chosen treatment options will be implemented (who, what, when, and resource requirements).

6. **Obtain Risk Owner Approval:** The risk owners must formally approve the risk treatment plan and accept any residual information security risks.

### 3.4 Information Security Objectives and Planning (Clause 6.2)
Risk management is about preventing bad things from happening; setting objectives is about driving the ISMS forward to achieve positive outcomes.

The organization must establish information security objectives at relevant functions and levels. These objectives must:
- Be consistent with the Information Security Policy.
- Be measurable (if practicable).
- Take into account applicable information security requirements and results from risk assessments.
- Be monitored, communicated, and updated as appropriate.

When planning how to achieve its objectives, the organization must determine:
- What will be done.
- What resources will be required.
- Who will be responsible.
- When it will be completed.
- How the results will be evaluated.

*Example of a good objective:* "Reduce the average time to deploy critical security patches from 14 days to 48 hours by the end of Q3." (This is specific, measurable, assigned, and time-bound).
*Example of a poor objective:* "Improve network security." (This is vague and unmeasurable).

### 3.5 Planning of Changes (Clause 6.3)
This clause, explicitly added in the 2022 revision, requires that when the organization determines the need for changes to the ISMS, the changes must be carried out in a planned manner. This ensures that changes (e.g., migrating to a new cloud provider, or restructuring the IT department) do not inadvertently introduce new vulnerabilities or break existing controls.

### Knowledge Check
**Question 1:** During an audit, you review an organization's Statement of Applicability (SoA). You notice that Control 8.24 (Use of cryptography) from Annex A has been excluded. The justification column simply says "Not required." Is this acceptable?
A) Yes, organizations can exclude any Annex A control they wish.
B) Yes, "Not required" is a standard justification.
C) No, the standard requires a valid, documented justification for excluding any Annex A control (e.g., "The organization does not transmit or store sensitive data requiring cryptographic protection"). "Not required" is insufficient.
D) No, Annex A controls can never be excluded.
*Answer: C. Exclusions are permitted, but the justification must be robust and logical.*

**Question 2:** An organization's risk register identifies a critical risk related to unauthorized access to the server room. The risk treatment plan states: "Install biometric scanners on all server room doors." However, during the audit, you observe that the scanners have not been installed. What is the most appropriate finding?
A) Nonconformity against Clause 6.1.2 (Risk Assessment).
B) Nonconformity against Clause 6.1.3 (Risk Treatment) and Clause 8.1 (Operational planning and control) because the planned treatment has not been implemented.
C) Conformity, because they have a plan to install them eventually.
D) Opportunity for Improvement.
*Answer: B. The organization has failed to implement the controls determined in its risk treatment process.*

### References
[1] ISO/IEC. (2022). ISO/IEC 27001:2022 Information security, cybersecurity and privacy protection -- Information security management systems -- Requirements. https://www.iso.org/standard/82875.html
