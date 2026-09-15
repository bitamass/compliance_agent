---
name: risk-control-assessment
description: Identify compliance risks, evaluate their likelihood and impact, and map them to preventive, detective, or corrective controls. Use when assessing whether proposed controls reduce identified risks to an acceptable level and what evidence, owners, or remediation actions are needed.
---

# Risk and Control Assessment

## Purpose

Assess compliance risks associated with an initiative and determine whether appropriate controls, owners, evidence, and monitoring are in place.

This skill provides risk-based decision support. It does not provide legal advice, certify compliance, or accept risk on behalf of an organization.

## Inputs

Use the available information about:

- Initiative, system, vendor, product, or process
- Intended use and operating environment
- Applicable requirements
- Data, users, stakeholders, and integrations
- Existing policies and controls
- Known risks, incidents, or audit findings
- Control owners and approval authorities
- Available evidence
- Project stage and desired decision

If requirement mapping has not been completed, identify which requirements must be confirmed before completing the assessment.

## Risk Categories

Consider only categories relevant to the request, including:

- Privacy and data protection
- Information security
- Responsible AI, bias, and transparency
- Accessibility
- Records retention and public records
- Regulatory and legal exposure
- Vendor and third-party risk
- Contractual risk
- Procurement risk
- Operational and business-continuity risk
- Financial and fraud risk
- Reputational and stakeholder risk
- Governance and accountability

## Workflow

1. Clarify the initiative, scope, environment, and decision.
2. Review confirmed and potentially applicable requirements.
3. Identify risk events, causes, affected stakeholders, and consequences.
4. Distinguish inherent risk from residual risk.
5. Evaluate likelihood and impact using the scoring method below.
6. Identify existing controls and classify their purpose.
7. Evaluate whether each control is appropriately designed and supported by evidence.
8. Identify control gaps, weak ownership, missing evidence, and monitoring needs.
9. Propose proportionate remediation or additional controls.
10. Identify the person or function authorized to accept any remaining risk.
11. Recommend whether the initiative is ready for compliance review or requires remediation.

## Risk Scoring

Score likelihood from 1 to 5:

- 1 = Rare
- 2 = Unlikely
- 3 = Possible
- 4 = Likely
- 5 = Almost certain

Score impact from 1 to 5:

- 1 = Minimal
- 2 = Minor
- 3 = Moderate
- 4 = Major
- 5 = Severe

Calculate:

`Risk score = likelihood × impact`

Use these default ranges unless an approved organizational framework specifies otherwise:

- 1–4 = Low
- 5–9 = Moderate
- 10–16 = High
- 17–25 = Critical

Explain the evidence and uncertainty behind every score. Do not present an unsupported score as objective fact.

## Control Classification

Classify controls as:

- Preventive: reduces the chance that a risk event occurs
- Detective: identifies a risk event or control failure
- Corrective: limits harm or restores an acceptable state
- Directive: establishes expected behavior or responsibility

For each control, identify:

- Risk addressed
- Control description
- Control type
- Control owner
- Implementation status
- Evidence available
- Testing or monitoring approach
- Known gaps
- Expected effect on residual risk

Do not describe a planned or undocumented control as fully implemented.

## Required Output

Provide:

1. Executive summary
2. Scope and decision being supported
3. Confirmed requirements and assumptions
4. Risk register
5. Inherent-risk ratings with rationale
6. Existing and proposed controls
7. Control gaps and evidence gaps
8. Residual-risk ratings with rationale
9. Remediation actions, owners, and timing
10. Risks requiring escalation or formal acceptance
11. Readiness recommendation
12. Confidence level and rationale

## Readiness Categories

Recommend one of the following:

- Ready for compliance review
- Ready with conditions
- Remediation required
- Insufficient information
- Do not proceed pending authorized review

A readiness recommendation is not final compliance approval.

## Handoffs

Recommend that the Chief of Staff Agent involve:

- The Innovation Agent when controls materially affect feasibility, value, or design
- The Data Analyst Agent when quantitative evidence, monitoring, or validation is needed
- The Project Management Agent when remediation actions require planning and tracking
- Legal counsel, privacy, security, accessibility, records management, procurement, audit, or another authorized function when formal interpretation, testing, approval, or risk acceptance is required

## Guardrails

- Do not provide legal advice or certify compliance.
- Do not fabricate risks, requirements, control evidence, incidents, or test results.
- Do not claim a control is effective solely because it is documented.
- Clearly distinguish implemented, planned, partially implemented, and missing controls.
- Do not accept residual risk on behalf of an accountable executive or authorized function.
- Escalate critical risks, unresolved legal questions, and missing mandatory controls.
- Do not modify systems, controls, records, or approvals without authorization.
