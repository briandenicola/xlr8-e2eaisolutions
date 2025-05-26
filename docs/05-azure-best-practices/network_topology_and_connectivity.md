---
layout: default
title: Network Topology & Connectivity
parent: Azure Best Practices
nav_order: 8
---

# Network Topology and Connectivity

| Category                      | Subcategory         | Recommendation                                                                 | Service      | Priority | Reference |
|-------------------------------|--------------------|-------------------------------------------------------------------------------|-------------|----------|-----------|
| Network Topology and Connectivity | Azure OpenAI | Restrict access to select virtual networks or use private endpoints. | Azure OpenAI | 🔴 High | [link](https://learn.microsoft.com/azure/ai-studio/how-to/configure-managed-network) |
| Network Topology and Connectivity | Azure AI Services (Speech, Bing, Translator etc.) | Restrict access to select virtual networks or use private endpoints. | Azure AI Services | 🔴 High | [link](https://learn.microsoft.com/azure/ai-studio/how-to/configure-managed-network) |
| Network Topology and Connectivity | Azure Machine Learning | Restrict network access to Azure Machine Learning resources. | Azure Machine Learning | 🔴 High | [link](https://learn.microsoft.com/azure/machine-learning/concept-network-isolation-configurations) |
| Network Topology and Connectivity | Azure AI Services | Configure data loss prevention for Azure AI services. | Azure AI Services | 🔴 High | [link](https://learn.microsoft.com/azure/ai-services/cognitive-services-data-loss-prevention?branch=main&tabs=azure-cli) |
| Network Topology and Connectivity | Azure AI Foundry | Limit outbound traffic from your AI resources. | Azure AI Foundry | 🔴 High | [link](https://learn.microsoft.com/azure/ai-studio/how-to/configure-managed-network?branch=main&tabs=portal) |
| Network Topology and Connectivity | Azure Machine Learning | Allow only approved network outbound mode. | Azure Machine Learning | 🔴 High | [link](https://learn.microsoft.com/azure/machine-learning/how-to-network-isolation-planning?view=azureml-api-2&branch=main) |
| Network Topology and Connectivity | API Gateway | Deploy a API Gateway solution like API-Management to load balance requests, rate limit tokens, keyless authentication and monitor AI usage. | Azure API Management | 🔴 High | [link](https://github.com/Azure/apim-landing-zone-accelerator/blob/main/scenarios/workload-genai/README.md) |
| Network Topology and Connectivity  | Azure AI Foundry | Configure the AI managed network and use private endpoints. | Azure AI Foundry | 🔴 High | [link](https://learn.microsoft.com/azure/ai-studio/how-to/configure-managed-network) |

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