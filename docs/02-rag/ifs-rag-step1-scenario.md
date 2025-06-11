---
layout: default
title: Step 1 - Scenario
parent: Agentic AI challenge
nav_order: 1
---

# Step 1: Scenario

This section is part of the **IFS Agentic AI challenge**. Here, you’ll analyze the business scenario and user needs for the IFS Knowledge Assistant chatbot.

---

## Objective

Understand the business context, user needs, and high-level goals for the RAG chatbot solution.

---

## Activities

- Review the scenario below.
- As a team, discuss and answer:
  1. **What are the main user needs and business drivers for the IFS Knowledge Assistant?**
  2. **What are the high-level inputs, processes, and outputs for this solution?**
  3. **What are the key constraints (e.g., private network, Azure AI Search, security)?**

---

## Scenario
Innovate Financial Services (IFS) wants to empower its employees by providing quick and accurate answers to questions about internal policies, procedures, and market analysis reports. They have decided to build an internal web-based chatbot, the "IFS Knowledge Assistant". This application needs to:

- Understand employee questions in natural language
- Securely access a curated set of internal documents via Azure AI Search
- Use an approved Azure OpenAI model to generate grounded answers
- Present answers through a simple, intuitive web interface
- Adhere to IFS's security and compliance standards, running entirely within their private Azure network
- Be maintainable and deployable using modern DevOps practices (including IaC)

---

## Guidance

> **Tip:** Focus on extracting the key business drivers, user needs, and constraints that will inform your design decisions. Reference the [Baseline OpenAI E2E Chat reference architecture](https://learn.microsoft.com/azure/architecture/ai-ml/architecture/baseline-openai-e2e-chat) and [Azure Best Practices](../05-azure-best-practices/).

---

## Success Criteria

By the end of this step, you should have:
- Identified the primary input (user query) and output (generated answer)
- Listed the core processing steps (retrieve, augment, generate)
- Listed at least three distinct functional components (e.g., UI, Orchestration, Search, LLM interaction)
- Acknowledged key constraints (private network, Azure AI Search, security)

---

## Navigation
- [⬅️ Back to Overview](./ifs-rag-overview.md)
- [Next: Step 2 – Requirements ➡️](./ifs-rag-step2-requirements.md)