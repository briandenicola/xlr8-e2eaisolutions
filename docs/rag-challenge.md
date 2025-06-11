---
layout: default
title: Agentic AI Challenge
nav_order: 4
has_children: true
permalink: /rag-challenge/
---

# Agentic AI Challenge

The Agentic AI Challenge guides you through designing a secure internal Retrieval-Augmented Generation (RAG) chatbot application for IFS employees.

This section focuses on creating a chatbot architecture that integrates with the existing Azure Landing Zones while meeting specific security and performance requirements.

## Challenge Steps

1. [Agentic AI Principles & Patterns](./02-rag/ifs-rag-step1-agentic-ai-principles.md)
2. [Functional Requirements](./02-rag/ifs-rag-step2-fr.md)
3. [Non-Functional Requirements](./02-rag/ifs-rag-step3-nfr.md)
4. [Solution Design](./02-rag/ifs-rag-step4-design.md)
5. [Integration](./02-rag/ifs-rag-step5-integrate.md)
6. [Present](./02-rag/ifs-rag-step6-present.md)

### Challenge Workflow

```mermaid
flowchart LR
    %% Define the flow of the Agentic AI Challenge
    Start([Start]) --> Step1
    Step1[Step 1:\nAgentic AI Principles] --> Step2[Step 2:\nFunctional Req.]
    Step2 --> Step3[Step 3:\nNon-Functional Req.]
    Step3 --> Step4[Step 4:\nSolution Design]
    Step4 --> Step5[Step 5:\nIntegration]
    Step5 --> Step6[Step 6:\nPresent & Justify]
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

## Additional Resources

- [Overview](./02-rag/ifs-rag-overview.md)
- [References](./02-rag/ifs-rag-references.md)

## Navigation
- [⬅️ Back to Home](./index.md)
- [Customer Story](./ifs-customer-story.md)
- [AI Ready Challenge](./ai-ready-challenge.md)
- [AI Hub Challenge](./ai-hub-challenge.md)
