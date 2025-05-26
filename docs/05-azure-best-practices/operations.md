---
layout: default
title: Operations
parent: Azure Best Practices
nav_order: 9
---

# Operations

| Category   | Subcategory         | Recommendation                                                                 | Service      | Priority | Reference |
|------------|--------------------|-------------------------------------------------------------------------------|-------------|----------|-----------|
| Operations | Operations | Use Dynamic Sessions in Azure Container Apps, to ensure each code execution occurs in a fresh, isolated environment that is destroyed after use. | Azure Container Apps | 🔴 High | [link](https://learn.microsoft.com/azure/container-apps/sessions?tabs=azure-cli) |
| Operations | Operations | Set resource limits (CPU, memory, disk usage) for code execution environments to prevent any single execution from consuming excessive resources. | NA | 🟡 Medium | |
| Operations | Monitoring | Implement a monitoring system to ensure that AI workloads remain aligned with KPIs. | Azure AI Foundry | 🔴 High | [link](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-approach-gen-ai) |
| Operations | Monitoring | Proactively identify performance bottlenecks and anomalies. | Azure AI Foundry | 🔴 High | [link](https://learn.microsoft.com/azure/ai-studio/how-to/develop/trace-local-sdk) |

## Navigation
- [⬅️ Back to Home](../index.md)
- [Azure Best Practices Index](./index.md)
- [Application Deployment](./application_deployment.md)
- [BC and DR](./bc_and_dr.md)
- [Best Practices Summary](./best-practices-summary.md)
- [Cost Governance](./cost_governance.md)
- [Governance and Security](./governance_and_security.md)
- [Identity and Access Management](./identity_and_access_management.md)
- [Network Topology and Connectivity](./network_topology_and_connectivity.md)
- [Operations](./operations.md)