# Compliance Agent

The Compliance Agent is a specialist agent designed to support a broader Chief of Staff Agent. It identifies applicable requirements, assesses compliance risks and controls, reviews readiness, and routes unresolved matters to authorized decision-makers.

This repository is an early prototype exploring how specialized agents can contribute to executive decision support and responsible organizational governance.

## Role in the Agent System

The Chief of Staff Agent acts as the orchestrator. It assigns compliance-related work to the Compliance Agent and combines its findings with input from other specialist agents.

The Compliance Agent may recommend involvement from:

- Innovation Agent for redesign, feasibility, or opportunity reassessment
- Data Analyst Agent for quantitative evidence, validation, and monitoring
- Project Management Agent for remediation planning, dependencies, and execution tracking
- Authorized legal, privacy, security, accessibility, procurement, records-management, audit, or governance functions for formal review or approval

The Compliance Agent provides structured decision support. It does not provide legal advice, grant approval, approve exceptions, or accept risk.

## Core Skills

### 1. Requirement and Policy Mapping

Identifies potentially applicable laws, regulations, policies, standards, contracts, governance bodies, required approvals, and evidence.

[View the Requirement and Policy Mapping skill](.agents/skills/requirement-policy-mapping/SKILL.md)

### 2. Risk and Control Assessment

Identifies compliance risks, evaluates likelihood and impact, distinguishes inherent from residual risk, and maps risks to controls, owners, evidence, and remediation actions.

[View the Risk and Control Assessment skill](.agents/skills/risk-control-assessment/SKILL.md)

### 3. Compliance Review and Escalation

Reviews an initiative against identified requirements and controls, classifies findings, determines readiness, and routes unresolved matters to authorized reviewers.

[View the Compliance Review and Escalation skill](.agents/skills/compliance-review-escalation/SKILL.md)

## Typical Workflow

1. Identify and map applicable requirements.
2. Assess risks and existing or proposed controls.
3. Review compliance readiness.
4. Classify findings and identify remediation needs.
5. Escalate unresolved matters to authorized reviewers through the Chief of Staff Agent.

Not every assignment requires all three skills. The agent begins at the stage appropriate to the available documentation and prior decisions.

## Example Use Case

**Question:** What compliance work is needed before piloting an AI tool that summarizes executive meeting materials?

The Compliance Agent can:

- Identify potentially applicable privacy, security, records-retention, accessibility, procurement, and responsible-AI requirements
- Determine what information requires authoritative confirmation
- Identify risks related to sensitive data, access, retention, accuracy, and vendor use
- Map risks to proposed controls, accountable functions, and required evidence
- Classify gaps and determine readiness
- Route formal interpretations, approvals, exceptions, and risk acceptance to authorized decision-makers

## Repository Structure

```text
compliance_agent/
├── AGENTS.md
├── README.md
└── .agents/
    └── skills/
        ├── requirement-policy-mapping/
        │   └── SKILL.md
        ├── risk-control-assessment/
        │   └── SKILL.md
        └── compliance-review-escalation/
            └── SKILL.md
```

## Status

Early-stage prototype for professional development and concept validation. The current version establishes the Compliance Agent’s role, routing instructions, core skills, outputs, handoffs, evidence expectations, and guardrails.
