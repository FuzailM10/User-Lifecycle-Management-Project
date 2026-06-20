# User Lifecycle Management Project - Microsoft Entra ID

## Objective

Simulate a Joiner-Mover-Leaver (JML) workflow using Microsoft Entra ID to demonstrate identity lifecycle management, role-based access control, provisioning, deprovisioning, and audit logging.

## Environment

* Microsoft Entra ID Free Tenant
* Enterprise Application: Finance Portal
* Security Groups:

  * Finance-Team
  * HR-Team
  * IT-Team
  * Terminated-Users

## Joiner Process

Created employee identities and assigned them to department-based security groups.

Example:

* Sarah Johnson → Finance-Team
* John Smith → HR-Team
* Mike Brown → IT-Team

Result:

Users received access based on organizational role assignments.

## Application Assignment

Created a test enterprise application called Finance Portal and assigned users for access testing.

Result:

Application access was linked to organizational identity management processes.

## Mover Process

Simulated a departmental transfer by moving Sarah Johnson from Finance-Team to HR-Team.

Result:

User access was adjusted to reflect the new business role and prevent privilege creep.

## Leaver Process

Simulated employee termination by removing Sarah from active groups and placing the account in the Terminated-Users group.

Result:

Access was revoked according to least-privilege and offboarding principles.

## Audit Validation

Reviewed Microsoft Entra Audit Logs to validate:

* User updates
* Group membership changes
* Access management activities

## Key IAM Concepts Demonstrated

* Joiner-Mover-Leaver (JML)
* Role-Based Access Control (RBAC)
* Least Privilege
* Provisioning
* Deprovisioning
* Access Governance
* Audit Logging

## Lessons Learned

This project demonstrated how IAM teams manage employee identities throughout the lifecycle while maintaining appropriate access controls and auditability.
