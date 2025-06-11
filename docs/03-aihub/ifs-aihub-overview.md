---
layout: default
title: AI Hub Challenge Overview
parent: AI Hub Challenge
nav_order: 0
tags: [ai-hub, overview, architecture, governance]
---

# AI Hub Challenge Overview

[Home](../../index.md) > [AI Hub Challenge](../../ai-hub-challenge.md) > [Overview](./ifs-aihub-overview.md)

- [Next: Step 1 - Scenario ➡️](./ifs-aihub-step1-scenario.md)

Welcome to the **IFS AI Hub Challenge**. This challenge guides you through designing a secure, scalable, and governed Azure-based AI Hub to centrally manage and control shared AI services for IFS, building on lessons learned from the RAG chatbot implementation.

## Table of Contents
{:.no_toc}

* TOC
{:toc}

*Note: Generated using Jekyll's automatic table of contents feature*

---

## Challenge Objectives

- Analyze IFS’s business context and drivers for a centralized AI Hub
- Identify and prioritize business, technical, and compliance requirements
- Design a robust Azure AI Hub architecture aligned with best practices
- Present and justify your solution to peers

[🔝 Back to Top](#ai-hub-challenge-overview)

---

## Challenge Structure

This challenge is divided into four steps:

1. [Step 1: Scenario](./ifs-aihub-step1-scenario.md) – Analyze the business scenario and user needs
2. [Step 2: Requirements](./ifs-aihub-step2-requirements.md) – Identify and document requirements
3. [Step 3: Design](./ifs-aihub-step3-design.md) – Design the AI Hub architecture
4. [Step 4: Present](./ifs-aihub-step4-present.md) – Present and justify your solution

[🔝 Back to Top](#ai-hub-challenge-overview)

## Challenge Workflow (Visual)

```mermaid
flowchart LR
    %% Define the flow of the AI Hub Challenge
    Start([Start]) --> Step1
    Step1[Step 1:<br>Scenario] --> Step2[Step 2:<br>Requirements]
    Step2 --> Step3[Step 3:<br>Design]
    Step3 --> Step4[Step 4:<br>Present & Justify]
    Step4 --> End([End])
    
    %% Add descriptions
    classDef step fill:#0072C6,stroke:#025,color:white,stroke-width:2px
    classDef endpoint fill:#5CB85C,stroke:#4CAE4C,color:white,stroke-width:2px
    
[🔝 Back to Top](#ai-hub-challenge-overview)
    
    class Step1,Step2,Step3,Step4 step
    class Start,End endpoint
    
    %% Add annotations
    Step1 -.-> Ann1[Business scenario<br>and use case<br>analysis]
    Step2 -.-> Ann2[Business, technical<br>and compliance<br>requirements]
    Step3 -.-> Ann3[Centralized AI Hub<br>architecture design]
    Step4 -.-> Ann4[Solution presentation<br>and justification]
```

---

## How to Use This Challenge

- Work as a team to complete each step in order
- Use the provided activities, guidance, and success criteria to structure your work
- Reference the [Azure Best Practices](../05-azure-best-practices/) for proven recommendations
- Document your findings and designs for each step

---

## Navigation
- [Next: Step 1 - Scenario ➡️](./ifs-aihub-step1-scenario.md)
- [🏠 AI Hub Challenge Home](../../ai-hub-challenge.md)