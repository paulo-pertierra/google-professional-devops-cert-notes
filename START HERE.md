# google-professional-devops-cert-notes

## Section 1: Bootstrapping and maintaining a Google Cloud organization (~15%)

### [[Designing the overall resource hierarchy for an organization|Designing hierarchy]]

- [ ] [[Projects and folders|Projects and folders]]  
- [ ] [[Shared networking|Shared networking]]  
- [ ] [[Multi-project monitoring and logging|Multi-project monitoring and logging]]  
- [ ] [[Identity and Access Management (IAM) roles and organization-level policies|Identity and Access Management (IAM) roles and organization-level policies]]  
- [ ] [[Creating and managing service accounts|Creating and managing service accounts]]  
- [ ] [[Organizing resources by using an application-centric approach (e.g., App Hub)|Organizing resources by using an application-centric approach (e.g., App Hub)]]  

### [[Managing infrastructure|Infra management]]

- [ ] [[Infrastructure-as-code tooling (e.g., Cloud Foundation Toolkit, Config Connector, Terraform, Helm)|Infrastructure-as-code tooling (e.g., Cloud Foundation Toolkit, Config Connector, Terraform, Helm)]]  
- [ ] [[Making infrastructure changes using Google-recommended practices and blueprints|Making infrastructure changes using Google-recommended practices and blueprints]]  
- [ ] [[Automation with scripting (e.g., Python, Go)|Automation with scripting (e.g., Python, Go)]]  

### [[Designing a CI/CD architecture stack|CI/CD architecture]]

- [ ] [[CI with Cloud Build|CI with Cloud Build]]  
- [ ] [[CD with Cloud Deploy, Kustomize, Skaffold|CD with Cloud Deploy, Kustomize, Skaffold]]  
- [ ] [[Jenkins, Git, Argo CD, Packer|Jenkins, Git, Argo CD, Packer]]  
- [ ] [[Securing CI/CD tooling|Securing CI/CD tooling]]  

### [[Managing multiple environments|Managing envs]]

- [ ] [[Purpose and number of environments|Purpose and number of environments]]  
- [ ] [[Ephemeral environments|Ephemeral environments]]  
- [ ] [[Configuration and policy management|Configuration and policy management]]  
- [ ] [[Managing GKE clusters across an enterprise|Managing GKE clusters across an enterprise]]  
- [ ] [[Safe and secure patching and upgrading|Safe and secure patching and upgrading]]  

### [[Enabling secure cloud development environments|Cloud dev envs]]

- [ ] [[Cloud Workstations, Cloud Shell|Cloud Workstations, Cloud Shell]]  
- [ ] [[Bootstrapping environments (e.g., IDE, SDK, custom images)|Bootstrapping environments (e.g., IDE, SDK, custom images)]]  
- [ ] [[AI assistance (e.g., Cloud Code, Gemini Code Assist)|AI assistance (e.g., Cloud Code, Gemini Code Assist)]]  

---

## Section 2: Building and implementing CI/CD pipelines (~27%)

### [[Designing and managing CI/CD pipelines|Designing pipelines]]

- [ ] [[Artifact Registry|Artifact Registry]]  
- [ ] [[Hybrid/multi-cloud deployment (e.g., GKE Enterprise)|Hybrid/multi-cloud deployment (e.g., GKE Enterprise)]]  
- [ ] [[Pipeline triggers|Pipeline triggers]]  
- [ ] [[Testing new app versions|Testing new app versions]]  
- [ ] [[Deployment approvals|Deployment approvals]]  
- [ ] [[Serverless CI/CD|Serverless CI/CD]]  
- [ ] [[Infra as CI/CD (e.g., GKE, MIGs, Service Mesh)|Infra as CI/CD (e.g., GKE, MIGs, Service Mesh)]]  

### [[Implementing CI/CD pipelines|Implementing pipelines]]

- [ ] [[Deployment auditing (e.g., Artifact Registry, Cloud Build, Cloud Deploy, Audit Logs)|Deployment auditing (e.g., Artifact Registry, Cloud Build, Cloud Deploy, Audit Logs)]]  
- [ ] [[Strategies: canary, blue/green, rolling, traffic splitting|Strategies: canary, blue/green, rolling, traffic splitting]]  
- [ ] [[Deployment troubleshooting|Deployment troubleshooting]]  

