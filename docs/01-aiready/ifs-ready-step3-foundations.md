---
layout: default
title: Step 3 - Landing Zone Design
parent: AI Ready Challenge
nav_order: 3
---

# Step 3: Landing Zone Design

This section is part of the **IFS AI Ready Challenge**. Here, you’ll design the Azure Landing Zone platform environment that meets IFS’s regulatory, compliance, and best practice requirements, providing the foundation for future AI workloads.

---

## Objective

Define a scalable, secure, and governed Azure Landing Zone architecture by:
- Structuring management groups and subscriptions (platform vs application zones)
- Applying Azure Policy baselines for regulatory and compliance requirements
- Designing network topology and connectivity controls
- Establishing identity, access, and resource organization strategies
- Planning operational readiness (monitoring, management, and governance)

---

## Activities

- Review requirements from **Step 2: Requirements & Plan**.
- As a team, design and document:
  1. **Management Group Hierarchy:** Define parent and child management groups for platform and application workloads.
  2. **Subscription Strategy:** Map services and workloads to platform and application subscriptions.
  3. **Policy Baselines:** Select and assign built-in and custom Azure Policy definitions to enforce compliance (e.g., allowed locations, tag enforcement, diagnostic settings).
  4. **Network Topology:** Design hub-and-spoke or virtual WAN topology with private endpoints, DDoS protection, and firewall controls.
  5. **Identity & Access Controls:** Plan Azure AD, RBAC roles, and Managed Identities for least-privileged access.
  6. **Operational Plan:** Outline monitoring (Azure Monitor, Log Analytics), cost management, and automation (landing zone provisioning scripts).

---

## Guidance

> **References:**
> - [Azure Landing Zones Overview](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/landing-zone/)
> - [AI Ready – CAF Landing Zone Processes](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/ai/ready)
>
> **Management Groups & Subscriptions:**
> - Use separate management groups for regulatory boundaries (e.g., internet-facing vs internal).
> - Deploy platform services (identity, connectivity, management) in dedicated platform subscriptions.
>
> **Policy & Compliance:**
> - Assign policy initiatives for required standards (e.g., GDPR, HIPAA, ISO).
> - Enforce resource tagging and diagnostic settings at subscription scope.
>
> **Networking:**
> - Implement hub-and-spoke topology with Azure Firewall and DDoS protection.
> - Use private endpoints to secure PaaS resource access.
>
> **Identity:**
> - Use Azure AD for tenant-level identity and Managed Identities for resource access.
> - Plan RBAC roles at management group and subscription scopes.
>
> **Operations:**
> - Use Azure Policy and Azure Blueprints for repeatable landing zone deployment.
> - Set up monitoring and alerting with Log Analytics workspaces.

**Example Landing Zone Architecture Table:**

| Design Area        | Approach/Service                               | Purpose                                               |
|--------------------|------------------------------------------------|-------------------------------------------------------|
| Management Groups  | mgmt-platform, mgmt-app                       | Segment platform vs application governance            |
| Subscriptions      | sub-platform-id, sub-app-ai                    | Isolate shared vs AI workloads                        |
| Policy             | Allowed Locations, Tag Enforcement, Audit Logs | Enforce compliance and governance                     |
| Network            | Hub VNet + Spokes, Firewall, Private Endpoints | Secure connectivity and traffic inspection            |
| Identity           | Azure AD, RBAC, Managed Identities            | Least-privilege access and service identities         |
| Operations         | Log Analytics, Azure Monitor, Automation       | Monitor health, logs, and automate landing zone setup |

**Example Azure Policy Table:**

| Policy Definition                           | Purpose                                            | Assignment Scope               |
|---------------------------------------------|----------------------------------------------------|--------------------------------|
| Allowed locations                           | Restrict resource deployment to approved regions   | Management Group or Subscription |
| Require tag and its value                   | Enforce application of standard tags               | Subscription or Resource Group |
| Audit diagnostic settings                   | Ensure diagnostic logs are enabled for resources   | Subscription                   |
| Enforce resource naming conventions         | Standardize resource names for consistency         | Management Group               |
| Deny public network access on PaaS services | Block public endpoint creation for critical PaaS  | Subscription or Resource Group |

---

## Success Criteria

By the end of this step, you should have:
- A management group and subscription layout diagram
- Policy baseline assignments for regulatory & compliance controls
- Network topology diagram showing secure connectivity
- Identity and access plan for least-privileged operations
- Operational readiness plan (monitoring, management, automation)

---

[⬅️ Back: Step 2 – Requirements & Plan](./ifs-alz-step2-requirements.md) | [Next: Step 4 – Present & Justify ➡️](./ifs-ready-step4-present.md)
