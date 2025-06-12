---
layout: default
title: AI Hub Challenge
nav_order: 5
has_children: true
permalink: /ai-hub-challenge/
version: 1.1.0
last_updated: 2025-06-12
---

# AI Hub Challenge

The AI Hub Challenge guides you through designing a dedicated, secure "AI Hub" environment to centrally manage and control access to shared Azure AI services.

This section focuses on creating a scalable architecture for enterprise-wide AI governance and management.

## Challenge Steps

1. [Scenario](./03-aihub/ifs-aihub-step1-scenario.md)
2. [Requirements](./03-aihub/ifs-aihub-step2-requirements.md)
3. [Design](./03-aihub/ifs-aihub-step3-design.md)
4. [Present](./03-aihub/ifs-aihub-step4-present.md)

## Additional Resources

- [Overview](./03-aihub/ifs-aihub-overview.md)
- [References](./references/ai-hub-references.md)

### Challenge Workflow

```mermaid
flowchart LR
    %% Define the flow of the AI Hub Challenge
    Start([Start]) --> Step1
    Step1[Step 1 Scenario] --> Step2[Step 2 Requirements]
    Step2 --> Step3[Step 3 Design]
    Step3 --> Step4[Step 4 Present & Justify]
    Step4 --> End([End])
    
    %% Add descriptions
    classDef step fill:#0072C6,stroke:#025,color:white,stroke-width:2px
    classDef endpoint fill:#5CB85C,stroke:#4CAE4C,color:white,stroke-width:2px
    
    class Step1,Step2,Step3,Step4 step
    class Start,End endpoint
    
    %% Add annotations
    Step1 -.-> Ann1[Business scenario\nand use case\nanalysis]
    Step2 -.-> Ann2[Business, technical\nand compliance\nrequirements]
    Step3 -.-> Ann3[Centralized AI Hub\narchitecture design]
    Step4 -.-> Ann4[Solution presentation\nand justification]
    
    classDef annotation fill:#F8F9FA,stroke:#DDD,color:#333
    class Ann1,Ann2,Ann3,Ann4 annotation
```
