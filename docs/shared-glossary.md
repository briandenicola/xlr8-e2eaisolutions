---
layout: default
title: AI Challenge Glossary
nav_order: 8
---

# AI Challenge Glossary

This glossary provides definitions for key terms used across all three AI challenges (AI Ready, AI Agent, and AI Hub). Use this as a reference to understand the terminology consistently throughout the challenges.

## Cross-Challenge Integration

This section explains how the three challenges build upon each other in the XLR8 journey:

| Challenge | Builds on Previous | Enables Next | Key Contribution |
|-----------|-------------------|--------------|------------------|
| **AI Ready** | N/A - Foundation | Provides secure infrastructure for AI Agent | Secure, governed Azure foundation with landing zones |
| **AI Agent** | Uses AI Ready foundation | Informs AI Hub design | RAG chatbot implementation proving the concept |
| **AI Hub** | Scales patterns from both challenges | N/A - Final stage | Enterprise-wide AI service management |

> [!TIP]
> Each challenge delivers value independently, but together they form a comprehensive AI transformation journey.

## AI Concepts

| Term | Definition |
|------|------------|
| **AI Foundation** | The underlying infrastructure, policies, and governance required to support AI workloads in an organization. |
| **AI Hub** | A centralized platform for managing, governing, and providing access to AI services across an organization. |
| **AI Landing Zone** | A secure, scalable, and governed cloud environment specifically designed for AI workloads. |
| **Agentic AI** | AI systems that can operate with some degree of autonomy to accomplish tasks or objectives. |
| **Agents** | AI components that can perceive their environment, make decisions, and take actions to achieve goals. |
| **Embeddings** | Vector representations of text, images, or other data that capture semantic meaning for use in AI applications. |
| **Generative AI** | AI systems that can generate new content, such as text, images, code, or other media. |
| **LLM** | Large Language Model - AI models trained on vast amounts of text data that can understand and generate human language. |
| **Multi-Agent System** | A system composed of multiple interacting intelligent agents working together. |
| **Orchestration** | The coordination and management of multiple AI components or services to work together. |
| **RAG** | Retrieval-Augmented Generation - A technique that enhances AI responses by retrieving relevant information from external sources. |
| **Vector Database** | A specialized database designed to store and retrieve vector embeddings efficiently. |

## Azure Services & Components

| Azure Service | Description | Used In |
|---------------|-------------|---------|
| **Azure AI Search** | Managed search service with AI capabilities for content retrieval. | AI Agent, AI Hub |
| **Azure AI Services** | Collection of AI services for vision, language, speech, and decision making. | AI Hub |
| **Azure OpenAI Service** | Microsoft's managed offering of OpenAI models (GPT-4, etc.) on Azure. | AI Agent, AI Hub |
| **Azure Landing Zone** | The Azure implementation of a landing zone - a secure, governed environment. | AI Ready |
| **Azure Policy** | Service for creating, assigning, and managing policies that enforce rules on resources. | AI Ready, AI Hub |
| **Entra ID** | Microsoft's identity and access management service (formerly Azure AD). | All Challenges |
| **Key Vault** | Service for secure management of keys, secrets, and certificates. | All Challenges |
| **Private Endpoints** | Network interfaces that connect privately to Azure services from a virtual network. | All Challenges |

## Governance & Security

| Term | Definition |
|------|------------|
| **Data Residency** | Requirements governing the physical location where data can be stored and processed. |
| **Guardrails** | Constraints applied to AI systems to ensure safety, security, and compliance. |
| **RBAC** | Role-Based Access Control - security model that restricts system access based on roles. |
| **Responsible AI** | Ethical principles and practices that guide the development and use of AI systems. |
| **Zero Trust** | Security model that eliminates implicit trust by continuously validating every access request. |

## Project XLR8 (IFS) Terminology

| Term | Definition |
|------|------------|
| **IFS** | International Financial Services - the fictional company in our challenges. |
| **Knowledge Assistant** | The RAG-based chatbot application developed in the AI Agent Challenge. |
| **Project XLR8** | The overarching AI transformation initiative at IFS that includes all three challenges. |

## Challenge-Spanning Concepts

| Concept | Appears in All Challenges As |
|---------|------------------------------|
| **Governance** | AI Ready: Foundational policies<br>AI Agent: Application-level controls<br>AI Hub: Enterprise-wide management |
| **Security** | AI Ready: Network & identity framework<br>AI Agent: Implementation security<br>AI Hub: Centralized security controls |
| **Cost Management** | AI Ready: Foundation budget & controls<br>AI Agent: Application-specific costs<br>AI Hub: Enterprise-wide optimization |
| **Scalability** | AI Ready: Infrastructure foundation<br>AI Agent: Single application design<br>AI Hub: Multi-tenant platform |

## Implementation Progression

| Component | Challenge 1: AI Ready | Challenge 2: AI Agent | Challenge 3: AI Hub |
|-----------|------------------------|---------------------|--------------------|
| **Azure OpenAI** | Governance planning | Single deployment | Centralized service |
| **Data Storage** | Infrastructure design | Application storage | Enterprise data lake |
| **Identity** | Foundation Entra ID setup | Application access controls | Centralized identity management |
| **Monitoring** | Base platform monitoring | Application telemetry | Cross-platform observability |

## References

For more comprehensive definitions, refer to:
- [Microsoft Azure AI Documentation](https://learn.microsoft.com/en-us/azure/ai-services/)
- [Cloud Adoption Framework for AI](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/ai/)
- [Azure Well-Architected Framework](https://learn.microsoft.com/en-us/azure/architecture/framework/)
- [Azure OpenAI Service documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/)
- [Microsoft Responsible AI Principles](https://www.microsoft.com/en-us/ai/responsible-ai)
