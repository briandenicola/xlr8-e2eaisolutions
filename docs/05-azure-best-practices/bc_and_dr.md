---
layout: default
title: Business Continuity & Disaster Recovery
parent: Azure Best Practices
nav_order: 4
---

# BC and DR

| Category   | Subcategory                | Recommendation                                                                                                               | Service                | Priority | Reference |
|------------|----------------------------|-----------------------------------------------------------------------------------------------------------------------------|------------------------|----------|-----------|
| BC and DR  | Data Protection            | Implement multi-region deployments to ensure high availability and resiliency for Azure AI Foundry.                         | Azure AI Foundry       | 🟡 Medium   | [link](https://learn.microsoft.com/azure/ai-studio/how-to/disaster-recovery) |
| BC and DR  | Data Protection            | Implement multi-region deployments to ensure high availability and resiliency for Azure Machine Learning.                    | Azure Machine Learning | 🟡 Medium   | [link](https://learn.microsoft.com/azure/machine-learning/how-to-high-availability-machine-learning) |
| BC and DR  | Data Protection            | Implement multi-region deployments to ensure high availability and resiliency for Azure Open AI                              | Azure Open AI          | 🟡 Medium   | [link](https://learn.microsoft.com/azure/ai-services/openai/how-to/business-continuity-disaster-recovery) |
| BC and DR  | Multi-region architecture  | Deploy multiple OAI instances across regions                                                                                | Azure OpenAI           | 🔵 Low      | [link](https://learn.microsoft.com/azure/architecture/ai-ml/architecture/baseline-openai-e2e-chat#azure-openai---reliability) |
| BC and DR  | Load balancing             | Implement retry & healthchecks with Gateway pattern like APIM                                                               | Azure OpenAI           | 🔴 High     | [link](https://learn.microsoft.com/azure/architecture/ai-ml/architecture/baseline-openai-e2e-chat#azure-openai---reliability) |
| BC and DR  | Quotas                     | Ensure having adequate quotas of TPM & RPM for the workload                                                                 | Azure OpenAI           | 🟡 Medium   | [link](https://learn.microsoft.com/azure/ai-services/openai/how-to/quota?tabs=rest#introduction-to-quota) |
| BC and DR  | Load balancing             | Deploy separate fine tuned models across regions if finetuning is employed                                                  | Azure OpenAI           | 🟡 Medium   | [link](https://learn.microsoft.com/azure/ai-services/openai/how-to/business-continuity-disaster-recovery) |
| BC and DR  | Data Backup and Disaster Recovery | Regularly backup and replicate critical data to ensure data availability and recoverability in case of data loss or system failures. Leverage Azure's backup and disaster recovery services to protect your data. | Azure OpenAI           | 🟡 Medium   | [link](https://learn.microsoft.com/azure/backup/backup-overview) |
| BC and DR  | SLA considerations         | Azure AI search service tiers should be choosen to have a SLA                                                               | Azure OpenAI           | 🔴 High     | [link](https://learn.microsoft.com/azure/search/search-reliability) |
