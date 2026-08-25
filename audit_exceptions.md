# Internal Audit Exceptions

## Purpose

This document summarizes control exceptions identified during the simulated internal audit and control testing engagement for Northbridge Technologies.

Each exception includes the related control area, test result, risk level, business impact, and recommended corrective action.

---

## Exception 1: Incomplete User Provisioning Approval

### Test ID

**CT-001**

### Control Area

User Provisioning

### Test Result

Effective with Minor Exception

### Risk Level

**Medium**

### Exception

1 of 10 sampled user provisioning records lacked complete manager approval evidence.

### Business Impact

Incomplete approval evidence may make it difficult to demonstrate that user access was properly authorized.

### Recommendation

Require documented approval before account provisioning and retain approval evidence with the access request.

---

## Exception 2: Delayed Terminated-User Access Removal

### Test ID

**CT-002**

### Control Area

User Termination

### Test Result

Partially Effective

### Risk Level

**High**

### Exception

2 of 10 terminated users retained active access beyond the expected disablement timeframe.

### Business Impact

Former employees may retain unauthorized access to systems, applications, or sensitive data.

### Recommendation

Automate termination notifications and monitor account-disablement completion.

---

## Exception 3: Privileged Access Review Gaps

### Test ID

**CT-003**

### Control Area

Privileged Access

### Test Result

Partially Effective

### Risk Level

**High**

### Exception

3 of 8 sampled privileged accounts lacked current business justification or recent review evidence.

### Business Impact

Users may retain elevated privileges that are no longer necessary.

### Recommendation

Perform quarterly privileged-access reviews, document business justification, and remove unnecessary elevated permissions.

---

## Exception 4: MFA Coverage Gap

### Test ID

**CT-004**

### Control Area

Multi-Factor Authentication

### Test Result

Partially Effective

### Risk Level

**High**

### Exception

2 applicable privileged accounts were not enrolled in MFA and had no approved exception.

### Business Impact

Compromised credentials may provide unauthorized privileged access.

### Recommendation

Enforce MFA for all applicable privileged accounts and document approved exceptions.

---

## Exception 5: Access Review Follow-Up Missing

### Test ID

**CT-005**

### Control Area

Access Reviews

### Test Result

Partially Effective

### Risk Level

**High**

### Exception

2 of 10 sampled access review decisions lacked evidence showing identified unnecessary access was removed.

### Business Impact

Excessive or inappropriate access may remain active after review.

### Recommendation

Require remediation evidence for every access-review exception and verify closure before completing the review cycle.

---

## Exception 6: Incomplete Change Testing Evidence

### Test ID

**CT-006**

### Control Area

Change Management

### Test Result

Effective with Minor Exception

### Risk Level

**Medium**

### Exception

1 of 10 sampled production changes lacked complete testing evidence.

### Business Impact

Untested changes may increase the risk of service disruption, misconfiguration, or security issues.

### Recommendation

Require documented testing evidence before final change approval and implementation.

---

## Exception 7: Incomplete Log Review Documentation

### Test ID

**CT-007**

### Control Area

Audit Logging

### Test Result

Partially Effective

### Risk Level

**Medium**

### Exception

2 review periods lacked complete documentation showing security logs were reviewed and analyzed.

### Business Impact

Suspicious activity may go undetected or lack sufficient investigation evidence.

### Recommendation

Establish recurring log-review procedures and retain reviewer, investigation, escalation, and resolution evidence.

---

## Exception 8: Overdue High-Risk Vulnerabilities

### Test ID

**CT-008**

### Control Area

Vulnerability Management

### Test Result

Partially Effective

### Risk Level

**High**

### Exception

3 of 10 high-risk vulnerabilities exceeded defined remediation timelines without documented risk acceptance.

### Business Impact

Known vulnerabilities may remain exploitable longer than acceptable.

### Recommendation

Enforce severity-based remediation SLAs and require formal risk acceptance for approved exceptions.

---

## Exception 9: Incomplete Incident Documentation

### Test ID

**CT-009**

### Control Area

Incident Response

### Test Result

Effective with Minor Exception

### Risk Level

**Medium**

### Exception

1 of 5 sampled security incidents lacked complete escalation and closure documentation.

