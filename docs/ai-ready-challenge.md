---
layout: default
title: AI Ready Challenge
nav_order: 3
has_children: true
permalink: /ai-ready-challenge/
---

# AI Ready Challenge

The AI Ready Challenge guides you through designing a secure, scalable, and governed Azure foundation to support IFS's AI transformation journey.

This section walks you through the process of designing Azure Landing Zones aligned with IFS's business requirements and security standards.

## Challenge Steps

1. [Customer Context](./01-aiready/ifs-ready-step1-customer.md)
2. [Requirements](./01-aiready/ifs-ready-step2-requirements.md)
3. [Foundations Design](./01-aiready/ifs-ready-step3-foundations.md)
4. [Present](./01-aiready/ifs-ready-step4-present.md)

## Additional Resources

- [Overview](./01-aiready/ifs-ready-overview.md)
- [References](./ifs-alz-references.md)

### Challenge Workflow

```mermaid
flowchart LR
    %% Define the flow of the AI Ready Challenge
    Start([Start]) --> Step1
    Step1[Step 1:\nCustomer Context] --> Step2[Step 2:\nRequirements]
    Step2 --> Step3[Step 3:\nFoundations Design]
    Step3 --> Step4[Step 4:\nPresent & Justify]
    Step4 --> End([End])
    
    %% Add descriptions
    classDef step fill:#0072C6,stroke:#025,color:white,stroke-width:2px
    classDef endpoint fill:#5CB85C,stroke:#4CAE4C,color:white,stroke-width:2px
    
    class Step1,Step2,Step3,Step4 step
    class Start,End endpoint
    
    %% Add annotations
    Step1 -.-> Ann1[Business context\nand AI strategy\nassessment]
    Step2 -.-> Ann2[Business, technical\nand compliance\nrequirements]
    Step3 -.-> Ann3[Azure Landing Zone\nfoundation design]
    Step4 -.-> Ann4[Solution presentation\nand justification]
    
    classDef annotation fill:#F8F9FA,stroke:#DDD,color:#333
    class Ann1,Ann2,Ann3,Ann4 annotation
```

## Navigation
- [⬅️ Back to Home](./index.md)
- [Customer Story](./ifs-customer-story.md)
- [AI Ready Challenge](./ai-ready-challenge.md)
- [AI Agent Challenge](./ai-agent-challenge.md)
- [AI Hub Challenge](./ai-hub-challenge.md)
