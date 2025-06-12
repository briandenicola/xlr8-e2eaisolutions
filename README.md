# Workshop: Designing an End-to-End Azure AI Solution

**Version:** 1.1.0  
**Last Updated:** 2025-06-12  
**Tags:** #workshop #azure #ai #landing-zone #trustworthy-ai #documentation

![IFS Logo](./media/images/ifs.png)

## Overview

This workshop guides participants through the end-to-end process of designing a secure, scalable, and governed AI solution on Microsoft Azure, aligning with the Microsoft Cloud Adoption Framework (CAF) and Azure Well-Architected Framework (WAF) principles.

The workshop follows a logical progression that mirrors an organization's AI adoption journey. Participants will first analyze a case study to identify AI use cases and define an AI Strategy and Plan. Participants will then proceed to build an AI Ready platform on Azure, corresponding to designing the foundational infrastructure. Following this, they will Design AI workloads by developing the specific AI solution and integrating it into the platform. The ultimate objective is to run well-architected AI workloads in a production-ready environment, integrating governance, management, and security practices—all aligned toward achieving Trustworthy AI.

**Goal:** To equip participants with the knowledge and design patterns necessary to architect robust enterprise AI solutions on Azure, following the natural evolution from foundation to workload to enterprise-wide scaling.

> Note: This workshop is available as a public GitHub repository, allowing participants to access materials, documentation, and resources easily. The workshop is designed to be hands-on, with practical exercises and discussions throughout the sessions. It is also published as a documentation site using GitHub Pages, providing a structured and navigable format for participants to follow along. Link to github pages: [Workshop Documentation](https://jonathan-vella.github.io/xlr8-e2eaisolutions/)

## Workshop Flow

![Trustworthy AI Logo](./media/images/cafai.png)

## Modules

### Module 1: Understanding the Business Need
#### In scope: CAF AI Strategy - Process to develop an AI strategy | AI Plan - Process to plan for AI adoption

**Objective:** Analyze the customer's (IFS) business drivers, challenges, goals, and specific AI use cases.

**Activities:**  
- Review the customer story.  
- Identify key objectives, success metrics, and initial high-level requirements.

**Materials:**  
- [Customer Story](./docs/ifs-customer-story.md)
- [Workshop Agenda](./docs/04-workshop/workshop-agenda.md)

---

### Module 2: Designing the Azure AI Platform Foundation
#### In scope: CAF: Ready, Govern, Manage, Secure | WAF: Security, Reliability, Operational Excellence

**Objective:** Design a secure, scalable, and well-governed Azure foundation using Landing Zone principles to support IFS's current needs and future AI adoption.

**Activities:**  
- Define platform requirements (security, governance, connectivity).  
- Design the Landing Zone structure (Platform & Application LZs).  
- Establish networking, identity, and security controls.  
- Select core platform services.

**Key Concepts:**  
- Subscription democratization.  
- Identity management.  
- Network topology (Hub-Spoke).  
- Private networking.  
- Azure Policy.  
- Azure Monitor.

**Materials:**  
- [AI Ready Challenge Overview](./docs/01-aiready/ifs-ready-overview.md)
- [Step 1: Understand the Customer](./docs/01-aiready/ifs-ready-step1-customer.md)
- [Step 2: Define Requirements](./docs/01-aiready/ifs-ready-step2-requirements.md)
- [Step 3: Design Foundations](./docs/01-aiready/ifs-ready-step3-foundations.md)
- [Step 4: Present and Justify](./docs/01-aiready/ifs-ready-step4-present.md)
- [References](./docs/references/ai-ready-references.md)

---

### Module 3: Designing the AI Workload - AI Agent Challenge
#### In scope: AI Ready – Process to build AI workloads in Azure | Well Architected Framework

**Objective:** Design a secure internal Retrieval-Augmented Generation (RAG) chatbot application for IFS employees, ensuring it leverages the platform foundation securely and efficiently.

**Activities:**  
- Define workload requirements.  
- Design the application architecture (UI, backend/orchestration, data sources).  
- Select appropriate Azure services for hosting components (e.g., App Service, ML Endpoints).  
- Design the RAG pipeline.  
- Implement security controls (Managed Identities, Key Vault).  
- Plan for monitoring and deployment.

**Key Concepts:**  
- RAG pattern.  
- Agentic AI principles.  
- Azure OpenAI.  
- Azure AI Search.  
- App Service.  
- ML Managed Online Endpoints.  
- Application Gateway.  
- VNet Integration.  
- Private Endpoints.  
- Managed Identities.  
- Application Insights.  
- IaC (Bicep).

**Materials:**  
- [AI Agent Challenge Overview](./docs/02-agent/ifs-agent-overview.md)
- [Step 1: Agentic AI Principles & Patterns](./docs/02-agent/ifs-agent-step1-principles.md)
- [Step 2: Functional Requirements](./docs/02-agent/ifs-agent-step2-functional-requirements.md)
- [Step 3: Non-Functional Requirements](./docs/02-agent/ifs-agent-step3-nonfunctional-requirements.md)
- [Step 4: Solution Design](./docs/02-agent/ifs-agent-step4-solution-design.md)
- [Step 5: Integration](./docs/02-agent/ifs-agent-step5-integration.md)
- [Step 6: Presentation](./docs/02-agent/ifs-agent-step6-presentation.md)
- [References](./docs/references/ai-agent-references.md)

---

### Module 4: Designing the Enterprise AI Hub
#### In scope: Enterprise Scaling, Centralized Governance, Cost Management

**Objective:** Based on lessons learned from the initial RAG chatbot implementation, design a dedicated "AI Hub" that enables enterprise-wide AI adoption with centralized governance and security.

**Activities:**  
- Identify scaling limitations from the initial workload implementation.
- Define requirements for multi-department AI service access.
- Design a secure gateway architecture for AI services.
- Create governance, monitoring, and cost management strategies.
- Establish patterns for secure cross-department connectivity.

**Key Concepts:**  
- Centralized AI service management.
- Secure API gateway.
- Private endpoints at scale.
- Cost allocation.
- Cross-VNet connectivity.
- Standardized development practices.
- Comprehensive monitoring.

**Materials:**  
- [AI Hub Challenge Overview](./docs/03-aihub/ifs-aihub-overview.md)
- [Step 1: Define the Scenario](./docs/03-aihub/ifs-aihub-step1-scenario.md)
- [Step 2: Define Requirements](./docs/03-aihub/ifs-aihub-step2-requirements.md)
- [Step 3: Design Architecture](./docs/03-aihub/ifs-aihub-step3-design.md)
- [Step 4: Present and Justify](./docs/03-aihub/ifs-aihub-step4-present.md)
- [References](./docs/references/ai-hub-references.md)

---

### Module 5: End-to-End Review & Justification

**Objective:** Consolidate the complete solution from foundation to workload to enterprise AI Hub into a cohesive end-to-end architecture.

**Activities:**  
- Review the progression from initial foundation to enterprise AI capabilities.
- Present the final architecture with all components.
- Justify design choices based on requirements, CAF principles, and WAF pillars.
- Discuss potential risks and mitigation strategies.

---

## Key Principles Emphasized

- **Cloud Adoption Framework (CAF):** Applying guidance across Strategy, Plan, Ready, Adopt, Govern, Manage, and Secure phases.  
- **Well-Architected Framework (WAF):** Designing solutions considering the five pillars: Cost Optimization, Operational Excellence, Performance Efficiency, Reliability, and Security.  
- **Security:** Defense-in-depth, private networking, identity-based access control, secure secrets management.  
- **Governance:** Centralized policy enforcement, cost management, resource organization.  
- **Scalability & Reliability:** Designing for growth and resilience.  
- **Automation:** Utilizing Infrastructure as Code (IaC) and CI/CD practices.
- **Enterprise Evolution:** Natural progression from initial workload to enterprise-wide capabilities.

## Documentation Improvements

The documentation for this workshop has been enhanced with several improvements:

### Content Organization
- **Centralized References**: All reference materials are now in a dedicated `/references/` directory
- **Challenge-specific CHANGELOG files**: Track version history for each challenge
- **Table of Contents**: Added to long documentation files for easier navigation

### Standardization
- **Consistent File Naming**: Files follow the pattern `ifs-[challenge]-step[step#]-[slug].md`
- **Uniform Tags**: All files include relevant tags for filtering and search
- **Navigation Structure**: Improved breadcrumb navigation and cross-linking

### Versioning
- **Version Numbers**: All files include semantic versioning (MAJOR.MINOR.PATCH)
- **Last Updated Dates**: Track when content was last modified
- **CHANGELOG**: Comprehensive version history in the root CHANGELOG.md

These improvements make the documentation more maintainable, easier to navigate, and better organized for both facilitators and participants.

## Prerequisites

- Familiarity with fundamental Azure concepts (Subscriptions, Resource Groups, Networking, PaaS services).  
- Basic understanding of AI/ML concepts (LLMs, RAG is helpful but not essential).  
- Experience with architectural design discussions.

---

## Workshop Materials

- [Workshop Home Page](./docs/index.md)
- [Workshop Agenda](./docs/04-workshop/workshop-agenda.md)
- [Scenario definition for Innovate Financial Services](./docs/ifs-customer-story.md)
- [Whiteboard Design Session guide for the Platform Foundation](./docs/01-aiready/ifs-ready-overview.md)
- [Whiteboard Design Session guide for the AI Agent Challenge](./docs/02-agent/ifs-agent-overview.md)
- [Whiteboard Design Session guide for the AI Hub](./docs/03-aihub/ifs-aihub-overview.md)
- [Frequently Asked Questions](./docs/ifs-faq.md)
- [Reference Materials](./docs/references/index.md)
- Workshop presentation slides (available separately)
- IFS logo image at [media/images/ifs.png](./media/images/ifs.png)

## Documentation

- [Documentation Standards](./docs/documentation-standards.md)
- [Documentation Improvements](./docs/documentation-improvements.md)
- [Versioning Guide](./docs/versioning-guide.md)
- [CHANGELOG](./CHANGELOG.md)

---

## GitHub Pages Documentation

This repository is configured to be published as a documentation site using GitHub Pages with:
- Jekyll static site generator
- Just-the-Docs theme for clean navigation and documentation layout

The documentation site structure includes:
- Home page with workshop overview
- Workshop agenda with detailed timeline
- Challenge sessions with step-by-step guides
- Centralized references section
- Navigation hierarchy for easy content exploration
- Version information and last updated dates
- Comprehensive table of contents for long documents
- Consistent tagging system for better search and filtering

---

## References

* [Microsoft Cloud Adoption Framework for Azure](https://learn.microsoft.com/azure/cloud-adoption-framework/)
* [Azure Cloud Adoption Framework - AI Scenario](https://learn.microsoft.com/azure/cloud-adoption-framework/scenarios/ai/)
* [Azure OpenAI baseline Landing Zone reference architecture](https://learn.microsoft.com/azure/architecture/ai-ml/architecture/azure-openai-baseline-landing-zone)
* [Azure OpenAI End-to-End Chat Reference Architecture](https://learn.microsoft.com/azure/architecture/ai-ml/architecture/baseline-openai-e2e-chat)
* [AI Hub Gateway Solution Accelerator](https://github.com/Azure-Samples/ai-hub-gateway-solution-accelerator/tree/main)
* [Scaling AI workloads across the enterprise](https://learn.microsoft.com/azure/cloud-adoption-framework/scenarios/ai/ai-ready/scale-ai-workloads)
* [Just-the-Docs Jekyll Theme](https://just-the-docs.github.io/just-the-docs/)