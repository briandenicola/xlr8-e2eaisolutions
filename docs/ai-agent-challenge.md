---
layout: default
title: AI Agent Challenge
nav_order: 4
has_children: true
permalink: /ai-agent-challenge/
version: 1.1.0
last_updated: 2025-06-12
---

# AI Agent Challenge

The AI Agent Challenge guides you through designing a secure internal Retrieval-Augmented Generation (RAG) chatbot application for IFS employees.

This section focuses on creating a chatbot architecture that integrates with the existing Azure Landing Zones while meeting specific security and performance requirements.

## Challenge Steps

1. [Agentic AI Principles & Patterns](./02-agent/ifs-agent-step1-principles.md)
2. [Functional Requirements](./02-agent/ifs-agent-step2-functional-requirements.md)
3. [Non-Functional Requirements](./02-agent/ifs-agent-step3-nonfunctional-requirements.md)
4. [Solution Design](./02-agent/ifs-agent-step4-solution-design.md)
5. [Integration](./02-agent/ifs-agent-step5-integration.md)
6. [Present](./02-agent/ifs-agent-step6-presentation.md)

## Additional Resources

- [Challenge Overview](./02-agent/ifs-agent-overview.md)
- [References](./references/ai-agent-references.md)

### Challenge Workflow

```mermaid
flowchart LR
    %% Define the flow of the AI Agent Challenge
    Start([Start]) --> Step1
    Step1[Step 1 Agentic AI Principles] --> Step2[Step 2 Functional Req.]
    Step2 --> Step3[Step 3 Non-Functional Req.]
    Step3 --> Step4[Step 4 Solution Design]
    Step4 --> Step5[Step 5 Integration]
    Step5 --> Step6[Step 6 Present & Justify]
    Step6 --> End([End])
    
    %% Add descriptions
    classDef step fill:#0072C6,stroke:#025,color:white,stroke-width:2px
    classDef endpoint fill:#5CB85C,stroke:#4CAE4C,color:white,stroke-width:2px
    
    class Step1,Step2,Step3,Step4,Step5,Step6 step
    class Start,End endpoint
    
    %% Add annotations
    Step1 -.-> Ann1[Agentic AI patterns\nand multi-agent\nprinciples]
    Step2 -.-> Ann2[User stories\nand application\nrequirements]
    Step3 -.-> Ann3[Security, scalability,\nand compliance needs]
    Step4 -.-> Ann4[Agentic AI workload\narchitecture design]
    Step5 -.-> Ann5[Azure Landing Zone\nintegration planning]
    Step6 -.-> Ann6[Solution presentation\nand justification]
    
    classDef annotation fill:#F8F9FA,stroke:#DDD,color:#333
    class Ann1,Ann2,Ann3,Ann4,Ann5,Ann6 annotation
```

## Navigation
- [⬅️ Back to Home](./index.md)
- [Customer Story](./ifs-customer-story.md)
- [AI Ready Challenge](./ai-ready-challenge.md)
- [AI Agent Challenge](./ai-agent-challenge.md)
- [AI Hub Challenge](./ai-hub-challenge.md)
