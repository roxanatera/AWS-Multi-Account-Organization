# AWS-Multi-Account-Organization
This project demonstrates a basic yet essential AWS Organizations structure, where we separate environments into dedicated accounts under a centralized management.

![AWS Organization Diagram](https://github.com/roxanatera/AWS-Multi-Account-Organization/blob/main/docs/aws-org-diagram.png)


🧱 Architecture Overview
We define a multi-account structure using AWS Organizations:

Root IAM User: Centralized identity and billing control.

Organizational Units (OU):

Production OU: Contains the account used for live environments.

Development OU: Isolated account for testing, feature development, and staging.

✅ Why This Structure Matters
Even for small or basic setups, organizing your AWS accounts like this offers several key benefits:

Environment isolation: Mistakes in development won't impact production.

Centralized governance: Apply SCPs (Service Control Policies), budgets, and guardrails across all accounts.

Security: Reduce blast radius and improve access management.

Billing clarity: Separate costs by department, usage, or team.

Scalability: Ready to grow with your team or project.
