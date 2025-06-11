---
layout: default
title: Step 4 - Solution Design
parent: AI Agent Challenge
nav_order: 4
---

# Step 4: Solution Design

This section is part of the **IFS Agentic AI challenge**. Here, you’ll design the end-to-end architecture for the IFS Knowledge Assistant chatbot, ensuring alignment with Azure best practices and the Baseline OpenAI E2E Chat reference architecture.

---

## Objective

Define the architecture, controls, and Azure services needed for a robust, secure, and scalable RAG solution.

---

## Activities

- Review your requirements from Step 2.
- As a team, design and document:
  1. **Architecture Diagram:** Sketch a high-level diagram of the RAG solution (UI, orchestration, retrieval, LLM backend, networking, identity, security, monitoring, etc.)
  2. **Azure Services:** List and justify the core Azure services and controls you will use (e.g., App Service, AI Search, OpenAI, Key Vault, Log Analytics).
  3. **Security & Governance:** Describe how you will enforce governance, compliance, and security (e.g., policies, private endpoints, managed identities).
  4. **Operational Readiness:** Outline how you will monitor, manage, and support the environment.
  5. **Reliability & Performance:** How will you ensure high availability, redundancy, and performance for the RAG workload?
  6. **Networking:** What network topologies and controls will you use to secure and connect RAG components?
  7. **Deployment:** How will you use IaC and CI/CD to automate deployment and updates?

---

## Guidance

> **Reference:** [Baseline OpenAI E2E Chat reference architecture](https://learn.microsoft.com/azure/architecture/ai-ml/architecture/baseline-openai-e2e-chat) and [Azure Best Practices](../05-azure-best-practices/)
>
> - Use diagrams and tables to clarify your design.
> - Justify your Azure service choices based on requirements and best practices.
> - Consider both current and future needs for scalability and governance.

---

## Success Criteria

By the end of this step, you should have:
- Presented a clear architecture diagram with all major components and Azure services
- Justified your service selection and design decisions
- Described your approach to security, governance, and operational excellence
- Outlined your deployment and monitoring strategy

---

## Navigation
- [⬅️ Back to Step 3](./ifs-rag-step3-nfr.md)
- [Next: Step 5 – Integration ➡️](./ifs-rag-step5-integrate.md)