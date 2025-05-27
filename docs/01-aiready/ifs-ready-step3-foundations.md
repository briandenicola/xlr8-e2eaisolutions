---
layout: default
title: Step 3 - AI Solution Design
parent: AI Ready Challenge
nav_order: 3
---

# Step 3: AI Solution Design

This section is part of the **IFS AI Ready Challenge**. Here, you’ll design AI workloads and platform architecture, applying governance, management, and security controls as outlined in the CAF AI **Ready** phase and Azure Well-Architected Framework.

---

## Objective

Architect and plan AI workloads by selecting appropriate Azure AI services, designing data and model pipelines, and embedding governance and security controls.

---

## Activities

- Review your requirements from Step 2.
- As a team, design and document:
  1. **AI Workload Architecture:** Sketch a high-level diagram of AI components (data pipeline, model training/inference endpoints, orchestration).
  2. **Data & Model Pipelines:** Define data ingestion, processing, storage, training, and deployment workflows using Azure AI services.
  3. **AI Services Selection:** Choose and justify Azure services (OpenAI, ML Endpoints, AI Foundry, Search) and integration patterns.
  4. **Governance & Security Controls:** Outline policies, access controls, and responsible AI checks (e.g., bias, content safety).
  5. **Operational Plan:** Specify monitoring, logging, alerting, and incident response for AI workloads.
  6. **Responsible AI & Compliance:** Map required ethical, privacy, and compliance controls (e.g., data residency, PII handling).

---

## Guidance

> **Reference:** [AI Ready – Process to build AI workloads in Azure](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/ai/ready)
>
> **Establish AI reliability:**
> - Use multiple regions for redundancy and failover (e.g., global deployments, API Management for load balancing).
> - Confirm service and quota availability in your chosen regions.
> - Replicate critical assets (models, data) for business continuity.
> - Optimize data/model placement for performance.
>
> **Establish AI governance:**
> - Separate internet-facing and internal workloads using management groups and subscriptions.
> - Apply baseline and workload-specific policies (see Azure landing zone policy sets).
> - Deploy AI resources in workload subscriptions, not platform subscriptions.
>
> **Establish AI networking:**
> - Use secure topologies (hub-and-spoke, private endpoints, DDoS, firewalls).
> - Integrate DNS for private endpoints and configure network security groups.
> - Use ExpressRoute or VPN Gateway for on-premises connectivity if needed.
> - Monitor network health and security (Azure Monitor, Network Watcher, Sentinel).
>
> **Establish an AI foundation:**
> - Use Azure landing zones or baseline resource hierarchies to organize and secure your environment.
> - Reference diagrams and official guidance for best practices.

**Example Table:**

| Foundation Area | Azure Service/Feature | Purpose |
|-----------------|----------------------|---------|
| Identity        | Azure AD, RBAC       | Access control for AI resources and endpoints |
| Security        | Key Vault, Policy, Managed Identities | Secrets, compliance, secure access to AI models and data |
| Monitoring      | Log Analytics, Azure Monitor, Defender for Cloud | Observability, AI risk detection, and threat protection |
| Networking      | VNet, Private Endpoints, DDoS, Firewall | Secure connectivity for AI endpoints and data sources |
| Governance      | Management Groups, Policy, Tags, Purview | Resource organization, data cataloging, compliance for AI workloads |
| Reliability     | Multi-region, API Management, Quota Management | High availability and performance for AI models and endpoints |
| Model Management| Azure AI Foundry, Azure Machine Learning | Model catalog, versioning, and deployment governance |
| Content Safety  | Azure AI Content Safety | Harmful content detection and prompt/response filtering |

**Example Azure Policy Table (AI Focus):**

| Policy Name                                              | Purpose                                                                 | Assignment Location                |
|----------------------------------------------------------|-------------------------------------------------------------------------|------------------------------------|
| Allowed AI Model Deployments (Foundry)                   | Control which AI models can be deployed from the model catalog          | Subscription or Resource Group     |
| Audit AI Model Diagnostic Settings                       | Ensure monitoring is enabled for deployed AI models                     | Subscription or Resource Group     |
| Require Content Safety for Generative AI                 | Enforce use of Azure AI Content Safety for prompt and completion        | Resource Group or Subscription     |
| Allowed locations for AI resources                       | Restrict AI resource deployment to approved regions                     | Management Group or Subscription   |
| Enforce tag and its value for AI workloads               | Require specific tags for AI resource organization                      | Subscription or Resource Group     |
| Require managed identity for AI endpoints                | Enforce use of managed identity for secure access to AI endpoints       | Resource Group or Subscription     |
| Audit use of public endpoints for AI services            | Detect and restrict public exposure of AI endpoints                     | Subscription or Resource Group     |
| Require private endpoint for AI PaaS services            | Enforce private connectivity for sensitive AI workloads                 | Resource Group or Subscription     |
| Enforce regulatory compliance initiative for AI workloads| Apply industry-specific compliance standards to AI resources            | Management Group or Subscription   |

---

## Whiteboard Prompts

- Draw your proposed Azure AI Ready platform architecture. Label key components for:
  - Responsible AI controls (content safety, data privacy, model management)
  - Identity, access, and data security for AI endpoints and data sources
  - Networking and connectivity for AI services (private endpoints, firewalls, etc.)
  - Monitoring, logging, and risk detection for AI workloads
- Annotate your diagram to show:
  - How you will ensure reliability, redundancy, and failover for critical AI services
  - How you will separate and govern internal vs. external (internet-facing) AI workloads
  - Where and how you will apply AI-specific Azure Policies (e.g., content safety, model deployment restrictions, data residency)
  - How you will monitor and respond to AI risks (e.g., prompt injection, data leakage, model drift)
- List the Azure services, features, and policies you would use for each AI governance and operational area
- Identify any open questions or risks specific to AI adoption, governance, or responsible use in your design

---

## Success Criteria

By the end of this step, you should have:
- A high-level Azure AI Ready platform architecture diagram
- A list of core Azure services, features, and policies with justifications for AI governance and operations
- A plan for responsible AI, security, reliability, and operational readiness
- Documented design decisions, open questions, and identified AI-specific risks for group discussion

---

[⬅️ Back: Step 2 – Requirements](./ifs-ready-step2-requirements.md) | [Next: Step 4 – Present & Justify ➡️](./ifs-ready-step4-present.md)
