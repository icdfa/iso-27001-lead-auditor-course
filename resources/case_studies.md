# ISO/IEC 27001 Comprehensive Case Studies

This document provides end-to-end audit walkthroughs to demonstrate how auditing principles are applied in real-world scenarios.

## Case Study 1: GlobalFinance Inc. (Financial Services)

**Background:** GlobalFinance is a multinational investment bank seeking ISO/IEC 27001 certification for its core trading platform.

**Stage 1 Findings:** The auditor noted that while the risk assessment methodology was sound, the Statement of Applicability (SoA) excluded Annex A Control 8.12 (Data leakage prevention) without adequate justification, given the highly sensitive nature of financial trading data.

**Stage 2 Execution:** During the on-site audit, the auditor interviewed the Network Security Manager regarding data egress. The manager stated, "We rely on employee training to prevent data leakage." The auditor then reviewed email logs and observed that employees frequently emailed spreadsheets containing client portfolio data to personal email addresses to work from home.

**Audit Conclusion:** The auditor raised a Major Nonconformity against Clause 6.1.3 (Risk Treatment) and Annex A 8.12. The organization had failed to implement necessary controls to mitigate a high-impact risk. Certification was withheld pending a Corrective Action Plan.

**CAP Review:** GlobalFinance submitted a CAP detailing the immediate blocking of external email domains for portfolio data (Correction), an analysis revealing a lack of remote work tools (Root Cause), and the implementation of a comprehensive DLP solution and secure remote access portal (Corrective Action). The auditor accepted the CAP and verified implementation during a follow-up visit.

## Case Study 2: HealthTech Solutions (Healthcare IT)

**Background:** HealthTech provides a cloud-based electronic health record (EHR) system to regional hospitals. They are undergoing their first surveillance audit.

**Audit Execution:** The auditor focused on Clause 8.1 (Operational planning and control) and Annex A 5.19 (Information security in supplier relationships). HealthTech hosts its application on AWS. The auditor requested evidence of how HealthTech monitors AWS's security performance. The IT Director provided a copy of the AWS shared responsibility model but could not provide any evidence that HealthTech actively reviews AWS SOC 2 reports or monitors SLA compliance.

**Audit Conclusion:** The auditor raised a Minor Nonconformity against Clause 8.1. While AWS is a reputable provider, HealthTech failed to control the outsourced process and maintain evidence of monitoring supplier performance.

**CAP Review:** HealthTech updated its vendor management procedure to require an annual review of critical suppliers' compliance reports and assigned this responsibility to the Compliance Officer.

## Case Study 3: RetailCorp (E-Commerce)

**Background:** RetailCorp is a large online retailer undergoing recertification.

**Audit Execution:** The auditor reviewed the Internal Audit program (Clause 9.2). The schedule showed that all internal audits were conducted on time. However, upon reviewing the audit reports, the auditor noticed that the IT Infrastructure department was audited by the Lead Network Engineer.

**Audit Conclusion:** The auditor raised a Nonconformity against Clause 9.2. The standard explicitly requires the selection of auditors to ensure objectivity and the impartiality of the audit process. The Lead Network Engineer was auditing their own department's work, compromising independence.
