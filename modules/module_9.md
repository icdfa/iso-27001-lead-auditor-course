# ISO/IEC 27001 Lead Auditor Training Course: The Complete Guide

## Module 9: Closing the Audit and Follow-up

### Learning Objectives
By the end of this module, you will be able to:
1. Prepare for and conduct an effective Closing Meeting.
2. Differentiate between Major and Minor nonconformities.
3. Structure and write a comprehensive formal Audit Report.
4. Evaluate Corrective Action Plans (CAPs) submitted by the auditee.
5. Understand the process for verifying and closing nonconformities.

### 9.1 Preparing for the Closing Meeting
Before presenting the findings to the auditee's management, the audit team must meet privately to review their notes, consolidate findings, and agree on the audit conclusions.

**Key tasks during preparation:**
- Review all findings against the audit criteria to ensure they are valid and supported by objective evidence.
- Ensure all nonconformity reports (NCRs) are written clearly using the PLO structure.
- Categorize the nonconformities (Major vs. Minor).
- Agree on the final audit conclusion (e.g., recommend certification, recommend certification pending corrective actions, or do not recommend certification).

### 9.2 Categorizing Nonconformities
Certification bodies typically classify nonconformities into two categories:

**1. Major Nonconformity:**
A failure that affects the capability of the ISMS to achieve its intended outcomes. Examples include:
- A complete failure to implement a mandatory clause of ISO/IEC 27001 (e.g., no internal audits have been conducted).
- A significant breakdown in a critical security control that poses an immediate, high risk to the organization (e.g., a total failure of access control on the core financial database).
- A number of minor nonconformities associated with the same requirement or issue that, when viewed together, demonstrate a systemic failure.

*Impact:* A major nonconformity will prevent the issuance of an ISO/IEC 27001 certificate until it is fully resolved and verified by the auditor (often requiring a follow-up on-site visit).

**2. Minor Nonconformity:**
A single, isolated lapse in the implementation of a requirement or control that does not affect the overall capability of the ISMS to achieve its intended outcomes. Examples include:
- A few employee training records are missing, but the vast majority are present and the training program is generally functioning.
- A procedure document has not been updated with the new department name, though the process itself is being followed correctly.

*Impact:* A minor nonconformity will not usually prevent certification, provided the organization submits an acceptable Corrective Action Plan (CAP) within a specified timeframe. The auditor will verify the implementation of the CAP during the next surveillance audit.

### 9.3 The Closing Meeting
The closing meeting is the formal conclusion of the on-site audit. It is chaired by the Lead Auditor and attended by top management.

**Agenda for the Closing Meeting:**
- **Thanks and Acknowledgments:** Thank the auditee for their time and cooperation.
- **Disclaimer:** Reiterate that auditing is a sampling process; absence of findings in an area does not guarantee absolute security.
- **Presentation of Findings:** Present the nonconformities and positive findings clearly. Avoid getting drawn into arguments. If the auditee disputes a finding, refer back to the objective evidence and the specific clause.
- **Audit Conclusion:** State the team's recommendation regarding certification.
- **Next Steps:** Explain the process and timelines for submitting Corrective Action Plans (CAPs) and the follow-up process.

### 9.4 The Audit Report
The Lead Auditor is responsible for providing a written report. The report must provide a complete, accurate, concise, and clear record of the audit.

**A standard Audit Report includes:**
- Audit objectives, scope, and criteria.
- Identification of the audit client, auditee, and audit team members.
- Dates and locations of the audit.
- Audit findings (both conformities and nonconformities) with supporting evidence.
- Audit conclusions.
- A statement on the degree to which the audit criteria have been fulfilled.
- Any unresolved diverging opinions between the audit team and the auditee.

### 9.5 Evaluating Corrective Action Plans (CAPs)
When an auditor issues a nonconformity, the auditee must respond with a Corrective Action Plan. The auditor must evaluate this plan before accepting it.

**The Five-Question Test for a CAP:**
1. **Correction:** Does the plan address the immediate issue? (e.g., fixing the broken server configuration).
2. **Root Cause Analysis:** Has the organization identified *why* the failure occurred? (e.g., "The server was misconfigured because the deployment script was outdated and the administrator bypassed the change control process").
3. **Corrective Action:** Does the proposed action address the root cause to prevent recurrence? (e.g., "Update the deployment script, retrain the administrator, and implement a hard technical block on bypassing change control").
4. **Responsibility:** Is a specific person assigned to implement the action?
5. **Timeline:** Is there a realistic deadline for completion?

If the CAP only addresses the symptom (correction) and not the disease (root cause), the auditor must reject it and ask the auditee to resubmit.

### 9.6 Closing the Nonconformity
Once the auditee has implemented the corrective action, the auditor must verify its effectiveness.
- For a **Minor Nonconformity**, this verification usually happens during the next scheduled surveillance audit (typically one year later).
- For a **Major Nonconformity**, the auditor may require documentary evidence to be submitted immediately, or may need to conduct a special short-notice on-site visit to verify the fix before certification can be granted.

If the auditor verifies that the root cause has been eliminated and the new process is working effectively, the nonconformity is formally closed.

### Knowledge Check
**Question 1:** During a Stage 2 audit, the auditor discovers that the organization has completely failed to conduct a Management Review (Clause 9.3) over the past year. How should this finding be categorized?
A) Minor Nonconformity, because it is just an administrative meeting.
B) Major Nonconformity, because it is a complete failure to implement a mandatory clause of the management system, severely impacting governance.
C) Opportunity for Improvement.
D) Conformity, provided they promise to hold one next month.
*Answer: B. The total absence of management review is a systemic failure of the ISMS.*

**Question 2:** An auditor issues a nonconformity because three employees in the finance department were found sharing a single generic user account and password. The auditee submits the following Corrective Action Plan: "We have instructed the three employees to stop sharing the account and have issued them individual accounts." Should the auditor accept this CAP?
A) Yes, the immediate problem is solved.
B) Yes, this is a standard IT response.
C) No. The CAP only contains a correction. It lacks a root cause analysis (why were they sharing an account? Was the provisioning process too slow? Was it to save on software licensing costs?) and therefore lacks a true corrective action to prevent recurrence.
D) No, the auditor should fix the issue for them.
*Answer: C. A CAP must address the root cause, not just the immediate symptom.*

### References
[1] ISO. (2018). ISO 19011:2018 Guidelines for auditing management systems. https://www.iso.org/standard/70017.html
