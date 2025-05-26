---
layout: default
title: Cost Governance
parent: Azure Best Practices
nav_order: 5
---

# Cost Governance

| Category         | Subcategory         | Recommendation                                                            | Service      | Priority | Reference |
|------------------|--------------------|---------------------------------------------------------------------------|-------------|----------|-----------|
| Cost Governance | Cost Management | Verify PTU cost savings vs pay as you pricing for Azure OpenAI and OpenAI models. | Azure OpenAI | 🔴 High | [link](https://learn.microsoft.com/azure/ai-services/openai/concepts/provisioned-throughput) |
| Cost Governance | Cost Management | Ensure the right and cost effective model is in use, unless the use case demands a more expensive model. | Azure OpenAI | 🟡 Medium | [link](https://learn.microsoft.com/azure/ai-services/openai/concepts/models?branch=main&tabs=python-secure) |
| Cost Governance | Cost Management | Allocate provisioning quotas for each model based on expected workloads to prevent unnecessary costs. | Azure OpenAI | 🟡 Medium | [link](https://learn.microsoft.com/azure/ai-services/openai/how-to/quota?tabs=rest&branch=main) |
| Cost Governance | Cost Management | Use the right deployment type, global deployment offers lower cost-per-token pricing on certain GPT models. | Azure OpenAI | 🔴 High | [link](https://learn.microsoft.com/azure/ai-services/openai/how-to/deployment-types) |
| Cost Governance | Cost Management | Choose the right hosting infrastructure, depending on your solution's needs e.g. managed endpoints, AKS or Azure App Service. | NA | 🟡 Medium | |
| Cost Governance | Cost Management | Define and enforce a policy to automatically shutdown Azure AI Foundry and Azure Machine Learning compute instances. | Azure AI Foundry | 🔵 Low | [link](https://github.com/Azure/Community-Policy/tree/main/policyDefinitions/Compute/deploy-vm-auto-shutdown) |
| Cost Governance | Cost Management | Configure 'Actual' and 'Forecasted' Budget Alerts. | Azure Cost Management | 🟡 Medium | [link](https://learn.microsoft.com/azure/cost-management-billing/costs/tutorial-acm-create-budgets?bc=%2Fazure%2Fcloud-adoption-framework%2F_bread%2Ftoc.json&toc=%2Fazure%2Fcloud-adoption-framework%2Ftoc.json) |
| Cost Governance | Token Optimization | Use prompt compression tools like LLMLingua or gprtrim | Azure OpenAI | 🟡 Medium | [link](https://www.microsoft.com/research/blog/llmlingua-innovating-llm-efficiency-with-prompt-compression/) |
| Cost Governance | Token Optimization | Use tiktoken to understand token sizes for token optimizations in conversational mode | Azure OpenAI | 🔴 High | [link](https://github.com/openai/tiktoken) |
| Cost Governance | Cost familiarization | Understand difference in cost of base models and fine tuned models and token step sizes | Azure OpenAI | 🟡 Medium | [link](https://learn.microsoft.com/azure/ai-services/openai/how-to/manage-costs#base-series-and-codex-series-fine-tuned-models) |
| Cost Governance | Batch processing | Batch requests, where possible, to minimize the per-call overhead which can reduce overall costs. Ensure you optimize batch size | Azure OpenAI | 🔴 High | [link](https://learn.microsoft.com/azure/ai-services/openai/how-to/latency#batching) |
| Cost Governance | Cost monitoring | Set up a cost tracking system that monitors model usage and use that information to help inform model choices and prompt sizes | Azure OpenAI | 🟡 Medium | [link](https://learn.microsoft.com/azure/ai-services/openai/how-to/manage-costs) |
| Cost Governance | Token limit | Set a maximum limit on the number of tokens per model response (max_tokens and the number of completions to generate). Optimize the size to ensure it is large enough for a valid response | Azure OpenAI | 🟡 Medium | [link](https://learn.microsoft.com/azure/ai-services/openai/how-to/quota?tabs=rest#understanding-rate-limits) |
| Cost Governance | Costing Model | Evaluate usage of billing models - PAYG vs PTU. Start with PAYG and consider PTU when the usage is predictable in production since it offers dedicated memory and compute, reserved capacity, and consistent maximum latency for the specified model version | Azure OpenAI | 🔴 High | [link](https://learn.microsoft.com/azure/ai-services/openai/how-to/provisioned-throughput-onboarding#understanding-the-provisioned-throughput-purchase-model) |
| Cost Governance | Quota Management | Consider Quota management practices. Use dynamic quota for certain use cases when your application can use extra capacity opportunistically or the application itself is driving the rate at which the Azure OpenAI API is called | Azure OpenAI | 🔴 High | [link](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/optimizing-azure-openai-a-guide-to-limits-quotas-and-best/ba-p/4076268) |
| Cost Governance | Cost estimation | Develop your cost model, considering prompt sizes. Understanding prompt input and response sizes and how text translates into tokens helps you create a viable cost model | Azure OpenAI | 🟡 Medium | [link](https://learn.microsoft.com/azure/ai-services/openai/how-to/manage-costs) |
| Cost Governance | Model selection | Consider model pricing and capabilities when you choose models. Start with less-costly models for less-complex tasks like text generation or completion tasks and for complex tasks like language translation or content understanding, consider using more advanced models. Optimize costs while still achieving the desired application performance | Azure OpenAI | 🟡 Medium | [link](https://azure.microsoft.com/pricing/details/cognitive-services/openai-service/) |
| Cost Governance | Usage Optimization | Maximize Azure OpenAI price breakpoints like fine-tuning and model breakpoints like image generation to your advantage. Fine-tuning is charged per hour, use as much time as you have available per hour to improve results without slipping into the next billing period. The cost for generating 100 images is the same as the cost for 1 image | Azure OpenAI | 🟡 Medium | [link](https://learn.microsoft.com/azure/ai-services/openai/how-to/manage-costs) |
| Cost Governance | Usage Optimization | Remove unused fine-tuned models when they're no longer being consumed to avoid incurring an ongoing hosting fee | Azure OpenAI | 🟡 Medium | [link](https://learn.microsoft.com/azure/ai-services/openai/how-to/manage-costs) |
| Cost Governance | Token Optimization | Create concise prompts that provide enough context for the model to generate a useful response. Also ensure that you optimize the limit of the response length. | Azure OpenAI | 🟡 Medium | [link](https://learn.microsoft.com/azure/ai-services/openai/how-to/manage-costs) |

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
