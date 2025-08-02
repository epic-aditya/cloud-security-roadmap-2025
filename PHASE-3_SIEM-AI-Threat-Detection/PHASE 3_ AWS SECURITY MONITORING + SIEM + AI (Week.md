# PHASE 3: AWS SECURITY MONITORING + SIEM + AI (Weeks 9-12)

## **Week 9: CloudTrail + Security Hub Integration**

### **CloudTrail Advanced Configuration**

- [ ] CloudTrail event structure and data events (Understand the anatomy of CloudTrail logs including management events, data events, and insight events)
    - [AWS CloudTrail User Guide](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/) | [CloudTrail Tutorial](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-tutorial.html)[^1]
- [ ] Multi-region CloudTrail setup with S3 encryption (Create organization-wide logging with proper encryption and access controls)
    - [Creating a CloudTrail Trail](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-create-a-trail-using-the-console-first-time.html)[^2] | [Beginner's Guide to AWS CloudTrail for Security](https://www.youtube.com/watch?v=1ZKuwyATV3c)[^3]
- [ ] CloudTrail Insights for anomaly detection (Enable ML-powered detection of unusual API activity patterns)
    - [CloudTrail Insights Documentation](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/logging-insights-events-with-cloudtrail.html) | [CloudTrail-Tracker Dashboard](https://www.mdpi.com/1424-8220/19/13/2952/pdf)[^4]


### **AWS Security Hub Configuration**

- [ ] Security Hub standards and compliance checks (Enable AWS Foundational Security Standard, CIS, and PCI DSS controls)
    - [AWS Security Hub Getting Started](https://docs.aws.amazon.com/securityhub/latest/userguide/securityhub-settingup.html) | [Security Hub Integration Guide](https://docs.aws.amazon.com/smc/latest/ag/config-security-hub.html)[^5]
- [ ] Custom insights and findings aggregation (Create custom queries to identify security trends and prioritize remediation)
    - [Security Hub Custom Insights](https://docs.aws.amazon.com/securityhub/latest/userguide/securityhub-insights.html) | [Third-party Integration Overview](https://docs.aws.amazon.com/securityhub/latest/partnerguide/integration-overview.html)[^6]
- [ ] Cross-account Security Hub management (Centralize security findings across multiple AWS accounts)
    - [Security Hub Multi-account Setup](https://docs.aws.amazon.com/securityhub/latest/userguide/securityhub-accounts.html) | [Organization Trail Creation](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/creating-trail-organization.html)[^7]


### **GuardDuty Threat Detection**

- [ ] GuardDuty setup and threat intelligence feeds (Enable ML-powered threat detection with global threat intelligence)
    - [Getting Started with GuardDuty](https://docs.aws.amazon.com/guardduty/latest/ug/guardduty_settingup.html)[^8] | [AWS GuardDuty Getting Started](https://aws.amazon.com/guardduty/getting-started/)[^9]
- [ ] GuardDuty Extended Threat Detection with AI/ML (Configure advanced attack sequence identification using artificial intelligence)
    - [GuardDuty Extended Threat Detection](https://aws.amazon.com/blogs/aws/introducing-amazon-guardduty-extended-threat-detection-aiml-attack-sequence-identification-for-enhanced-cloud-security/)[^10] | [AI/ML Threat Detection](https://aws.amazon.com/guardduty/)[^11]
- [ ] Custom threat detection rules and suppression (Create environment-specific detection rules and manage false positives)
    - [GuardDuty Custom Threat Lists](https://docs.aws.amazon.com/guardduty/latest/ug/guardduty_upload-lists.html) | [Fortifying Cloud Security with AWS](https://www.ijirmps.org/papers/2023/3/230230.pdf)[^12]


### **AWS Config and Compliance**

- [ ] Config rules for security compliance (Automate compliance checking against security baselines and standards)
    - [AWS Config Getting Started](https://docs.aws.amazon.com/config/latest/developerguide/getting-started.html) | [Config Security Best Practices](https://aws.amazon.com/blogs/security/how-to-use-aws-config-to-monitor-for-and-respond-to-amazon-s3-buckets-allowing-public-access/)
- [ ] Config remediation actions and automation (Set up automatic remediation for common misconfigurations)
    - [Config Remediation Actions](https://docs.aws.amazon.com/config/latest/developerguide/remediation.html) | [Automated Remediation Tutorial](https://aws.amazon.com/blogs/mt/aws-config-auto-remediation-s3-compliance/)
- [ ] Config conformance packs deployment (Deploy industry-standard compliance templates across accounts)
    - [Config Conformance Packs](https://docs.aws.amazon.com/config/latest/developerguide/conformance-packs.html) | [Conformance Pack Templates](https://github.com/awslabs/aws-config-rules/tree/master/aws-config-conformance-packs)


### **Hands-on Labs Setup**

- [ ] CloudTrail log analysis with CloudWatch Logs Insights (Practice querying CloudTrail data for security investigations)
    - [CloudWatch Logs Insights for CloudTrail](https://aws.amazon.com/blogs/mt/analyzing-aws-cloudtrail-in-amazon-cloudwatch/) | [Log Analysis Queries](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/AnalyzingLogData.html)
- [ ] Security Hub dashboard customization (Create executive-level security posture dashboards)
    - [Security Hub Dashboard](https://docs.aws.amazon.com/securityhub/latest/userguide/securityhub-insights.html) | [Custom Dashboard Tutorial](https://aws.amazon.com/blogs/security/how-to-build-a-multi-account-multi-region-dashboard-with-aws-security-hub/)


## **Week 10: AI-Enhanced IAM Analysis**

### **IAM Access Analyzer Deep Dive**

- [ ] Access Analyzer external access findings (Identify resources accessible from outside your AWS organization)
    - [IAM Access Analyzer Documentation](https://docs.aws.amazon.com/access-analyzer/latest/APIReference/Welcome.html)[^13] | [Access Analyzer Tutorial](https://www.youtube.com/watch?v=ksg9Hh00VMY)[^14]
- [ ] Unused access analysis and optimization (Discover dormant permissions and implement least privilege principles)
    - [Unused Access Analysis](https://aws.amazon.com/blogs/security/identify-unused-iam-roles-remove-confidently/) | [IAM Access Analyzer Simplifies Unused Access](https://www.youtube.com/watch?v=ksg9Hh00VMY)[^14]
- [ ] Policy generation from CloudTrail logs (Generate fine-grained policies based on actual access patterns)
    - [Policy Generation Guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_policy-generator.html) | [CloudTrail Policy Generation](https://aws.amazon.com/blogs/security/generate-iam-policies-based-on-access-activity/)


### **Amazon Detective Investigation**

- [ ] Detective data model and graph visualization (Understand how Detective correlates security events across time)
    - [Amazon Detective Documentation](https://docs.aws.amazon.com/detective/latest/userguide/) | [Detective Cheat Sheet](https://tutorialsdojo.com/amazon-detective/)[^15]
- [ ] Investigation workflows and finding correlation (Learn to trace attack paths and identify root causes)
    - [Detective Investigation Guide](https://docs.aws.amazon.com/detective/latest/userguide/detective-investigation.html) | [Amazon Detective Features](https://k21academy.com/amazon-web-services/amazon-detective/)[^16]
- [ ] Integration with GuardDuty and Security Hub findings (Create unified investigation workflows across security tools)
    - [Detective Multi-Service Integration](https://docs.aws.amazon.com/detective/latest/userguide/detective-source-data-about.html) | [Detective Data Collection](https://k21academy.com/amazon-web-services/amazon-detective/)[^16]


### **AI-Powered IAM Analysis Project**

- [ ] OpenAI API integration for credential report analysis (Build AI system to analyze IAM credential reports intelligently)
    - [OpenAI API Documentation](https://platform.openai.com/docs/api-reference) | [AWS Lambda with OpenAI Tutorial](https://aws.amazon.com/blogs/machine-learning/build-a-robust-text-based-nlp-model-with-amazon-sagemaker/)
- [ ] Automated policy risk assessment (Create ML models to identify overly permissive IAM policies)
    - [IAM Greybox Penetration Testing](http://arxiv.org/pdf/2304.14540.pdf)[^17] | [IAM Security Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)
- [ ] Intelligent permission recommendations (Develop AI system that suggests optimal permission sets)
    - [IAM Policy Optimization](https://aws.amazon.com/blogs/security/continuously-monitor-unused-iam-roles-with-iam-access-analyzer/) | [Machine Learning for Security](https://aws.amazon.com/machine-learning/security/)


### **Advanced IAM Security Patterns**

- [ ] Cross-account role analysis and optimization (Audit and optimize cross-account access patterns)
    - [Cross-Account IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/tutorial_cross-account-with-roles.html) | [Cross-Account Security Analysis](https://aws.amazon.com/blogs/security/how-to-use-aws-iam-access-analyzer-to-simplify-permissions-management/)
- [ ] Service-linked role governance (Manage AWS service permissions and minimize over-privileged access)
    - [Service-Linked Roles](https://docs.aws.amazon.com/IAM/latest/UserGuide/using-service-linked-roles.html) | [IAM Role Management](https://aws.amazon.com/blogs/security/how-to-control-access-to-aws-resources-based-on-aws-account-ou-or-organization/)
- [ ] ABAC (Attribute-Based Access Control) implementation (Implement dynamic access control using tags and attributes)
    - [ABAC with AWS](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction_attribute-based-access-control.html) | [ABAC Tutorial](https://aws.amazon.com/blogs/security/simplify-granting-access-to-your-aws-resources-by-using-tags-on-aws-iam-users-and-roles/)


### **Testing and Validation**

- [ ] IAM policy testing and simulation (Validate policy changes before deployment using simulation tools)
    - [IAM Policy Simulator](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_testing-policies.html) | [Policy Testing Best Practices](https://aws.amazon.com/blogs/security/use-iam-policy-simulator-to-grant-least-privilege-permissions/)
- [ ] Automated IAM compliance scanning (Build continuous monitoring for IAM compliance violations)
    - [IAM Compliance Automation](https://aws.amazon.com/blogs/security/how-to-create-an-aws-iam-account-assignment-with-automatic-cleanup/) | [Config Rules for IAM](https://docs.aws.amazon.com/config/latest/developerguide/managed-rules-by-aws-config.html)


## **Week 11: Event-Driven Security + AI Threat Detection**

### **EventBridge Security Patterns**

- [ ] EventBridge event patterns for security events (Create intelligent event routing based on security findings)
    - [EventBridge Event Patterns](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-event-patterns.html)[^18] | [Custom Event Patterns](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/eventbridge-using-events-rules-patterns.html)[^19]
- [ ] Security event correlation and aggregation (Build systems that connect related security events across services)
    - [EventBridge Security Use Cases](https://aws.amazon.com/blogs/security/how-to-use-amazon-eventbridge-to-build-decoupled-fault-tolerant-applications/) | [Event-Driven Architecture](https://aws.amazon.com/event-driven-architecture/)
- [ ] Custom event sources for security tools (Integrate third-party security tools with AWS event infrastructure)
    - [Custom EventBridge Sources](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-custom-event-sources.html) | [API Gateway EventBridge Integration](http://jier.org/index.php/journal/article/view/1711)[^20]


### **SNS/SQS Alert Routing**

- [ ] Multi-channel alerting with SNS (Route security alerts to appropriate teams via email, SMS, and Slack)
    - [SNS Multi-Protocol Messaging](https://docs.aws.amazon.com/sns/latest/dg/) | [SNS SQS Integration](https://docs.aws.amazon.com/sns/latest/dg/subscribe-sqs-queue-to-sns-topic.html)[^21]
- [ ] SQS dead letter queues for alert reliability (Ensure critical security alerts are never lost)
    - [SQS Dead Letter Queues](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-dead-letter-queues.html) | [S3 Bucket Notifications](https://docs.aws.amazon.com/AmazonS3/latest/userguide/ways-to-add-notification-config-to-bucket.html)[^22]
- [ ] Alert deduplication and rate limiting (Prevent alert fatigue while maintaining security visibility)
    - [SNS Message Deduplication](https://docs.aws.amazon.com/sns/latest/dg/fifo-message-dedup.html) | [EventBridge Message Filtering](https://aws.amazon.com/blogs/compute/filtering-event-patterns-in-amazon-eventbridge/)


### **Lambda Security Automation**

- [ ] Serverless security response functions (Build automated remediation for common security violations)
    - [Lambda Security Best Practices](https://docs.aws.amazon.com/lambda/latest/dg/lambda-security.html) | [PostgreSQL Serverless Architecture](https://ijmrset.com/upload/2_PostgreSQL.pdf)[^23]
- [ ] Lambda function security hardening (Secure your automation functions against attacks and misuse)
    - [Lambda Function Security](https://aws.amazon.com/blogs/security/defense-in-depth-open-firewalls-reverse-proxies-ssrf-vulnerabilities-ec2-instance-metadata-service/) | [Serverless Security Best Practices](https://aws.amazon.com/lambda/security/)
- [ ] Event-driven incident response automation (Create workflows that automatically respond to security incidents)
    - [Incident Response Automation](https://aws.amazon.com/blogs/security/how-to-automate-incident-response-in-the-aws-cloud-for-ec2-instances/) | [EventBridge Lambda Integration](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-lambda.html)


### **AI Threat Detection Implementation**

- [ ] OpenAI API integration for log analysis (Build AI system that can understand and categorize security events)
    - [OpenAI API Integration](https://platform.openai.com/docs/guides/text-generation) | [AI-Powered Security Analysis](https://aws.amazon.com/blogs/machine-learning/detect-anomalies-in-real-time-with-amazon-kinesis-data-analytics/)
- [ ] Bedrock Guardrails for prompt injection detection (Implement AWS native AI security for LLM interactions)
    - [Amazon Bedrock Guardrails](https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html) | [AI Security Best Practices](https://aws.amazon.com/blogs/machine-learning/responsible-ai-in-the-generative-ai-era/)
- [ ] Custom ML models for anomaly detection (Train models to detect unusual patterns specific to your environment)
    - [SageMaker Security Models](https://aws.amazon.com/sagemaker/security/) | [CloudWatch Anomaly Detection](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Anomaly_Detector.html)


### **Advanced Security Workflows**

- [ ] SOAR (Security Orchestration) integration (Connect AWS security tools with enterprise SOAR platforms)
    - [AWS Security Orchestration](https://aws.amazon.com/blogs/security/how-to-automate-forensic-disk-collection-in-aws/) | [Security Hub SOAR Integration](https://aws.amazon.com/blogs/security/how-to-set-up-two-way-integration-between-aws-security-hub-and-jira-service-management/)
- [ ] Threat hunting automation workflows (Build systems that proactively search for threats in your environment)
    - [Automated Threat Hunting](https://aws.amazon.com/blogs/security/how-to-approach-threat-detection-and-response-with-amazon-detective/) | [Threat Intelligence Integration](https://aws.amazon.com/blogs/security/how-to-use-aws-security-services-and-open-source-tools-for-threat-detection-and-incident-response/)
- [ ] Custom security metrics and KPIs (Create dashboards that track security posture improvements over time)
    - [CloudWatch Custom Metrics](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/publishingMetrics.html) | [Security Metrics Dashboard](https://aws.amazon.com/blogs/mt/create-a-multi-account-amazon-cloudwatch-dashboard/)


## **Week 12: PROJECT 3 - Serverless Threat Detection Dashboard**

### **Architecture Design and Planning**

- [ ] Serverless security architecture blueprint (Design scalable, cost-effective security monitoring infrastructure)
    - [AWS Well-Architected Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/) | [Serverless Security Reference](https://github.com/awslabs/aws-serverless-security-workshop)
- [ ] Data flow and event correlation design (Plan how security events flow and connect across your architecture)
    - [Event-Driven Architecture Patterns](https://aws.amazon.com/blogs/compute/building-resilient-serverless-patterns-by-combining-messaging-services/) | [Real-Time Event Processing](http://jier.org/index.php/journal/article/view/1711)[^20]
- [ ] Threat detection algorithm specification (Define the logic for identifying security threats using AI)
    - [Threat Detection Algorithms](https://aws.amazon.com/blogs/security/how-to-visualize-amazon-guardduty-findings-serverless-edition/) | [AI Threat Intelligence](https://aws.amazon.com/blogs/security/how-to-use-amazon-detective-to-analyze-and-investigate-security-findings/)


### **Data Ingestion and Processing**

- [ ] CloudTrail to EventBridge integration (Stream security events in real-time to processing pipeline)
    - [CloudTrail EventBridge Integration](https://aws.amazon.com/blogs/mt/monitor-aws-cloudtrail-events-using-amazon-eventbridge/) | [Event Processing Pipeline](https://aws.amazon.com/blogs/compute/building-serverless-applications-with-streaming-data-part-1/)
- [ ] Lambda data transformation functions (Clean, normalize, and enrich security event data)
    - [Lambda Data Processing](https://docs.aws.amazon.com/lambda/latest/dg/lambda-services.html) | [Serverless Data Pipeline](https://aws.amazon.com/blogs/big-data/build-a-serverless-data-lake-using-an-object-relational-mapping-orm-framework/)
- [ ] DynamoDB schema design for time-series security data (Store security events efficiently for analysis and querying)
    - [DynamoDB Time Series Design](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/bp-time-series.html) | [Security Event Storage Patterns](https://aws.amazon.com/blogs/database/analyzing-time-series-data-with-amazon-dynamodb-and-apache-spark/)


### **AI-Powered Threat Detection**

- [ ] OpenAI integration for anomaly scoring (Use AI to score the risk level of security events)
    - [OpenAI API for Security](https://platform.openai.com/docs/guides/safety-best-practices) | [AI Security Analysis](https://aws.amazon.com/blogs/machine-learning/build-a-real-time-ml-pipeline-to-predict-user-behavior/)
- [ ] Privilege escalation detection algorithms (Identify patterns indicating potential privilege escalation attacks)
    - [Privilege Escalation Detection](https://aws.amazon.com/blogs/security/how-to-receive-notifications-when-your-aws-account-root-access-keys-are-used/) | [IAM Attack Detection](http://arxiv.org/pdf/2304.14540.pdf)[^17]
- [ ] Unusual API activity correlation (Detect coordinated attacks across multiple AWS services)
    - [API Activity Analysis](https://aws.amazon.com/blogs/security/how-to-correlate-iam-user-activity-using-cloudtrail-and-identity-center-audit-logs/) | [Attack Pattern Recognition](https://aws.amazon.com/blogs/security/how-to-use-amazon-guardduty-to-take-a-deeper-dive-into-malicious-activity/)


### **Real-Time Visualization Dashboard**

- [ ] QuickSight security dashboard creation (Build executive-level security posture visualizations)
    - [QuickSight Security Analytics](https://docs.aws.amazon.com/quicksight/latest/user/security-overview.html) | [Security Dashboard Tutorial](https://aws.amazon.com/blogs/big-data/build-a-security-dashboard-using-amazon-elasticsearch-service-and-amazon-quicksight/)
- [ ] Real-time alert widgets and KPIs (Display live security metrics and threat indicators)
    - [CloudWatch Dashboard](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/create_dashboard.html) | [Real-Time Monitoring](https://aws.amazon.com/blogs/aws/amazon-cloudwatch-dashboards-create-and-use-customized-metrics-views/)
- [ ] Interactive investigation interfaces (Create drill-down capabilities for security analysts)
    - [Interactive Analytics](https://aws.amazon.com/blogs/big-data/build-interactive-queries-on-amazon-s3-data-lakes-using-amazon-redshift-spectrum/) | [Security Investigation Workflows](https://aws.amazon.com/blogs/security/aws-foundational-security-best-practices-standard-now-available-in-aws-security-hub/)


### **Automation and Response**

- [ ] Automated incident response playbooks (Create workflows that respond to threats automatically)
    - [Incident Response Automation](https://aws.amazon.com/blogs/security/how-to-automate-incident-response-in-aws/) | [Security Playbooks](https://github.com/awslabs/aws-incident-response-runbooks)
- [ ] Stakeholder notification automation (Ensure the right people are alerted based on threat severity)
    - [SNS Multi-Channel Alerts](https://docs.aws.amazon.com/sns/latest/dg/welcome.html) | [Alert Routing Best Practices](https://aws.amazon.com/blogs/mt/implementing-an-escalation-messaging-pattern-with-amazon-sns/)
- [ ] Compliance reporting automation (Generate automated compliance reports from security data)
    - [Automated Compliance](https://aws.amazon.com/blogs/security/how-to-use-aws-systems-manager-to-patch-and-secure-amazon-ec2-instances/) | [Security Reporting](https://aws.amazon.com/blogs/security/how-to-visualize-multi-account-amazon-inspector-findings-with-amazon-elasticsearch-service/)


### **Testing and Optimization**

- [ ] Load testing the detection pipeline (Ensure your system can handle production security event volumes)
    - [Serverless Load Testing](https://aws.amazon.com/blogs/compute/building-a-serverless-load-testing-tool/) | [Performance Optimization](https://aws.amazon.com/blogs/compute/operating-lambda-performance-optimization-part-1/)
- [ ] Cost optimization and monitoring (Implement cost controls for your serverless security infrastructure)
    - [Serverless Cost Optimization](https://aws.amazon.com/blogs/compute/optimizing-your-aws-lambda-costs-part-1/) | [AWS Cost Optimization](https://ieeexplore.ieee.org/document/10527314/)[^24]
- [ ] Security testing of the security system (Ensure your threat detection system is secure against attacks)
    - [Security Testing Best Practices](https://aws.amazon.com/blogs/security/how-to-approach-threat-modeling/) | [Serverless Security Testing](https://aws.amazon.com/blogs/compute/securing-serverless-applications/)


### **Week 12 Deliverables**

- **GitHub repo:** `serverless-threat-detection-dashboard`
- **AI Component:** Real-time threat scoring and analysis engine
- Complete serverless security monitoring platform
- Executive security dashboard with live metrics
- **📱 LinkedIn Action:** Share screen recording of AI threat detection in action with analysis of detected patterns

[^1]: https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-tutorial.html

[^2]: https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-create-a-trail-using-the-console-first-time.html

[^3]: https://www.youtube.com/watch?v=1ZKuwyATV3c

[^4]: https://www.mdpi.com/1424-8220/19/13/2952/pdf

[^5]: https://docs.aws.amazon.com/smc/latest/ag/config-security-hub.html

[^6]: https://docs.aws.amazon.com/securityhub/latest/partnerguide/integration-overview.html

[^7]: https://docs.aws.amazon.com/awscloudtrail/latest/userguide/creating-trail-organization.html

[^8]: https://docs.aws.amazon.com/guardduty/latest/ug/guardduty_settingup.html

[^9]: https://aws.amazon.com/guardduty/getting-started/

[^10]: https://aws.amazon.com/blogs/aws/introducing-amazon-guardduty-extended-threat-detection-aiml-attack-sequence-identification-for-enhanced-cloud-security/

[^11]: https://aws.amazon.com/guardduty/

[^12]: https://www.ijirmps.org/papers/2023/3/230230.pdf

[^13]: https://docs.aws.amazon.com/access-analyzer/latest/APIReference/Welcome.html

[^14]: https://www.youtube.com/watch?v=ksg9Hh00VMY

[^15]: https://tutorialsdojo.com/amazon-detective/

[^16]: https://k21academy.com/amazon-web-services/amazon-detective/

[^17]: http://arxiv.org/pdf/2304.14540.pdf

[^18]: https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-event-patterns.html

[^19]: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/eventbridge-using-events-rules-patterns.html

[^20]: http://jier.org/index.php/journal/article/view/1711

[^21]: https://docs.aws.amazon.com/sns/latest/dg/subscribe-sqs-queue-to-sns-topic.html

[^22]: https://docs.aws.amazon.com/AmazonS3/latest/userguide/ways-to-add-notification-config-to-bucket.html

[^23]: https://ijmrset.com/upload/2_PostgreSQL.pdf

[^24]: https://ieeexplore.ieee.org/document/10527314/

[^25]: Cloud-Security-Engineering-Roadmap.md

[^26]: https://onlinelibrary.wiley.com/unavailable-obooks

[^27]: https://www.semanticscholar.org/paper/739268a56160ff6c26a1630cc2af2303efe6a584

[^28]: https://www.protocols.io/view/mind-pipeline-aws-ec2-installation-and-setup-b3f6qjre

[^29]: https://www.protocols.io/view/mind-pipeline-aws-ec2-installation-and-setup-b2s8qehw

[^30]: https://onlinelibrary.wiley.com/doi/10.1002/9781119560395.ch7

[^31]: https://www.srinivaspublication.com/journal/index.php/ijcsbe/article/view/2283/875

[^32]: https://www.srinivaspublication.com/journal/index.php/ijmts/article/view/2321/881

[^33]: https://dx.plos.org/10.1371/journal.pone.0278316

[^34]: http://arxiv.org/pdf/2401.16545.pdf

[^35]: https://gigabytejournal.com/articles/133

[^36]: http://arxiv.org/pdf/2402.15632.pdf

[^37]: https://arxiv.org/pdf/2302.11617.pdf

[^38]: https://pmc.ncbi.nlm.nih.gov/articles/PMC9910747/

[^39]: https://pmc.ncbi.nlm.nih.gov/articles/PMC11638732/

[^40]: https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-settings.html

[^41]: https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-create-and-update-a-trail.html

