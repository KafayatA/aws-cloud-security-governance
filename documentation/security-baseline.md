# AWS Security & Governance Baseline

## Scenario

A fictional organisation is moving workloads into AWS.

The organisation wants a foundational security and governance
baseline that provides visibility, controls access, detects
potential threats, maintains an audit trail and helps prevent
uncontrolled cloud expenditure.

## Security & Governance Objectives

1. Control identity and access
2. Detect potential security threats
3. Maintain audit visibility
4. Monitor cloud consumption
5. Establish appropriate automation and human oversight

## Initial Control Areas

| Risk | Control | AWS Service | Evidence |
|---|---|---|---|
| Unintended external access | External access analysis | IAM Access Analyzer | Findings |
| Threat activity goes undetected | Threat detection | GuardDuty | Findings |
| Insufficient audit visibility | Activity logging | CloudTrail | Events/logs |
| Uncontrolled cloud spend | Cost monitoring | AWS Budgets | Budget alerts |
| Unsafe automated actions | Risk-based automation | TBD | Audit trail / approval |