# Modbus Detection Lab Gap Analysis

## Overview

This gap analysis is an extension of my previous project (https://github.com/cjhosea/modbus-detection-lab). 

CISA's Cyber Security Evaluation Tool (CSET) is a tool designed to help organizations systematically evaluate their security posture and perform a gap analysis. NIST SP 800-82 is a document that provides guidance on how to secure operational technology assets and the systems and networks surrounding them. Using CSET, organizations can assess their ICS networks and systems based on NIST SP 800-82 revision 3. I used CSET to assess my Modbus detection lab against NIST SP 800-82 and see how it measures up. Additionally, I scrutinized the lab against ISA/IEC 62443.

Key Results:
  - 2% NIST SP 800-82 compliance
  - 6 out of 7 62443 foundational requirements failed, 1 partially met
  - Lacking access control, segmentation, incident recovery/response

Recommendation:
  - Implement OT-aware firewall

Write-Up:
  - https://github.com/cjhosea/gap-analysis-mb/blob/main/docs/Gap%20Analysis.pdf

Supplemental Files:
  - https://github.com/cjhosea/gap-analysis-mb/blob/main/docs/Executive%20Summary%20-%20Modbus%20Detection%20Lab.pdf
  - https://github.com/cjhosea/gap-analysis-mb/blob/main/docs/Site%20Summary%20-%20Modbus%20Detection%20Lab.pdf