### [[Managing CI/CD configuration and secrets|Secrets config]]

- [ ] [[Cloud KMS|Cloud KMS]]  
- [ ] [[Secret Manager, Certificate Manager|Secret Manager, Certificate Manager]]  
- [ ] [[Build vs runtime secret injection|Build vs runtime secret injection]]  

### [[Securing the CI/CD deployment pipeline|Securing pipeline]]

- [ ] [[Vulnerability scans with Artifact Registry|Vulnerability scans with Artifact Registry]]  
- [ ] [[Software supply chain (Binary Authorization, SLSA)|Software supply chain (Binary Authorization, SLSA)]]  
- [ ] [[IAM per environment|IAM per environment]]  

---

## Section 3: Applying SRE practices (~23%)

### [[Balancing change, velocity, and reliability|Balancing change]]

- [ ] [[SLIs (availability, latency), SLOs, SLAs|SLIs (availability, latency), SLOs, SLAs]]  
- [ ] [[Error budgets|Error budgets]]  
- [ ] [[Opportunity cost of reliability (e.g., number of "nines")|Opportunity cost of reliability (e.g., number of "nines")]]  

### [[Managing service lifecycle|Service lifecycle]]

- [ ] [[Onboarding checklist, launch/deployment/retirement plan|Onboarding checklist, launch/deployment/retirement plan]]  
- [ ] [[Quotas and limits|Quotas and limits]]  
- [ ] [[Autoscaling: MIGs, Cloud Run, GKE|Autoscaling: MIGs, Cloud Run, GKE]]  

### [[Mitigating incident impact|Incident impact]]

- [ ] [[Traffic redirection|Traffic redirection]]  
- [ ] [[Adding capacity|Adding capacity]]  
- [ ] [[Rollbacks|Rollbacks]]  

---

## Section 4: Implementing observability (~20%)

### [[Managing logs|Log management]]

- [ ] [[Cloud Logging agent, Audit Logs, Flow Logs, Service Mesh|Cloud Logging agent, Audit Logs, Flow Logs, Service Mesh]]  
- [ ] [[Optimization: filtering, sampling, exclusions, cost|Optimization: filtering, sampling, exclusions, cost]]  
- [ ] [[Exporting: BigQuery, Pub/Sub|Exporting: BigQuery, Pub/Sub]]  
- [ ] [[Log retention|Log retention]]  
- [ ] [[Sensitive data handling (PII, PHI)|Sensitive data handling (PII, PHI)]]  

### [[Managing metrics|Metric management]]

- [ ] [[Application/platform/network/mesh/hybrid metrics|Application/platform/network/mesh/hybrid metrics]]  
- [ ] [[Custom metrics from logs|Custom metrics from logs]]  
- [ ] [[Metrics Explorer|Metrics Explorer]]  
- [ ] [[Synthetic monitors|Synthetic monitors]]  

### [[Managing dashboards and alerts|Dashboards alerts]]

- [ ] [[Creating/sharing dashboards and playbooks|Creating/sharing dashboards and playbooks]]  
- [ ] [[Alert policies (SLIs, SLOs, cost)|Alert policies (SLIs, SLOs, cost)]]  
- [ ] [[Third-party alerting tools|Third-party alerting tools]]  

---

## Section 5: Optimizing performance and troubleshooting (~15%)

### [[Troubleshooting issues|Troubleshooting]]

- [ ] [[Infra, application, CI/CD, observability, performance/latency|Infra, application, CI/CD, observability, performance/latency]]  

### [[Implementing debugging tools|Debugging tools]]

- [ ] [[Application instrumentation|Application instrumentation]]  
- [ ] [[Cloud Trace|Cloud Trace]]  
- [ ] [[Error Reporting|Error Reporting]]  

### [[Optimizing resource utilization and costs|Cost perf]]

- [ ] [[Observability costs|Observability costs]]  
- [ ] [[Spot VMs|Spot VMs]]  
- [ ] [[Cost planning: committed/sustained use, network tiers|Cost planning: committed/sustained use, network tiers]]  
- [ ] [[Google Cloud recommenders|Google Cloud recommenders]]  
