---
layout: default
title: Step 3 - Azure Foundations
parent: AI Ready Challenge
nav_order: 3
---

# Step 3: Azure Foundations

This section is part of the **IFS AI Ready Challenge**. Here, you’ll design the secure, scalable Azure foundation (Landing Zone) to support IFS’s AI transformation.

---

## Objective

Define the architecture, controls, and services needed for a robust Azure Landing Zone that meets IFS’s requirements. Incorporate best practices for reliability, governance, networking, and operational excellence as outlined in the [AI Ready process](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/ai/ready).

---

## Activities

- Review your requirements from Step 2.
- As a team, design and document:
  1. **Landing Zone Architecture:** Sketch a high-level diagram of the Azure foundation (resource groups, networking, identity, security, monitoring, etc.)
  2. **Key Azure Services:** List and justify the core Azure services and controls you will use (e.g., Policy, RBAC, Key Vault, Log Analytics).
  3. **Governance & Security:** Describe how you will enforce governance, compliance, and security (e.g., policies, blueprints, tagging).
  4. **Operational Readiness:** Outline how you will monitor, manage, and support the environment.
  5. **AI Reliability:** How will you ensure high availability, redundancy, and performance for AI workloads? (Consider region selection, failover, quotas, and continuity.)
  6. **AI Governance:** How will you organize resources, apply policies, and separate internal vs. internet-facing workloads? (Consider management groups, subscriptions, and policy baselines.)
  7. **AI Networking:** What network topologies and controls will you use to secure and connect AI workloads? (Consider hub-and-spoke, DDoS, private endpoints, firewalls, and monitoring.)
  8. **AI Foundation:** How will you use Azure landing zones or baseline resource hierarchies to support scalable, secure AI deployment?

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
| Identity        | Azure AD, RBAC       | Access control |
| Security        | Key Vault, Policy    | Secrets, compliance |
| Monitoring      | Log Analytics        | Observability |
| Networking      | VNet, Private Endpoints, DDoS, Firewall | Secure connectivity |
| Governance      | Management Groups, Policy, Tags | Resource organization |
| Reliability     | Multi-region, API Management, Quota Management | High availability |

---

## Whiteboard Prompts

- Draw your proposed Azure Landing Zone architecture. Label key components for identity, security, networking, and monitoring.
- Annotate your diagram to show:
  - How you will achieve redundancy and failover for AI endpoints
  - How you will separate and govern internal vs. internet-facing workloads
  - How you will secure network access and monitor traffic
  - Where you will apply policies and controls
- List the Azure services and features you would use for each foundation area.
- Identify any open questions or risks for your design.

---

## Success Criteria

By the end of this step, you should have:
- A high-level Azure Landing Zone architecture diagram
- A list of core Azure services and controls with justifications
- A plan for governance, security, reliability, and operational readiness
- Documented design decisions and open questions for group discussion

---

[⬅️ Back: Step 2 – Requirements](./ifs-alz-step2-requirements.md) | [Next: Step 4 – Present & Justify ➡️](./ifs-alz-step4-present.md)
