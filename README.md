# Morgan Okanya

## Principal Cloud, Platform & Infrastructure Engineering Leader

**Cloud Architecture | Platform Engineering | Kubernetes/OpenShift | Infrastructure Automation | AWS/Azure | Terraform | Ansible/AAP | Python | SRE | Observability | HA/DR**

Principal-level Cloud, Platform and Infrastructure Engineering professional with 12+ years of experience designing, automating, modernizing and operating mission-critical technology platforms across enterprise banking and telecommunications environments.

My engineering background spans cloud architecture, Kubernetes/OpenShift, Linux, infrastructure automation, Infrastructure as Code, Python/API engineering, observability, virtualization, networking, enterprise storage, security, high availability and disaster recovery.

I focus on building secure, scalable and resilient platforms, reducing operational toil through automation, improving engineering delivery, and translating complex infrastructure requirements into reliable production solutions.

---

# Engineering Portfolio

## Cloud & Cloud-Native Architecture

### AWS Event-Driven Serverless Architecture

**Project**  
Designed an AWS serverless platform using event-driven architectural principles and Terraform-based Infrastructure as Code.

**Problem It Solves**  
Demonstrates how cloud workloads can be decoupled using event-driven compute and reusable Infrastructure-as-Code patterns, improving scalability, deployment repeatability and infrastructure lifecycle management.

**Architecture**  
Event Source → AWS Event Processing → Lambda Compute → Downstream Cloud Services → Monitoring, with infrastructure provisioned through reusable Terraform modules.

**Technologies**  
AWS | AWS Lambda | Terraform | Infrastructure as Code | Event-Driven Architecture | Serverless Computing | Terraform Modules | Remote State

**What I Personally Designed**  
Designed the serverless architecture, Lambda execution components, Terraform root configuration, reusable infrastructure modules, provider configuration, variables/outputs and remote-state/backend structure.

**Reliability / Security / Scale Focus**  
Loose coupling, stateless compute, independently scalable components, repeatable infrastructure provisioning, modular IaC and reduced infrastructure-management overhead.

