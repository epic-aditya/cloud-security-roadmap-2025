# PHASE 4: AZURE + AI SECURITY PROJECTS (Weeks 13-16)

*Expanding to Azure with cutting-edge AI security*

## **Week 13: Azure Fundamentals + Identity Management**

### **Azure Global Infrastructure**

- [ ] Azure regions and availability zones (Understand geographic distribution and compliance requirements for data residency)
    - [Azure Global Infrastructure](https://docs.microsoft.com/en-us/azure/networking/microsoft-global-network) | [Azure Geography Overview](https://azure.microsoft.com/en-us/global-infrastructure/geographies/)
- [ ] Azure resource hierarchy (Learn how subscriptions, resource groups, and resources organize your Azure environment)
    - [Azure Resource Manager Overview](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/overview) | [Azure Fundamentals Learning Path](https://docs.microsoft.com/en-us/learn/paths/azure-fundamentals/)
- [ ] Azure service categories and core offerings (Understand compute, networking, storage, and database services for security context)
    - [Azure Services Overview](https://azure.microsoft.com/en-us/services/) | [Azure Services Tutorial](https://www.youtube.com/watch?v=NKEFWyqJ5XA)


### **Azure Active Directory Deep Dive**

- [ ] Azure AD vs Active Directory Domain Services (Understand the difference between cloud identity and on-premises identity)
    - [Azure AD vs AD DS](https://docs.microsoft.com/en-us/azure/active-directory-domain-services/compare-identity-solutions) | [Azure AD Fundamentals](https://www.youtube.com/watch?v=Ma7VAQE7ga4)
- [ ] Azure AD tenant configuration and custom domains (Set up your identity foundation with proper domain verification)
    - [Azure AD Tenant Setup](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-access-create-new-tenant) | [Custom Domain Configuration](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/add-custom-domain)
- [ ] User and group management at scale (Learn to manage identities efficiently using groups and administrative units)
    - [Azure AD User Management](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/add-users-azure-active-directory) | [Group Management Best Practices](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-manage-groups)


### **Conditional Access and Zero Trust**

- [ ] Conditional Access policy components (Master the conditions, assignments, and controls for risk-based access)
    - [Conditional Access Documentation](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/) | [Conditional Access Tutorial](https://www.youtube.com/watch?v=LoFaAJNbb88)
- [ ] Multi-factor authentication configuration (Implement MFA for all users with appropriate methods and policies)
    - [Azure AD MFA Setup](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-getstarted) | [MFA Security Best Practices](https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-mfa-howitworks)
- [ ] Zero Trust architecture implementation (Design identity-centric security following never trust, always verify principles)
    - [Zero Trust with Azure AD](https://docs.microsoft.com/en-us/azure/security/fundamentals/zero-trust) | [Zero Trust Security Model](https://www.youtube.com/watch?v=FMMWSLIcaME)


### **Service Principals and Managed Identities**

- [ ] Service principal creation and management (Understand application identities for automated access)
    - [Service Principals Documentation](https://docs.microsoft.com/en-us/azure/active-directory/develop/app-objects-and-service-principals) | [Service Principal Tutorial](https://www.youtube.com/watch?v=WVNvoiA_ktw)
- [ ] System-assigned vs User-assigned managed identities (Choose the right identity type for Azure resources)
    - [Managed Identities Overview](https://docs.microsoft.com/en-us/azure/active-directory/managed-identities-azure-resources/overview) | [Managed Identity Best Practices](https://docs.microsoft.com/en-us/azure/active-directory/managed-identities-azure-resources/managed-identities-best-practice-recommendations)
- [ ] Azure RBAC role assignments and custom roles (Implement least privilege access using built-in and custom roles)
    - [Azure RBAC Documentation](https://docs.microsoft.com/en-us/azure/role-based-access-control/) | [Custom Roles Tutorial](https://www.youtube.com/watch?v=C-JiVYl4jOw)


### **Azure Cost Management**

- [ ] Azure pricing models and cost optimization (Understand pay-as-you-go, reservations, and spot pricing)
    - [Azure Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/) | [Cost Management Best Practices](https://docs.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-best-practices)
- [ ] Azure Cost Management and budgets (Set up cost monitoring and automated budget alerts)
    - [Azure Cost Management](https://docs.microsoft.com/en-us/azure/cost-management-billing/) | [Budget Setup Tutorial](https://www.youtube.com/watch?v=UrkHiUx19Po)


### **Hands-on Lab Setup**

- [ ] Azure Free Tier account setup with security hardening (Create account with proper security configurations)
    - [Azure Free Account](https://azure.microsoft.com/en-us/free/) | [Azure Account Security](https://docs.microsoft.com/en-us/azure/security/fundamentals/account-setup)
- [ ] First Azure resource deployment (Deploy a simple resource to understand Azure Resource Manager)
    - [Deploy Your First Resource](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/quickstart-create-templates-use-the-portal) | [Azure Resource Manager Tutorial](https://www.youtube.com/watch?v=Ge_Sp-1lWZ4)


## **Week 14: App Service + LLM Security Lab**

### **Azure App Service Security**

- [ ] App Service authentication and authorization (Configure built-in authentication with Azure AD integration)
    - [App Service Authentication](https://docs.microsoft.com/en-us/azure/app-service/overview-authentication-authorization) | [App Service Security Tutorial](https://www.youtube.com/watch?v=4BwyqmRTrx8)
- [ ] Custom domains and SSL certificates (Secure your applications with proper TLS configuration)
    - [Custom Domains in App Service](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-tutorial-custom-domain) | [SSL Certificate Tutorial](https://docs.microsoft.com/en-us/azure/app-service/configure-ssl-certificate)
- [ ] Application security features and hardening (Implement security headers, IP restrictions, and network isolation)
    - [App Service Security Features](https://docs.microsoft.com/en-us/azure/app-service/overview-security) | [Web App Security Best Practices](https://docs.microsoft.com/en-us/azure/security/fundamentals/paas-applications-using-app-services)


### **OWASP Top 10 for LLMs**

- [ ] LLM01 - Prompt injection vulnerabilities (Understand how malicious prompts can manipulate AI models)
    - [OWASP Top 10 for LLMs](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | [Prompt Injection Examples](https://github.com/TakSec/Prompt-Injection-Everywhere)
- [ ] LLM02 - Insecure output handling (Learn how to validate and sanitize LLM outputs)
    - [Insecure Output Handling](https://owasp.org/www-project-top-10-for-large-language-model-applications/assets/PDF/OWASP-Top-10-for-LLMs-2023-v1_1.pdf) | [LLM Security Guide](https://www.youtube.com/watch?v=Pq7M9QdFbI0)
- [ ] LLM03 - Training data poisoning and LLM06 - Sensitive information disclosure (Understand data security risks in AI systems)
    - [Training Data Security](https://arxiv.org/abs/2401.05566) | [AI Security Best Practices](https://docs.microsoft.com/en-us/azure/ai-services/security-features)


### **Prompt Injection Testing Lab**

- [ ] Flask application with OpenAI integration (Build a vulnerable LLM application for security testing)
    - [Flask OpenAI Tutorial](https://platform.openai.com/docs/quickstart?context=python) | [Building AI Apps with Flask](https://www.youtube.com/watch?v=kNMVXxzfetU)
- [ ] Direct prompt injection attack vectors (Test techniques like role-playing, context switching, and system override)
    - [Prompt Injection Techniques](https://github.com/FonduAI/awesome-prompt-injection) | [Adversarial Prompting Guide](https://www.promptingguide.ai/risks/adversarial)
- [ ] Indirect prompt injection through user input (Test how external data sources can manipulate AI behavior)
    - [Indirect Prompt Injection](https://kai-greshake.de/posts/inject-my-pdf/) | [LLM Security Testing](https://embracethered.com/blog/posts/2023/ai-injections-direct-and-indirect-prompt-injections-and-their-implications/)


### **Cross-Cloud Identity Federation**

- [ ] Azure AD and AWS IAM integration (Set up SAML federation between Azure AD and AWS)
    - [Azure AD AWS Integration](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/amazon-web-service-tutorial) | [Cross-Cloud Federation](https://aws.amazon.com/blogs/security/enabling-federation-to-aws-using-windows-active-directory-adfs-and-saml-2-0/)
- [ ] Google Cloud identity integration (Configure federated identity across all three major clouds)
    - [Azure AD Google Cloud Integration](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/google-apps-tutorial) | [Multi-Cloud Identity](https://cloud.google.com/architecture/identity/federating-gcp-with-azure-active-directory)
- [ ] Identity governance across clouds (Implement consistent identity policies across platforms)
    - [Azure AD Governance](https://docs.microsoft.com/en-us/azure/active-directory/governance/) | [Cross-Cloud Identity Strategy](https://www.youtube.com/watch?v=LXwgXI4QlWY)


### **AI Security Defense Implementation**

- [ ] Input validation and sanitization for LLMs (Implement robust filtering of user inputs before AI processing)
    - [Input Validation Best Practices](https://docs.microsoft.com/en-us/azure/security/develop/secure-develop#validate-all-inputs) | [AI Input Security](https://github.com/leondz/garak)
- [ ] Output filtering and content safety (Use Azure Content Safety or similar services to filter AI responses)
    - [Azure Content Safety](https://docs.microsoft.com/en-us/azure/cognitive-services/content-safety/) | [AI Content Moderation](https://www.youtube.com/watch?v=tAr4N1ThZBA)
- [ ] Rate limiting and usage monitoring (Implement controls to prevent abuse and monitor AI usage patterns)
    - [API Management Rate Limiting](https://docs.microsoft.com/en-us/azure/api-management/api-management-access-restriction-policies) | [AI Usage Monitoring](https://docs.microsoft.com/en-us/azure/cognitive-services/diagnostic-logging)


## **Week 15: Azure Sentinel + Security Monitoring**

### **Azure Sentinel SIEM Setup**

- [ ] Sentinel workspace configuration and data connectors (Set up centralized logging from multiple sources)
    - [Azure Sentinel Getting Started](https://docs.microsoft.com/en-us/azure/sentinel/quickstart-onboard) | [Sentinel Data Connectors](https://docs.microsoft.com/en-us/azure/sentinel/connect-data-sources)
- [ ] Log Analytics workspace optimization (Configure retention, pricing tier, and access controls)
    - [Log Analytics Workspace](https://docs.microsoft.com/en-us/azure/azure-monitor/logs/design-logs-deployment) | [Workspace Security](https://docs.microsoft.com/en-us/azure/azure-monitor/logs/manage-access)
- [ ] Microsoft security service integration (Connect Defender, Azure AD, and other Microsoft security tools)
    - [Microsoft 365 Defender Integration](https://docs.microsoft.com/en-us/azure/sentinel/connect-microsoft-365-defender) | [Security Service Integration](https://www.youtube.com/watch?v=WGtIT6HuS8g)


### **KQL (Kusto Query Language) Mastery**

- [ ] KQL syntax and basic operators (Master the query language for security investigations)
    - [KQL Quick Reference](https://docs.microsoft.com/en-us/azure/data-explorer/kql-quick-reference) | [KQL Tutorial](https://docs.microsoft.com/en-us/azure/data-explorer/kusto/query/tutorial)
- [ ] Advanced KQL for threat hunting (Create complex queries to identify attack patterns)
    - [KQL for Cybersecurity](https://github.com/rod-trent/MustLearnKQL) | [Threat Hunting with KQL](https://www.youtube.com/watch?v=3NuG8EX-2Xc)
- [ ] Time-based analysis and correlation (Build queries that identify patterns across time)
    - [Time-Series Analysis in KQL](https://docs.microsoft.com/en-us/azure/data-explorer/kusto/query/samples?pivots=azuremonitor#time-series-analysis) | [KQL Time Functions](https://docs.microsoft.com/en-us/azure/data-explorer/kusto/query/datetime-timespan-arithmetic)


### **Analytics Rules and Detection**

- [ ] Built-in analytics rules configuration (Enable and tune Microsoft's managed detection rules)
    - [Sentinel Analytics Rules](https://docs.microsoft.com/en-us/azure/sentinel/tutorial-detect-threats-built-in) | [Analytics Rule Templates](https://docs.microsoft.com/en-us/azure/sentinel/detect-threats-built-in)
- [ ] Custom detection rule creation (Build environment-specific detection logic)
    - [Custom Analytics Rules](https://docs.microsoft.com/en-us/azure/sentinel/tutorial-detect-threats-custom) | [Detection Engineering](https://www.youtube.com/watch?v=A5B5t9JVFM4)
- [ ] Machine learning analytics and anomaly detection (Leverage ML to identify unusual behavior patterns)
    - [ML Analytics in Sentinel](https://docs.microsoft.com/en-us/azure/sentinel/bring-your-own-ml) | [Fusion ML Detection](https://docs.microsoft.com/en-us/azure/sentinel/fusion)


### **Automated Response and SOAR**

- [ ] Playbook creation with Logic Apps (Build automated response workflows for security incidents)
    - [Sentinel Playbooks](https://docs.microsoft.com/en-us/azure/sentinel/tutorial-respond-threats-playbook) | [Logic Apps for Security](https://www.youtube.com/watch?v=H_RMLcYpkxs)
- [ ] Incident management and case tracking (Implement structured incident response processes)
    - [Incident Investigation](https://docs.microsoft.com/en-us/azure/sentinel/tutorial-investigate-cases) | [Case Management Best Practices](https://docs.microsoft.com/en-us/azure/sentinel/investigate-cases)
- [ ] Integration with external SOAR platforms (Connect Sentinel with enterprise security orchestration tools)
    - [Third-Party SOAR Integration](https://docs.microsoft.com/en-us/azure/sentinel/integrate-logic-apps-security-operations) | [Sentinel API Integration](https://docs.microsoft.com/en-us/azure/sentinel/api)


### **Data Classification and Protection**

- [ ] Azure Information Protection integration (Classify and protect sensitive data automatically)
    - [Information Protection](https://docs.microsoft.com/en-us/azure/information-protection/) | [Data Classification Tutorial](https://www.youtube.com/watch?v=cTN7mjfpKe0)
- [ ] Microsoft Purview data governance (Implement data discovery and governance policies)
    - [Microsoft Purview](https://docs.microsoft.com/en-us/azure/purview/) | [Data Governance Strategy](https://www.youtube.com/watch?v=BB5vI1Uwq8c)
- [ ] Sensitive data detection in security logs (Build rules to identify exposure of classified information)
    - [Sensitive Data Detection](https://docs.microsoft.com/en-us/azure/sentinel/normalization-about-schemas#sensitive-data-detection) | [Data Loss Prevention](https://docs.microsoft.com/en-us/microsoft-365/compliance/dlp-learn-about-dlp)


## **Week 16: PROJECT 4 - Azure Security Integration**

### **Enterprise Application Architecture**

- [ ] Multi-tier Azure application design (Design secure n-tier application architecture)
    - [Azure Application Architecture](https://docs.microsoft.com/en-us/azure/architecture/) | [N-tier Application Tutorial](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/n-tier)
- [ ] App Service with SQL Database integration (Implement secure database connectivity and authentication)
    - [App Service SQL Integration](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-tutorial-dotnet-sqldatabase) | [Secure Database Connections](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance-connect-app)
- [ ] Azure Key Vault secrets management (Centralize application secrets and certificates)
    - [Key Vault Integration](https://docs.microsoft.com/en-us/azure/key-vault/general/tutorial-net-create-vault-azure-web-app) | [Secrets Management Best Practices](https://docs.microsoft.com/en-us/azure/key-vault/general/best-practices)


### **Comprehensive Security Stack**

- [ ] Microsoft Defender for Cloud configuration (Enable advanced threat protection for all resources)
    - [Defender for Cloud Setup](https://docs.microsoft.com/en-us/azure/security-center/security-center-get-started) | [Security Center Tutorial](https://www.youtube.com/watch?v=0ylHekySEns)
- [ ] Azure Sentinel integration with custom detection rules (Create application-specific security monitoring)
    - [Custom Sentinel Rules](https://docs.microsoft.com/en-us/azure/sentinel/tutorial-detect-threats-custom) | [Application Security Monitoring](https://docs.microsoft.com/en-us/azure/sentinel/connect-azure-sql-logs)
- [ ] Web Application Firewall (WAF) configuration (Protect against OWASP Top 10 and application-specific threats)
    - [Azure WAF Configuration](https://docs.microsoft.com/en-us/azure/web-application-firewall/) | [WAF Best Practices](https://docs.microsoft.com/en-us/azure/web-application-firewall/afds/waf-front-door-best-practices)


### **AI-Powered Security Integration**

- [ ] Custom AI detection rules for application behavior (Build ML models to detect unusual application activity)
    - [Custom ML in Sentinel](https://docs.microsoft.com/en-us/azure/sentinel/bring-your-own-ml) | [AI Security Analytics](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-monitor-model-performance)
- [ ] Automated incident response with AI analysis (Create intelligent workflows that analyze and respond to threats)
    - [AI-Powered SOAR](https://docs.microsoft.com/en-us/azure/sentinel/automation-rules) | [Intelligent Incident Response](https://www.youtube.com/watch?v=kSYPl5IykWs)
- [ ] LLM security monitoring integration (Monitor AI components for prompt injection and abuse)
    - [AI Service Monitoring](https://docs.microsoft.com/en-us/azure/cognitive-services/diagnostic-logging) | [Responsible AI Monitoring](https://docs.microsoft.com/en-us/azure/machine-learning/concept-responsible-ai-dashboard)


### **Infrastructure as Code**

- [ ] ARM templates or Bicep for reproducible deployments (Create infrastructure-as-code for entire security stack)
    - [Bicep Tutorial](https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview) | [ARM Template Best Practices](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-best-practices)
- [ ] Azure DevOps CI/CD pipeline with security scanning (Implement DevSecOps practices)
    - [Azure DevOps Security](https://docs.microsoft.com/en-us/azure/devops/organizations/security/about-security) | [DevSecOps with Azure](https://docs.microsoft.com/en-us/azure/architecture/solution-ideas/articles/devsecops-in-azure)
- [ ] Policy-as-code with Azure Policy (Implement governance and compliance automation)
    - [Azure Policy](https://docs.microsoft.com/en-us/azure/governance/policy/) | [Policy as Code Tutorial](https://www.youtube.com/watch?v=9f-gBFDaWxg)


### **Monitoring and Optimization**

- [ ] Application performance monitoring with Application Insights (Monitor application health and security events)
    - [Application Insights Setup](https://docs.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview) | [Security Monitoring with App Insights](https://docs.microsoft.com/en-us/azure/azure-monitor/app/asp-net-trace-logs)
- [ ] Cost optimization and resource management (Implement cost controls and resource governance)
    - [Azure Cost Optimization](https://docs.microsoft.com/en-us/azure/cost-management-billing/costs/cost-analysis-common-uses) | [Resource Management Best Practices](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/best-practices)
- [ ] Compliance reporting and audit preparation (Generate automated compliance reports)
    - [Azure Compliance Manager](https://docs.microsoft.com/en-us/microsoft-365/compliance/compliance-manager) | [Audit and Compliance](https://docs.microsoft.com/en-us/azure/security/fundamentals/log-audit)


### **Week 16 Deliverables**

- **GitHub repo:** `azure-enterprise-security`
- **Sub-project:** `llm-prompt-injection-lab`
- Complete enterprise Azure application with integrated security stack
- AI-powered security monitoring and response system
- Comprehensive security documentation and runbooks
- **📱 LinkedIn Action:** Post carousel showing LLM attack/defense scenarios with professional insights



