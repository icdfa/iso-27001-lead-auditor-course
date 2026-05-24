# ISO/IEC 27001 Lead Auditor Training Course: The Complete Guide

## Module 8: Conducting an ISO/IEC 27001 Audit

### Learning Objectives
By the end of this module, you will be able to:
1. Conduct an effective Opening Meeting.
2. Apply techniques for gathering objective evidence (Interviews, Observation, Document Review).
3. Utilize effective interviewing skills to elicit accurate information.
4. Evaluate evidence against audit criteria to generate audit findings.
5. Structure and write clear, undeniable nonconformity reports using the PLO structure.

### 8.1 The Opening Meeting
The Stage 2 on-site (or virtual) audit begins with an opening meeting. This meeting sets the tone for the entire audit. It should be chaired by the Lead Auditor and attended by the auditee's management and, where appropriate, those responsible for the functions or processes to be audited.

**Agenda for the Opening Meeting:**
- **Introductions:** Introduce the audit team and their roles.
- **Confirmation of Scope and Objectives:** Reiterate what is being audited and why.
- **Audit Plan Review:** Confirm the schedule, availability of interviewees, and any necessary changes.
- **Communication Channels:** Explain how the team will communicate findings during the audit (e.g., daily wrap-up meetings).
- **Confidentiality:** Reaffirm the audit team's commitment to confidentiality.
- **Methodology:** Briefly explain how evidence will be gathered (sampling) and that auditing is a sampling process, meaning unexamined risks may still exist.
- **Reporting:** Explain how nonconformities are categorized and the reporting process.

### 8.2 Gathering Objective Evidence
Auditors gather evidence through three primary methods:

1. **Interviews:** Talking to people at all levels of the organization to understand processes, assess awareness, and verify leadership commitment.
2. **Observation:** Watching processes being performed and inspecting the physical environment (e.g., observing a user logging in, inspecting server room access controls, checking for clear desks).
3. **Document and Record Review:** Examining policies, procedures, logs, meeting minutes, and system configurations.

*The Triangulation Principle:* The strongest audit findings are supported by evidence from at least two, preferably all three, of these methods. For example, the auditor *reads* the backup policy, *interviews* the IT admin about how backups are performed, and *observes* the backup logs to verify they were successful.

### 8.3 Effective Interviewing Techniques
Interviews are often the most challenging part of the audit. The auditor must build rapport while extracting factual information.

**The OSCE Framework for Interviews:**
- **Open:** Make the interviewee comfortable. Explain the purpose of the interview. State clearly: "I am auditing the process, not you personally."
- **Show Me:** Ask open-ended questions. "Can you walk me through how you handle a new user access request?" Ask them to demonstrate the process on their computer.
- **Check:** Verify the information. "So, if I understand correctly, the manager's approval is required before IT creates the account?" Ask for records: "Can you show me the approval ticket for the last three users you created?"
- **End:** Summarize the key points. Thank the interviewee for their time. Give them a chance to ask questions.

**Handling Difficult Interviewees:**
- *The Talker:* Politely but firmly steer them back to the specific question.
- *The Defensive Employee:* Reassure them that the audit is about improving the system, not finding someone to blame.
- *The Evasive Employee:* Ask for specific, documented evidence to verify vague claims.

### 8.4 Generating Audit Findings
As evidence is gathered, it must be evaluated against the audit criteria (ISO/IEC 27001 requirements, the organization's own policies, legal requirements). This evaluation generates audit findings.

Findings can indicate:
- **Conformity:** The evidence demonstrates that the requirement is being met.
- **Nonconformity:** The evidence demonstrates that a requirement is *not* being met.
- **Opportunity for Improvement (OFI):** A situation where a requirement is currently being met, but the auditor identifies a risk that it might fail in the future, or suggests a best practice to enhance the ISMS. (Note: OFIs cannot be used to disguise nonconformities).

### 8.5 Writing Nonconformity Reports (NCRs)
A nonconformity report must be clear, concise, and undeniable. If the auditee can easily argue against the finding, it is poorly written.

**The PLO Structure for Nonconformities:**
Professional auditors use the PLO structure to write findings:

1. **Provision (The Requirement):** State exactly what the requirement is, citing the specific clause of the standard or the specific internal policy document.
2. **Location (Where it was found):** State exactly where the failure was observed (e.g., Department, specific server, specific document).
3. **Objective Evidence (The Facts):** State the verifiable facts that prove the requirement was not met.

**Example of a Poor NCR:**
"The company's password policy is weak and people aren't following it." *(Vague, subjective, no clause cited, no evidence provided).*

**Example of an Excellent NCR (using PLO):**
- **Provision:** ISO/IEC 27001:2022, Annex A Control 5.17 (Authentication information) requires that the allocation and management of authentication information be controlled by a management process. The organization's internal 'Access Control Policy v2.0' Section 4.1 requires passwords to be a minimum of 12 characters and changed every 90 days.
- **Location:** IT Operations Department, Active Directory configuration.
- **Objective Evidence:** During an observation of the Active Directory configuration on November 12, 2025, it was noted that the minimum password length was set to 8 characters, and password expiration was disabled. Furthermore, an interview with the IT Administrator confirmed that these settings have been in place since the system was deployed in 2023.

### Knowledge Check
**Question 1:** During an interview, an employee tells you, "We used to do weekly vulnerability scans, but the scanning tool license expired three months ago, so we haven't done any since." What should the auditor do next?
A) Immediately write a major nonconformity report based on the statement.
B) Ignore the statement unless the IT Manager confirms it.
C) Apply the "Check" phase of the OSCE framework by asking to see the scanning tool dashboard or the last generated scan report to verify the employee's claim with objective evidence.
D) End the interview and report the employee to their manager.
*Answer: C. Interview statements should be corroborated with objective evidence (records or observation) whenever possible.*

**Question 2:** Review the following audit finding: "The risk assessment methodology is confusing and could lead to errors." What is the primary flaw in this finding?
A) It does not cite a specific clause.
B) It is based on the auditor's subjective opinion rather than objective evidence.
C) It lacks a specific location.
D) All of the above.
*Answer: D. The finding fails all three elements of the PLO structure. It is subjective, lacks a provision, lacks a location, and lacks objective evidence.*

### References
[1] ISO. (2018). ISO 19011:2018 Guidelines for auditing management systems. https://www.iso.org/standard/70017.html