[View Project Repository](https://github.com/mokanyair/Event-Driven-Serverless-Architecture)

---

## Platform Engineering & Kubernetes

### Scalable Cloud-Native Messaging Platform

**Project**  
Designed and engineered a production-oriented messaging platform combining application engineering, containerization, Kubernetes orchestration, infrastructure automation, observability, performance testing and progressive deployment.

**Problem It Solves**  
Demonstrates how a real-time application can evolve into a scalable, observable and resilient cloud-native platform capable of supporting increasing workload and availability requirements.

**Architecture**  
Application → Containerized Runtime → Kubernetes → Application Instances → Data Services → Prometheus/Grafana/Alertmanager

**Technologies**  
Python | Docker | Kubernetes | AWS | Redis | Prometheus | Grafana | Alertmanager | Alembic | Locust | Blue/Green Deployment

**What I Personally Designed**  
Designed the application/platform architecture, containerization and Kubernetes deployment approach, infrastructure components, observability stack, scaling strategy, performance-testing approach and blue/green deployment workflow.

**Reliability / Security / Scale Focus**  
Horizontal scaling, Redis-based scaling patterns, database scaling, workload monitoring, alerting, load testing, controlled releases and failure-aware platform design.

[View Project Repository](https://github.com/mokanyair/chatApp/tree/master/chatApp)

### Kubernetes Engineering Projects

A collection of hands-on Kubernetes engineering work covering container orchestration, workload deployment, configuration, networking, storage and operational administration.

**Technologies**  
Kubernetes | Containers | YAML | Services | Deployments | Configuration | Networking | Persistent Storage

[View Kubernetes Projects](https://github.com/mokanyair/KubernetesProjects)

---

## Infrastructure Automation & Infrastructure as Code

### Enterprise Infrastructure Automation

My enterprise automation work focuses on transforming repeatable infrastructure activities into standardized, governed and reusable automation services.

**Architecture Pattern**

Git → CI/CD → Ansible/AAP → Inventory → Credentials → Job Templates → Workflows → Managed Infrastructure → Validation

**Engineering Capabilities**

Ansible | Ansible Automation Platform | AWX/Tower | Terraform | Python | Bash | PowerShell | Git | CI/CD | REST APIs

**Automation Patterns**

- Reusable roles and playbooks
- Configuration management
- Infrastructure provisioning
- OS patching and upgrades
- Security hardening
- Vulnerability remediation
- Application deployment
- RBAC and credential controls
- Approval workflows
- Prechecks and validation
- Canary and wave-based deployment
- Failure handling and recovery
- Infrastructure lifecycle automation

**Reliability / Security / Scale Focus**

Automation is designed around controlled execution, least privilege, reusable components, validation, limited blast radius, production approvals and repeatable recovery.

---

## Software, APIs & Service Engineering

### Python FastAPI E-Commerce Service Platform

**Project**  
Developed a modular e-commerce backend using Python and FastAPI, structured around API, service, data-access, integration and persistence layers.

**Problem It Solves**  
Demonstrates how backend services can be structured into maintainable and reusable components rather than tightly coupled application logic, creating a foundation for scalable cloud-hosted API services.

**Architecture**  
Client → FastAPI API Layer → Service Layer → CRUD/Data Access Layer → Database

Separate components manage schemas, models, configuration and integrations.

**Technologies**  
Python | FastAPI | REST APIs | Database Integration | Data Models | Schemas | Service-Layer Architecture | API Integration

**What I Personally Designed**  
Designed and implemented the application structure, API organization, service boundaries, CRUD/data-access components, database integration, schemas/models and integration patterns.

**Reliability / Security / Scale Focus**  
Separation of concerns, modular service architecture, maintainability, API validation, reusable components and architecture capable of supporting containerization and horizontal scaling.

[View Project Repository](https://github.com/mokanyair/fastapi-ecommerce)

---

# Reliability, Observability & SRE

My reliability engineering work focuses on making infrastructure and platforms measurable, resilient and operationally manageable.

### Observability Architecture

Platform / Infrastructure  
↓  
Metrics & Telemetry  
↓  
Prometheus / Thanos  
↓  
Grafana  
↓  
Alertmanager  
↓  
Operations / Engineering

**Capabilities**

Prometheus | Grafana | Thanos | Alertmanager | Platform Metrics | Infrastructure Monitoring | Capacity Analysis | Performance Engineering | Incident Response | RCA

**Engineering Focus**

- Platform health visibility
- CPU and memory utilization
- Node and workload health
- Storage and capacity visibility
- Infrastructure performance
- Alerting
- Failure diagnosis
- Capacity planning
- Service restoration
- Root-cause analysis
- Operational improvement

---

# Enterprise Infrastructure Engineering

My cloud and platform engineering experience is built on deep enterprise infrastructure knowledge across compute, operating systems, virtualization, networking, storage and business continuity.

### Core Infrastructure

**Compute & Virtualization**  
VMware vSphere/ESXi/vCenter | KVM | IBM Power | Bare Metal | Windows Server | RHEL/Linux

**Storage & Data Platforms**  
Pure Storage | NetApp | EMC VMAX/PowerMax | PowerStore | GPFS/Spectrum Scale | SAN | Fibre Channel | Brocade

**Networking & Availability**  
TCP/IP | DNS | Load Balancing | HAProxy | F5 | VLANs | Routing | High Availability | Multi-Datacenter Infrastructure

**Business Continuity**  
HA/DR | Replication | Backup/Recovery | RPO/RTO | Failover | Production Recovery | Migration | Rollback

---

# Cloud & Platform Security

Security is incorporated into platform architecture and automation rather than treated as a separate post-deployment activity.

**Capabilities**

IAM | RBAC | Least Privilege | Secrets Management | Credential Controls | SELinux | Firewalld | LDAP | Kerberos | SSSD | Certificate Management | Vulnerability Remediation | Infrastructure Hardening | Change Governance

**Engineering Principles**

- No credentials embedded in source code
- Least-privilege production access
- Segmented environments
- Controlled change
- Secure automation
- Infrastructure validation
- Auditable execution
- Security remediation
- Production-readiness controls

---

# Performance, Capacity & FinOps

I approach cloud and infrastructure architecture as a balance between:

**Availability + Performance + Scalability + Security + Cost**

Areas of focus include:

- Capacity forecasting
- Resource utilization analysis
- Infrastructure sizing
- Performance bottleneck analysis
- Rightsizing
- Autoscaling
- Cloud cost governance
- Storage lifecycle optimization
- Cost allocation
- High-availability tradeoffs
- Performance versus cost decisions

---

# Technical Leadership

My technical leadership approach combines hands-on engineering with architecture, governance and team enablement.

**Leadership Capabilities**

Architecture Strategy | HLD/LLD | Technical Discovery | Design Reviews | Production Readiness | Technology Evaluation | POCs | Engineering Standards | Mentoring | Cross-Functional Delivery | Vendor/OEM Leadership | Risk Management | Incident Leadership

I work across infrastructure, cloud, application, security, networking, database and operations teams to translate requirements into scalable engineering solutions and establish reusable patterns that other engineers can safely adopt.

---

# Core Technical Stack

### Cloud
AWS | Azure | Hybrid Cloud | Serverless | Cloud-Native Architecture

### Platform Engineering
Kubernetes | Red Hat OpenShift | Docker | Platform Automation | Self-Service Infrastructure

### Infrastructure as Code
Terraform | Ansible | Ansible Automation Platform | Git | CI/CD | GitOps

### Software & Automation
Python | FastAPI | REST APIs | Bash | PowerShell | PowerCLI

### Reliability & Observability
Prometheus | Grafana | Thanos | Alertmanager | SRE | Capacity Planning | Performance Engineering | Incident Response | RCA

### Operating Systems
RHEL | Linux | Windows Server | RHCOS

### Infrastructure
VMware | KVM | IBM Power | Enterprise Storage | SAN | Fibre Channel | Networking | HA/DR

### Security
IAM | RBAC | SELinux | LDAP | Kerberos | SSSD | Certificates | Vulnerability Remediation | Infrastructure Hardening

---

# Certifications

- AWS Certified Solutions Architect
- HashiCorp Certified: Terraform Associate
- Microsoft Azure Solutions Architect Expert
- Microsoft Azure Administrator
- Red Hat Certified Engineer (RHCE)
- Red Hat Certified System Administrator (RHCSA)
- VMware Certified Professional (VCP)
- Project Management Professional (PMP)
- ISO/IEC 20000 Lead Implementer

---

# Engineering Philosophy

> Build platforms that are automated, observable, secure, resilient and simple for other engineers to consume.

I believe strong infrastructure engineering is not only about deploying technology. It is about creating repeatable engineering systems that reduce operational friction, limit production risk, improve reliability and allow teams to deliver faster.

---

# Connect

**GitHub:** [github.com/mokanyair](https://github.com/mokanyair)
