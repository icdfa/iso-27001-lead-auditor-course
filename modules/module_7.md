# ISO/IEC 27001 Lead Auditor Training Course: The Complete Guide

## Module 7: Preparing for an ISO/IEC 27001 Audit

### Learning Objectives
By the end of this module, you will be able to:
1. Explain the process of initiating an audit.
2. Understand the purpose and execution of a Stage 1 Audit (Document Review).
3. Develop an effective Audit Plan for a Stage 2 Audit.
4. Apply risk-based sampling strategies.
5. Create comprehensive audit working documents, including checklists.

### 7.1 Initiating the Audit
The audit process begins long before the auditor arrives on-site. Initiation involves:
- **Establishing Contact:** The Lead Auditor formally contacts the auditee's representative to confirm the audit scope, objectives, and criteria, and to request access to relevant documents.
- **Determining Feasibility:** The Lead Auditor assesses whether the audit can actually be performed. Is sufficient information available? Is there adequate time and resources? Is the auditee cooperative?
- **Selecting the Audit Team:** The Lead Auditor (or the audit program manager) selects team members based on the competence needed to achieve the audit objectives. If the organization uses complex, proprietary cryptography, the team may need a technical expert.

### 7.2 The Stage 1 Audit (Document Review)
For third-party certification, the initial audit is split into two stages. Stage 1 is primarily a desktop review of the organization's documented ISMS.

**Purpose of Stage 1:**
1. To review the client's ISMS documented information.
2. To evaluate the client's site-specific conditions and undertake discussions with personnel to determine preparedness for Stage 2.
3. To review the client's status and understanding regarding requirements of the standard, particularly concerning the identification of key performance or significant aspects, processes, objectives, and operation of the ISMS.
4. To obtain necessary information regarding the scope of the ISMS, processes, and locations, and related statutory and regulatory aspects.
5. To evaluate if internal audits and management reviews are being planned and performed.

**Key Documents Reviewed during Stage 1:**
- Information Security Policy (Clause 5.2)
- Scope of the ISMS (Clause 4.3)
- Risk Assessment Methodology (Clause 6.1.2)
- Risk Treatment Plan (Clause 6.1.3)
- Statement of Applicability (SoA) (Clause 6.1.3)
- Internal Audit Program and Results (Clause 9.2)
- Management Review Minutes (Clause 9.3)

*Outcome:* The Lead Auditor issues a Stage 1 report identifying any areas of concern that could be classified as nonconformities during Stage 2. If the ISMS is severely deficient (e.g., no risk assessment has been performed), the Lead Auditor will recommend delaying Stage 2 until the issues are resolved.

### 7.3 Developing the Audit Plan (Stage 2)
The Stage 2 audit evaluates the *implementation* and *effectiveness* of the ISMS. The Audit Plan is the roadmap for this evaluation. It must be communicated to the auditee well in advance.

**A good Audit Plan includes:**
- Audit objectives, criteria, and scope.
- Dates and locations (physical or virtual) where the audit activities will be conducted.
- Expected time and duration of audit activities, including meetings with the auditee's management.
- Roles and responsibilities of the audit team members and accompanying persons (guides).
- Allocation of appropriate resources based upon consideration of the risks and opportunities related to the activities to be audited.

*Auditor Tip:* A common mistake is planning the audit strictly by clause number (e.g., "9:00 AM - Audit Clause 4; 10:00 AM - Audit Clause 5"). Effective audits are planned by *process* or *department* (e.g., "9:00 AM - HR Department: Reviewing onboarding, termination, and training processes"). This allows the auditor to assess multiple clauses and Annex A controls simultaneously in a natural business context.

### 7.4 Audit Sampling
An auditor cannot review every single record, interview every employee, or check every server configuration. Therefore, auditors must use sampling.

**Types of Sampling:**
1. **Statistical Sampling:** Used when there is a large, uniform dataset (e.g., thousands of user access request forms). The auditor uses statistical formulas to determine a sample size that provides a specific confidence level.
2. **Judgmental (Non-Statistical) Sampling:** The most common method in management system auditing. The auditor uses their professional judgment to select a sample based on risk, complexity, or specific areas of concern.

*Example of Judgmental Sampling:* When reviewing incident response records, the auditor might ask for "all critical incidents from the past 12 months, plus three randomly selected medium-severity incidents."

### 7.5 Preparing Working Documents
Audit team members should collect and review the information relevant to their audit assignments and prepare working documents, as necessary, for reference and for recording audit evidence.

**The Audit Checklist:**
The most important working document is the audit checklist. A checklist ensures that the audit is systematic, comprehensive, and stays on schedule.

*A good checklist:*
- Is tailored to the specific auditee based on the Stage 1 review.
- Uses open-ended questions (Who, What, Where, When, Why, How).
- Leaves space to record specific objective evidence (names, document version numbers, specific observations).
- Maps questions back to the specific clauses of ISO/IEC 27001.

*A bad checklist:*
- Simply rephrases the standard as a yes/no question (e.g., "Do you have an information security policy?").
- Is rigidly followed even when the interview reveals a high-risk area that requires deviation from the script.

### Knowledge Check
**Question 1:** What is the primary purpose of a Stage 1 certification audit?
A) To interview all staff members about their security awareness.
B) To evaluate the implementation and effectiveness of all Annex A controls.
C) To review the ISMS documented information and determine preparedness for the Stage 2 audit.
D) To issue the formal ISO/IEC 27001 certificate.
*Answer: C. Stage 1 is primarily a readiness review focused on documentation and planning.*

**Question 2:** An auditor is preparing to audit the Human Resources department's compliance with Annex A controls related to employee onboarding and offboarding. Which of the following is an example of Judgmental Sampling?
A) Requesting to review the files of the last 5 employees who were terminated, specifically looking for evidence that their IT access was revoked within 24 hours.
B) Using a random number generator to select 10% of all employee files from the past decade.
C) Reviewing every single employee file in the company.
D) Asking the HR manager if they follow the offboarding procedure.
*Answer: A. The auditor is using their judgment to select a specific, high-risk sample (recent terminations) to test a specific control (access revocation).*

### References
[1] ISO. (2018). ISO 19011:2018 Guidelines for auditing management systems. https://www.iso.org/standard/70017.html
