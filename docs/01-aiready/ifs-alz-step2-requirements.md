---
layout: default
title: Step 2 - Requirements & Plan
parent: AI Ready Challenge
nav_order: 2
---

# Step 2: Requirements & Plan

This section is part of the **IFS AI Ready Challenge**. Here, you’ll capture and categorize all requirements—business outcomes, technical constraints, compliance, responsible AI guardrails, and operational needs—and map them to Azure Well-Architected Framework pillars.

---

## Objective

Document and prioritize all critical requirements, ensuring your plan addresses:
- Business outcomes (value delivered)
- Technical constraints (scalability, performance)
- Security & compliance (data protection, regulatory)
- Responsible AI (ethics, fairness, content safety)
- Operational readiness (monitoring, support, management)

---

## Activities

- Review findings from **Step 1: AI Strategy & Plan**.
- As a team, discuss and document:
  1. **Business Outcomes Requirements**: What must AI deliver for IFS’s success? (e.g., fraud reduction, personalized experiences)
  2. **Technical Constraints**: What limits or integrations must you consider? (e.g., data residency, latency targets)
  3. **Security & Compliance**: Which standards must be enforced? (e.g., GDPR, SOC2, encryption)
  4. **Responsible AI Guardrails**: What ethical and safety controls are required? (e.g., bias detection, content safety)
  5. **Operational Requirements**: How will you monitor, manage, and support AI services?
  6. **Map each requirement to a WAF pillar**: Security, Reliability, Performance Efficiency, Cost Optimization, Operational Excellence.

---

## Guidance

> **Reference:**
> - [CAF AI Plan phase](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/ai/plan)
> - [Azure Well-Architected Framework](https://learn.microsoft.com/azure/well-architected/)
>
> - Use a table to capture and prioritize requirements.
> - Tag each requirement by WAF pillar and responsible AI dimension.

**Example Requirements Table:**

| Req Category          | Description                                         | Priority    | WAF Pillar            | Responsible AI   |
|-----------------------|-----------------------------------------------------|-------------|-----------------------|------------------|
| Business Outcomes     | 10% reduction in fraudulent transactions            | Must Have   | Cost Optimization     | N/A              |
| Technical Constraints | <200ms inference latency for models                 | Must Have   | Performance Efficiency| N/A              |
| Security & Compliance | All data encrypted at rest & in transit             | Must Have   | Security              | N/A              |
| Responsible AI        | Bias assessment for model outputs                   | Must Have   | Reliability           | Fairness/Bias    |
| Operational           | 99.9% uptime SLA with 24/7 alerting                 | Nice to Have| Operational Excellence| N/A              |

---

## Success Criteria

- A prioritized table of requirements covering all categories
- Each requirement mapped to a WAF pillar
- Responsible AI guardrails documented
- Team alignment on the plan and priorities

---

[⬅️ Back: Step 1 – AI Strategy & Plan](./ifs-ready-step1-customer.md) | [Next: Step 3 – AI Solution Design ➡️](./ifs-ready-step3-foundations.md)