### Business Impact

Incomplete incident records may reduce auditability, lessons learned, and management visibility.

### Recommendation

Use a standardized incident documentation checklist before closure.

---

## Exception 10: Incident Response Testing Not Current

### Test ID

**CT-010**

### Control Area

Incident Response Testing

### Test Result

Ineffective

### Risk Level

**High**

### Exception

No current tabletop exercise was available to demonstrate recurring incident response testing.

### Business Impact

The organization may be unprepared to respond effectively during a real security incident.

### Recommendation

Conduct an annual tabletop exercise and document participants, decisions, lessons learned, and corrective actions.

---

## Exception 11: Insufficient Backup Restoration Evidence

### Test ID

**CT-011**

### Control Area

Backup and Recovery

### Test Result

Partially Effective

### Risk Level

**Medium**

### Exception

Only 2 of 4 expected recent restoration tests had sufficient supporting evidence.

### Business Impact

The organization may not be able to demonstrate that critical systems and data can be recovered.

### Recommendation

Perform quarterly restoration testing and retain recovery results and corrective-action evidence.

---

## Exception 12: Outdated Vendor Reassessments

### Test ID

**CT-012**

### Control Area

Third-Party Risk

### Test Result

Partially Effective

### Risk Level

**High**

### Exception

2 of 5 high-risk vendors had outdated reassessment evidence.

### Business Impact

Changes in vendor security posture may not be identified in a timely manner.

### Recommendation

Perform annual reassessments for high-risk vendors and track overdue reviews.

---

## Exception 13: Overdue Policy Review

### Test ID

**CT-013**

### Control Area

Policy Management

### Test Result

Effective with Minor Exception

### Risk Level

**Low**

### Exception

1 of 5 sampled policies exceeded its scheduled review date.

### Business Impact

Outdated policies may not reflect current systems, risks, or security expectations.

### Recommendation

Update the overdue policy and implement recurring review reminders.

---

## Exception 14: Incomplete Risk Treatment Documentation

### Test ID

**CT-014**

### Control Area

Risk Management

### Test Result

Partially Effective

### Risk Level

**Medium**

### Exception

2 of 10 open risks lacked complete treatment or approval documentation.

### Business Impact

Material risks may remain unresolved or lack clear management accountability.

### Recommendation

Require documented treatment decisions, assigned owners, target dates, and management approval.

---

## Exception 15: Findings Closed Without Validation Evidence

### Test ID

**CT-015**

### Control Area

Remediation Tracking

### Test Result

Partially Effective

### Risk Level

**High**

### Exception

2 of 10 prior audit findings were marked closed without sufficient validation evidence.

### Business Impact

Control weaknesses may remain unresolved even though they appear closed in the audit tracker.

### Recommendation

Require independent validation evidence and formal closure approval before closing findings.

---

## Exception Summary

| Test ID | Control Area | Exceptions | Risk |
|---|---|---:|---|
| CT-001 | User Provisioning | 1/10 | Medium |
| CT-002 | User Termination | 2/10 | High |
| CT-003 | Privileged Access | 3/8 | High |
| CT-004 | MFA | 2 | High |
| CT-005 | Access Reviews | 2/10 | High |
| CT-006 | Change Management | 1/10 | Medium |
| CT-007 | Audit Logging | 2 periods | Medium |
| CT-008 | Vulnerability Management | 3/10 | High |
| CT-009 | Incident Response | 1/5 | Medium |
| CT-010 | Incident Response Testing | 1/1 | High |
| CT-011 | Backup and Recovery | 2/4 | Medium |
| CT-012 | Third-Party Risk | 2/5 | High |
| CT-013 | Policy Management | 1/5 | Low |
| CT-014 | Risk Management | 2/10 | Medium |
| CT-015 | Remediation Tracking | 2/10 | High |

## Conclusion

The most significant issues identified involved terminated-user access, privileged access, MFA, access-review follow-up, vulnerability remediation, incident response testing, third-party reassessment, and remediation closure validation.

High-risk exceptions should receive priority corrective action and remain open until sufficient evidence demonstrates that remediation is complete and effective.

This is a simulated portfolio project and does not represent a real internal audit.
