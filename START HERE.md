# google-professional-devops-cert-notes

## Section 1: Bootstrapping and maintaining a Google Cloud organization (~15%)

### [[Designing hierarchy|Designing the overall resource hierarchy for an organization]]

- [ ] Projects and folders  
- [ ] Shared networking  
- [ ] Multi-project monitoring and logging  
- [ ] Identity and Access Management (IAM) roles and organization-level policies  
- [ ] Creating and managing service accounts  
- [ ] Organizing resources by using an application-centric approach (e.g., App Hub)  

### [[Infra management|Managing infrastructure]]

- [ ] Infrastructure-as-code tooling (e.g., Cloud Foundation Toolkit, Config Connector, Terraform, Helm)  
- [ ] Making infrastructure changes using Google-recommended practices and blueprints  
- [ ] Automation with scripting (e.g., Python, Go)  

### [[CI/CD architecture|Designing a CI/CD architecture stack]]

- [ ] CI with Cloud Build  
- [ ] CD with Cloud Deploy, Kustomize, Skaffold  
- [ ] Jenkins, Git, Argo CD, Packer  
- [ ] Securing CI/CD tooling  

### [[Managing envs|Managing multiple environments]]

- [ ] Purpose and number of environments  
- [ ] Ephemeral environments  
- [ ] Configuration and policy management  
- [ ] Managing GKE clusters across an enterprise  
- [ ] Safe and secure patching and upgrading  

### [[Cloud dev envs|Enabling secure cloud development environments]]

- [ ] Cloud Workstations, Cloud Shell  
- [ ] Bootstrapping environments (e.g., IDE, SDK, custom images)  
- [ ] AI assistance (e.g., Cloud Code, Gemini Code Assist)  

---

## Section 2: Building and implementing CI/CD pipelines (~27%)

### [[Designing pipelines|Designing and managing CI/CD pipelines]]

- [ ] Artifact Registry  
- [ ] Hybrid/multi-cloud deployment (e.g., GKE Enterprise)  
- [ ] Pipeline triggers  
- [ ] Testing new app versions  
- [ ] Deployment approvals  
- [ ] Serverless CI/CD  
- [ ] Infra as CI/CD (e.g., GKE, MIGs, Service Mesh)  

### [[Implementing pipelines|Implementing CI/CD pipelines]]

- [ ] Deployment auditing (e.g., Artifact Registry, Cloud Build, Cloud Deploy, Audit Logs)  
- [ ] Strategies: canary, blue/green, rolling, traffic splitting  
- [ ] Deployment troubleshooting  

### [[Secrets config|Managing CI/CD configuration and secrets]]

- [ ] Cloud KMS  
- [ ] Secret Manager, Certificate Manager  
- [ ] Build vs runtime secret injection  

### [[Securing pipeline|Securing the CI/CD deployment pipeline]]

- [ ] Vulnerability scans with Artifact Registry  
- [ ] Software supply chain (Binary Authorization, SLSA)  
- [ ] IAM per environment  

---

## Section 3: Applying SRE practices (~23%)

### [[Balancing change|Balancing change, velocity, and reliability]]

- [ ] SLIs (availability, latency), SLOs, SLAs  
- [ ] Error budgets  
- [ ] Opportunity cost of reliability (e.g., number of "nines")  

### [[Service lifecycle|Managing service lifecycle]]

- [ ] Onboarding checklist, launch/deployment/retirement plan  
- [ ] Quotas and limits  
- [ ] Autoscaling: MIGs, Cloud Run, GKE  

### [[Incident impact|Mitigating incident impact]]

- [ ] Traffic redirection  
- [ ] Adding capacity  
- [ ] Rollbacks  

---

## Section 4: Implementing observability (~20%)

### [[Log management|Managing logs]]

- [ ] Cloud Logging agent, Audit Logs, Flow Logs, Service Mesh  
- [ ] Optimization: filtering, sampling, exclusions, cost  
- [ ] Exporting: BigQuery, Pub/Sub  
- [ ] Log retention  
- [ ] Sensitive data handling (PII, PHI)  

### [[Metric management|Managing metrics]]

- [ ] Application/platform/network/mesh/hybrid metrics  
- [ ] Custom metrics from logs  
- [ ] Metrics Explorer  
- [ ] Synthetic monitors  

### [[Dashboards alerts|Managing dashboards and alerts]]

- [ ] Creating/sharing dashboards and playbooks  
- [ ] Alert policies (SLIs, SLOs, cost)  
- [ ] Third-party alerting tools  

---

## Section 5: Optimizing performance and troubleshooting (~15%)

### [[Troubleshooting|Troubleshooting issues]]

- [ ] Infra, application, CI/CD, observability, performance/latency  

### [[Debugging tools|Implementing debugging tools]]

- [ ] Application instrumentation  
- [ ] Cloud Trace  
- [ ] Error Reporting  

### [[Cost perf|Optimizing resource utilization and costs]]

- [ ] Observability costs  
- [ ] Spot VMs  
- [ ] Cost planning: committed/sustained use, network tiers  
- [ ] Google Cloud recommenders  
