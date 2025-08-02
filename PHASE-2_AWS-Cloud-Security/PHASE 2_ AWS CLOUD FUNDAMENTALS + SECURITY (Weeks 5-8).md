# PHASE 2: AWS CLOUD FUNDAMENTALS + SECURITY (Weeks 5-8)

## **Week 5: AWS Foundation + Cost Controls**

### **AWS Global Infrastructure \& Core Concepts**

- [ ] AWS Regions and Availability Zones (Understand geographic distribution and how to choose optimal regions for latency/compliance)
    - [AWS Global Infrastructure Overview](https://aws.amazon.com/about-aws/global-infrastructure/) | [Stephane Maarek's AWS Course - Regions](https://www.udemy.com/course/aws-certified-cloud-practitioner-new/)
- [ ] Edge Locations and CloudFront basics (Learn how CDN improves performance and reduces latency globally)
    - [AWS CloudFront Documentation](https://docs.aws.amazon.com/cloudfront/) | [TechWorld with Nana - CloudFront Explained](https://www.youtube.com/watch?v=AT-nHW3_SVI)
- [ ] AWS Well-Architected Framework pillars (Security, Reliability, Performance, Cost, Operational Excellence, Sustainability)
    - [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/) | [AWS Well-Architected Tool hands-on](https://aws.amazon.com/well-architected-tool/)


### **Core AWS Services Foundation**

- [ ] EC2 instance types and families (Understand when to use compute-optimized vs memory-optimized vs storage-optimized)
    - [AWS EC2 Instance Types Guide](https://aws.amazon.com/ec2/instance-types/) | [AWS Training - EC2 Basics](https://aws.amazon.com/training/course-descriptions/ec2-basics/)
- [ ] S3 storage classes and use cases (Know the difference between Standard, IA, Glacier, and Deep Archive for cost optimization)
    - [AWS S3 Storage Classes](https://aws.amazon.com/s3/storage-classes/) | [Cloud Guru S3 Deep Dive](https://acloudguru.com/course/amazon-s3-deep-dive)
- [ ] VPC fundamentals and default networking (Understand how AWS networking works out-of-the-box)
    - [AWS VPC User Guide](https://docs.aws.amazon.com/vpc/latest/userguide/) | [Networking in AWS Tutorial](https://www.youtube.com/watch?v=hiKPPy584Mg)


### **AWS Account Security Setup**

- [ ] Root account security and MFA setup (Secure your root account and understand why you should never use it for daily tasks)
    - [AWS Root Account Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#lock-away-your-aws-account-root-user-access-keys) | [Enable MFA for Root Account](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_enable_virtual.html)
- [ ] AWS CloudTrail initial setup (Enable logging of all API calls for security monitoring and compliance)
    - [AWS CloudTrail User Guide](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/) | [CloudTrail Setup Tutorial](https://www.youtube.com/watch?v=YWzmoDcTP-g)
- [ ] AWS Config service basics (Understand how to track configuration changes and compliance)
    - [AWS Config Getting Started](https://docs.aws.amazon.com/config/latest/developerguide/) | [AWS Config Hands-on Lab](https://aws.amazon.com/getting-started/hands-on/getting-started-with-aws-config/)


### **Cost Management \& Billing**

- [ ] AWS Free Tier limits and monitoring (Know exactly what's free and set up alerts before charges occur)
    - [AWS Free Tier Details](https://aws.amazon.com/free/) | [AWS Billing and Cost Management Tutorial](https://www.youtube.com/watch?v=Ris23gKc7s0)
- [ ] Setting up billing alerts and budgets (Create proactive cost monitoring to avoid surprise charges)
    - [AWS Budgets User Guide](https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-managing-costs.html) | [Setting Up Billing Alerts](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html)
- [ ] AWS Cost Explorer navigation (Learn to analyze spending patterns and identify cost optimization opportunities)
    - [AWS Cost Explorer User Guide](https://docs.aws.amazon.com/cost-management/latest/userguide/ce-what-is.html) | [Cost Explorer Walkthrough](https://www.youtube.com/watch?v=XgUB_yCesoI)
- [ ] AWS Trusted Advisor basics (Understand how to get automated recommendations for cost, security, and performance)
    - [AWS Trusted Advisor](https://aws.amazon.com/premiumsupport/technology/trusted-advisor/) | [Trusted Advisor Tutorial](https://aws.amazon.com/getting-started/hands-on/trusted-advisor-tutorial/)


### **Hands-on Labs Setup**

- [ ] Launch and connect to first EC2 instance (Practice the fundamental skill of spinning up compute resources)
    - [EC2 Getting Started Guide](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html) | [AWS Hands-on Labs - EC2](https://aws.amazon.com/getting-started/hands-on/launch-a-virtual-machine/)
- [ ] Create S3 bucket with proper naming conventions (Learn object storage fundamentals and naming best practices)
    - [S3 Getting Started Guide](https://docs.aws.amazon.com/AmazonS3/latest/userguide/GetStartedWithS3.html) | [S3 Bucket Creation Tutorial](https://www.youtube.com/watch?v=e6w9LwZJFIA)


## **Week 6: IAM Deep Dive + Role-Based Access**

### **IAM Core Concepts**

- [ ] IAM Users vs Service Accounts vs Federated Users (Understand different identity types and when to use each)
    - [AWS IAM User Guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/) | [IAM Identities Deep Dive](https://www.youtube.com/watch?v=SXSqhTn2DuE)
- [ ] IAM Groups and permission inheritance (Learn how to organize users efficiently and avoid permission sprawl)
    - [IAM Groups Documentation](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_groups.html) | [IAM Best Practices Video](https://www.youtube.com/watch?v=YQsK4MtsELU)
- [ ] IAM Roles and temporary security credentials (Master the concept of assuming roles for cross-service access)
    - [IAM Roles Documentation](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles.html) | [AWS IAM Roles Explained](https://www.youtube.com/watch?v=N6YVD16oG_c)


### **IAM Policies Deep Dive**

- [ ] AWS managed vs customer managed vs inline policies (Know when to use each policy type and their trade-offs)
    - [IAM Policies Overview](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html) | [IAM Policy Types Tutorial](https://www.youtube.com/watch?v=iF9fs8Rw4Uo)
- [ ] Policy structure and JSON syntax (Master the anatomy of IAM policies: Effect, Action, Resource, Condition)
    - [IAM Policy Language](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_elements.html) | [IAM Policy Grammar Tutorial](https://www.youtube.com/watch?v=Iq_hDc385t4)
- [ ] Policy evaluation logic and precedence (Understand how AWS determines if an action is allowed or denied)
    - [Policy Evaluation Logic](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_evaluation-logic.html) | [IAM Policy Evaluation Explained](https://www.youtube.com/watch?v=A4FyHKE_Sq0)
- [ ] IAM Policy Variables and conditions (Learn to create dynamic policies based on context like time, IP, MFA)
    - [IAM Policy Variables](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_variables.html) | [Conditional IAM Policies](https://www.youtube.com/watch?v=8eoP1Cci0pI)


### **Access Control Patterns**

- [ ] Principle of least privilege implementation (Practice giving minimum necessary permissions for specific tasks)
    - [Least Privilege Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege) | [Zero Trust Security Model](https://www.youtube.com/watch?v=FMMWSLIcaME)
- [ ] Cross-account access with roles (Set up secure access between different AWS accounts)
    - [Cross-Account Access](https://docs.aws.amazon.com/IAM/latest/UserGuide/tutorial_cross-account-with-roles.html) | [Cross-Account Role Tutorial](https://www.youtube.com/watch?v=ZPXf5OZhe4s)
- [ ] Service-linked roles vs service roles (Understand when AWS creates roles automatically vs when you control them)
    - [Service-Linked Roles](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_terms-and-concepts.html#iam-term-service-linked-role) | [Service Roles Explained](https://www.youtube.com/watch?v=uFSadISiWcU)


### **IAM Security Features**

- [ ] MFA enforcement policies (Create policies that require multi-factor authentication for sensitive actions)
    - [MFA for IAM Users](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa.html) | [Conditional MFA Policies](https://aws.amazon.com/blogs/security/how-to-use-a-variable-in-an-iam-policy-to-restrict-access-to-specific-mfa-types/)
- [ ] Access Keys rotation and management (Implement secure API key lifecycle management)
    - [Access Key Rotation](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html#Using_RotateAccessKey) | [Automated Key Rotation](https://aws.amazon.com/blogs/security/how-to-rotate-access-keys-for-iam-users/)
- [ ] IAM Access Analyzer findings interpretation (Use ML-powered analysis to identify overly permissive access)
    - [IAM Access Analyzer](https://docs.aws.amazon.com/IAM/latest/UserGuide/what-is-access-analyzer.html) | [Access Analyzer Tutorial](https://www.youtube.com/watch?v=i5apYXya2m0)


### **Testing and Validation**

- [ ] IAM Policy Simulator usage (Test policies before deployment to avoid access issues)
    - [Policy Simulator](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_testing-policies.html) | [Policy Simulator Walkthrough](https://www.youtube.com/watch?v=1IIhVcXhvcE)
- [ ] CloudTrail integration for IAM auditing (Track who did what with IAM permissions)
    - [IAM with CloudTrail](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-event-reference-iam.html) | [IAM Auditing Best Practices](https://aws.amazon.com/blogs/security/aws-iam-best-practices-to-live-by/)


## **Week 7: VPC Architecture + Network Security**

### **VPC Core Architecture**

- [ ] VPC CIDR block planning and IPv4 addressing (Design scalable network addressing schemes for enterprise use)
    - [VPC CIDR Blocks](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html#VPC_Sizing) | [Network Planning for AWS](https://www.youtube.com/watch?v=LX5lHYGFcnA)
- [ ] Public vs Private vs Isolated subnets (Understand the three-tier architecture and when to use each subnet type)
    - [VPC Subnets](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html) | [AWS VPC Architecture Patterns](https://www.youtube.com/watch?v=jZAvKgqlrjY)
- [ ] Availability Zone distribution strategy (Design for high availability and fault tolerance)
    - [AZ Best Practices](https://docs.aws.amazon.com/whitepapers/latest/aws-vpc-connectivity-options/network-to-amazon-vpc-connectivity-options.html) | [Multi-AZ Architecture](https://aws.amazon.com/builders-library/static-stability-using-availability-zones/)


### **Routing and Gateways**

- [ ] Route Tables and routing priority (Master how traffic flows through your VPC)
    - [Route Tables](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Route_Tables.html) | [VPC Routing Deep Dive](https://www.youtube.com/watch?v=tbwD5IaJMvM)
- [ ] Internet Gateway setup and routing (Enable internet access for public resources)
    - [Internet Gateways](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Internet_Gateway.html) | [IGW Configuration Tutorial](https://www.youtube.com/watch?v=IfTBN8DP6dY)
- [ ] NAT Gateway vs NAT Instance (Choose the right solution for private subnet internet access)
    - [NAT Gateways](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-gateway.html) | [NAT Gateway vs NAT Instance](https://www.youtube.com/watch?v=AqNtZ5S3XtI)


### **Network Security Controls**

- [ ] Security Groups rules and best practices (Master stateful firewall rules at the instance level)
    - [Security Groups](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security-groups.html) | [Security Groups Tutorial](https://www.youtube.com/watch?v=XTgqrHvf8QE)
- [ ] Network ACLs configuration and use cases (Implement stateless subnet-level security)
    - [Network ACLs](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html) | [NACLs vs Security Groups](https://www.youtube.com/watch?v=BZEYmsTSZHU)
- [ ] Security Groups vs NACLs comparison (Know when to use each and how they work together)
    - [Security Groups vs NACLs](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Security.html) | [AWS Network Security Layers](https://aws.amazon.com/blogs/security/one-to-many-evolving-vpc-design/)


### **VPC Monitoring and Logging**

- [ ] VPC Flow Logs configuration (Capture network traffic metadata for security analysis)
    - [VPC Flow Logs](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html) | [Flow Logs Analysis Tutorial](https://www.youtube.com/watch?v=atjF1Vuj-rg)
- [ ] CloudWatch integration for network monitoring (Set up automated alerts for network anomalies)
    - [VPC CloudWatch Metrics](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/aws-services-cloudwatch-metrics.html) | [Network Monitoring with CloudWatch](https://www.youtube.com/watch?v=vAnIhIwE5hY)
- [ ] Network traffic analysis with Flow Logs (Learn to detect suspicious patterns and security incidents)
    - [Flow Logs Analysis](https://aws.amazon.com/blogs/aws/vpc-flow-logs-log-and-view-network-traffic-flows/) | [Security Analysis with Flow Logs](https://www.youtube.com/watch?v=5MHfrcd8Tks)


### **Advanced VPC Features**

- [ ] VPC Endpoints (Gateway and Interface) (Securely connect to AWS services without internet routing)
    - [VPC Endpoints](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-endpoints.html) | [VPC Endpoints Deep Dive](https://www.youtube.com/watch?v=OMqVTZ8GYJI)
- [ ] PrivateLink service connectivity (Create secure, private connections between VPCs and services)
    - [AWS PrivateLink](https://docs.aws.amazon.com/vpc/latest/userguide/vpce-interface.html) | [PrivateLink Tutorial](https://www.youtube.com/watch?v=qrDBSv34W2Q)
- [ ] VPC Peering fundamentals (Connect VPCs within and across regions securely)
    - [VPC Peering](https://docs.aws.amazon.com/vpc/latest/peering/) | [VPC Peering Best Practices](https://www.youtube.com/watch?v=LX5lHYGFcnA)


## **Week 8: PROJECT 2 - Secure Static Website Hosting**

### **S3 Static Website Configuration**

- [ ] S3 bucket policies for website hosting (Configure public read access while maintaining security)
    - [S3 Static Website Hosting](https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html) | [S3 Website Tutorial](https://www.youtube.com/watch?v=KE2LpzGMkdM)
- [ ] S3 bucket versioning and lifecycle policies (Implement proper content management and cost optimization)
    - [S3 Versioning](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Versioning.html) | [S3 Lifecycle Management](https://www.youtube.com/watch?v=TYP-aQyMkzI)
- [ ] S3 server-side encryption configuration (Protect data at rest with proper encryption)
    - [S3 Encryption](https://docs.aws.amazon.com/AmazonS3/latest/userguide/bucket-encryption.html) | [S3 Security Best Practices](https://aws.amazon.com/blogs/security/top-10-security-best-practices-for-securing-data-in-amazon-s3/)


### **CloudFront CDN Setup**

- [ ] CloudFront distribution creation and configuration (Set up global content delivery for performance)
    - [CloudFront Getting Started](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/GettingStarted.html) | [CloudFront Tutorial](https://www.youtube.com/watch?v=XwqEb8YQQQA)
- [ ] Custom SSL certificate with ACM (Implement HTTPS with AWS Certificate Manager)
    - [ACM with CloudFront](https://docs.aws.amazon.com/acm/latest/userguide/gs-acm-request-public.html) | [SSL Certificate Setup](https://www.youtube.com/watch?v=m6cMLJwS-OU)
- [ ] CloudFront security headers and HTTPS redirection (Implement security best practices for web applications)
    - [CloudFront Security Headers](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/using-managed-response-headers-policies.html) | [Web Security Headers Tutorial](https://www.youtube.com/watch?v=F24Z1DWwIIw)


### **DNS and Domain Management**

- [ ] Route 53 hosted zone configuration (Set up authoritative DNS for your domain)
    - [Route 53 Getting Started](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/getting-started.html) | [Route 53 Tutorial](https://www.youtube.com/watch?v=RGWgfhZByAI)
- [ ] DNS record types and routing policies (Understand A, CNAME, ALIAS records and when to use each)
    - [Route 53 Record Types](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/ResourceRecordTypes.html) | [DNS Records Explained](https://www.youtube.com/watch?v=dl-C6cBoRg4)
- [ ] Route 53 health checks and failover (Implement DNS-based high availability)
    - [Route 53 Health Checks](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/dns-failover.html) | [DNS Failover Tutorial](https://www.youtube.com/watch?v=1nce_3xtbIo)


### **Web Application Firewall (WAF)**

- [ ] AWS WAF core concepts and rule types (Understand how to protect against OWASP Top 10 threats)
    - [AWS WAF Developer Guide](https://docs.aws.amazon.com/waf/latest/developerguide/) | [WAF Tutorial](https://www.youtube.com/watch?v=nUI7G9UmVGY)
- [ ] AWS Managed Rules for common threats (Implement pre-built protection against known attack patterns)
    - [AWS WAF Managed Rules](https://docs.aws.amazon.com/waf/latest/developerguide/aws-managed-rule-groups.html) | [WAF Managed Rules Setup](https://www.youtube.com/watch?v=9t6sNXQIHdI)
- [ ] Custom WAF rules and rate limiting (Create application-specific protection rules)
    - [Custom WAF Rules](https://docs.aws.amazon.com/waf/latest/developerguide/waf-rules.html) | [Rate Limiting with WAF](https://aws.amazon.com/blogs/security/three-most-important-aws-waf-rate-based-rules/)


### **Infrastructure as Code**

- [ ] CloudFormation template structure (Write declarative infrastructure definitions)
    - [CloudFormation User Guide](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/) | [CloudFormation Tutorial](https://www.youtube.com/watch?v=6R44BADNJA8)
- [ ] CloudFormation parameters and outputs (Make templates reusable and modular)
    - [CloudFormation Parameters](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/parameters-section-structure.html) | [CloudFormation Best Practices](https://www.youtube.com/watch?v=9Xpuprxg7aY)
- [ ] CloudFormation stack deployment and updates (Manage infrastructure changes safely)
    - [CloudFormation Stack Operations](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/stacks.html) | [Stack Update Strategies](https://aws.amazon.com/blogs/devops/implementing-safe-aws-cloudformation-deployments-with-aws-codepipeline/)


### **Security and Monitoring**

- [ ] CloudTrail logging for website operations (Track all API calls related to your infrastructure)
    - [CloudTrail S3 Events](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/logging-data-events-with-cloudtrail.html) | [CloudTrail Security Monitoring](https://www.youtube.com/watch?v=tkAMt_Jc4pE)
- [ ] CloudWatch monitoring and alerting (Set up proactive monitoring for availability and performance)
    - [CloudWatch for Web Applications](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/) | [CloudWatch Alarms Tutorial](https://www.youtube.com/watch?v=LQoCZf2eKwU)
- [ ] Cost analysis and optimization (Monitor spending and implement cost reduction strategies)
    - [AWS Cost Explorer](https://docs.aws.amazon.com/cost-management/latest/userguide/ce-what-is.html) | [Cost Optimization for Static Websites](https://aws.amazon.com/blogs/networking-and-content-delivery/optimizing-costs-for-amazon-cloudfront/)



