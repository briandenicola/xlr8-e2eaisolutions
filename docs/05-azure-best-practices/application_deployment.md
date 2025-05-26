---
layout: default
title: Application Deployment
parent: Azure Best Practices
nav_order: 3
---

# Application Deployment

| Category              | Subcategory         | Recommendation                                                                 | Service      | Priority | Reference |
|-----------------------|--------------------|-------------------------------------------------------------------------------|-------------|----------|-----------|
| Application Deployment | Data Classification | Establish a version control process for grounding data, for example, in RAG. | Azure DevOps | 🔵 Low      |           |
| Application Deployment | DevOps | Use a CI/CD pipeline to deploy IaC artifacts and ensure the quality of your deployment and Azure environments. | Azure DevOps | 🟡 Medium   | [link](https://learn.microsoft.com/azure/cloud-adoption-framework/ready/considerations/infrastructure-as-code) |
| Application Deployment | DevOps | Include unit tests for IaC and application code as part of your build process. | NA | 🔵 Low | [link](https://learn.microsoft.com/azure/cloud-adoption-framework/ready/considerations/development-strategy-development-lifecycle) |
| Application Deployment | DevOps | Leverage Declarative Infrastructure as Code Tools such as Azure Bicep, ARM Templates or Terraform to maintain your Azure AI Landing Zone. | NA | 🔵 Low | [link](https://learn.microsoft.com/azure/cloud-adoption-framework/ready/considerations/infrastructure-as-code) |