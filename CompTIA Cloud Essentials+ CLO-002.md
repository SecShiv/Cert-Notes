## 1. Cloud Concepts

### Cloud principles
- **Definition**: On-demand delivery of IT resources via the internet.
- **Key benefits**: Scalability, efficiency, flexibility, cost savings.
- **Elasticity**: Ability to scale resources up/down automatically.
- **Pooling**: Resources are shared across customers (multi-tenancy).
- **Measured service**: Usage is monitored and billed accordingly.

### Cloud networking concepts
- **Internet** → Public access.
- **Intranet** → Private, internal network.
- **Extranet** → Shared limited access between organizations.
- **VPNs**, **Direct Connect** → Secure cloud connections.

### Cloud storage technologies and concepts
- **Object Storage**: Unstructured data (e.g., AWS S3).
- **Block Storage**: Structured storage for databases, VMs (e.g., AWS EBS).
- **File Storage**: Shared file systems (e.g., NFS, SMB).
- **Durability vs Availability**:
  - Durability: Data survives hardware failures.
  - Availability: Data is accessible when needed.

### Cloud compute concepts
- **Compute Resource**: CPU, RAM provisioned virtually.
- **Serverless Computing**: Run code without managing servers (e.g., AWS Lambda).
- **Containers**: Lightweight app environments (e.g., Docker).
- **Virtual Machines (VMs)**: Full OS virtualized environments.

## 2. Business Principles of Cloud Environments

### Apply cloud business concepts
- **OPEX vs CAPEX**:
  - **OPEX** = Ongoing operational costs (cloud).
  - **CAPEX** = Upfront hardware purchases.
- **Cloud Financial Management**:
  - Budget forecasting.
  - Cost optimization.
  - Cost allocation.

### Impact of cloud on business
- **Business Agility**: Faster time-to-market.
- **New Revenue Streams**: New digital services, products.
- **Innovation**: Easier prototyping and scaling.

### Cloud licensing models
- **Subscription Model**: Pay monthly/yearly for services.
- **Consumption-Based Model**: Pay-per-use (e.g., AWS EC2).
- **BYOL (Bring Your Own License)**: Use existing licenses in the cloud.

### Importance of cloud vendor support
- **Vendor Documentation** and **SLAs** are critical.
- **Support Tiers**: Basic to Premium support.
- **Escalation Paths**: How to get help quickly when needed.

## 3. Management and Technical Operations

### Aspects of operating within the cloud
- **Provisioning** and **deprovisioning** of resources.
- **Orchestration tools** (e.g., Terraform, AWS CloudFormation).
- **Monitoring and alerting** (e.g., AWS CloudWatch, Azure Monitor).

### DevOps in cloud environments
- **DevOps Culture**: Collaboration between Dev and Ops teams.
- **CI/CD Pipelines**: Automate testing and deployments.
- **Infrastructure as Code (IaC)**: Define infrastructure through code templates.

### Environment maintenance
- **Patching**: Regular updates to OS, apps, and services.
- **Backup and Restore**: Regular backups and tested recovery processes.

### Policies and compliance relating to cloud operations
- **Data Sovereignty**: Respect country-specific data laws.
- **Retention Policies**: How long to store different types of data.
- **Disposal Policies**: Secure data deletion practices.

## 4. Governance, Risk, Compliance, and Security for the Cloud

### Risk management in cloud environments
- **Risk Assessment**: Identify potential threats and vulnerabilities.
- **BCP (Business Continuity Plan)**: Plan to keep operations running.
- **DRP (Disaster Recovery Plan)**: Recovery plan after major incidents.
- **Common Threats**: Data breaches, misconfigurations, insider threats.

### Compliance and regulatory concerns
- **GDPR**: General Data Protection Regulation (EU).
- **HIPAA**: Healthcare data protection (USA).
- **PCI DSS**: Payment card data protection.
- **SOX**: Financial reporting controls (USA).

### Cloud security concepts
- **Encryption**: Protect data at rest and in transit.
- **IAM (Identity and Access Management)**: Manage user permissions.
- **MFA (Multi-Factor Authentication)**: Strengthen authentication.

### Shared responsibility model
- **Provider Responsibilities**: Physical infra, network, hypervisor security.
- **Customer Responsibilities**: Application, data, access control security.

## Cheatsheet

| Term | Meaning |
|:-----|:--------|
| Elasticity | Auto-scaling of resources |
| SaaS | Software as a Service (e.g., Gmail) |
| PaaS | Platform as a Service (e.g., Heroku) |
| IaaS | Infrastructure as a Service (e.g., AWS EC2) |
| VPN | Virtual Private Network for secure access |
| DRP | Disaster Recovery Plan |
| BCP | Business Continuity Plan |

## Extra Notes
- **Vendor Lock-In**: Hard to switch cloud providers once deeply integrated.
- **Shadow IT**: Unauthorized cloud services being used inside organizations.
- **Migration Strategies**:
  - **Lift and Shift**: Move apps without changes.
  - **Refactor**: Modify apps for better cloud-native use.
- **Chargebacks vs Showbacks**:
  - **Chargeback**: Departments are billed for cloud usage.
  - **Showback**: Departments see cloud costs but are not billed directly.
