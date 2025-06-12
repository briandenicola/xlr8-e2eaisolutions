# 📚 Documentation Issue Templates Guide

> **Executive Summary:**  
> This guide explains when and how to use the specialized issue templates for managing documentation tasks in the XLR8 E2E Azure AI Solutions workshop repository.

![Documentation Workflow Banner](https://via.placeholder.com/800x200?text=XLR8+Documentation+Workflow)

## 🧰 Available Templates

We have created four specialized issue templates to help manage documentation tasks:

| 📝 Template | 🎯 Purpose | 🔍 When to Use |
|------------|-----------|--------------|
| **📚 Documentation Task** | Comprehensive template for complex documentation tasks | For tasks needing multiple reviewers and formal approval |
| **🔄 Content Update** | Streamlined template for updating existing content | For straightforward changes to existing documents |
| **🌟 New Content Creation** | Template focused on creating new documentation | For developing entirely new content or sections |
| **🐞 Documentation Issue** | Template for reporting problems or errors | For highlighting issues in existing documentation |

## ⏱️ Choosing the Right Template

<details>
<summary>📚 <b>Documentation Task Template</b></summary>

### When to Use:
- ✅ Complex changes affecting multiple files
- ✅ Tasks requiring coordination between multiple contributors
- ✅ Changes that need formal review and approval steps
- ✅ Documentation that crosses challenge boundaries
- ✅ Major restructuring of existing content

### Effort Level: ☕☕☕ (Medium to Large)

</details>

<details>
<summary>🔄 <b>Content Update Template</b></summary>

### When to Use:
- ✅ Minor text changes or corrections
- ✅ Adding new sections to existing documents
- ✅ Updating screenshots or diagrams
- ✅ Revising examples or explanations
- ✅ Improving clarity without changing technical content

### Effort Level: ☕ to ☕☕ (Small to Medium)

</details>

<details>
<summary>🌟 <b>New Content Creation Template</b></summary>

### When to Use:
- ✅ Creating entirely new documentation files
- ✅ Developing new challenge steps
- ✅ Adding new reference materials or guides
- ✅ Creating new diagrams or visual aids
- ✅ Introducing new concepts or technologies

### Effort Level: ☕☕ to ☕☕☕☕ (Medium to Very Large)

</details>

<details>
<summary>🐞 <b>Documentation Issue Template</b></summary>

### When to Use:
- ✅ Reporting errors or inaccuracies
- ✅ Highlighting formatting issues
- ✅ Noting broken links or references
- ✅ Suggesting improvements
- ✅ Flagging outdated information

### Effort Level: n/a (Reporting Only)

</details>

## 👥 Role-Based Workflow

Our documentation process involves specific roles working together:

| 🧑‍💻 Role | 📋 Responsibility | 🔍 Focus Areas |
|----------|------------------|--------------|
| **Content Author** | Creates or modifies documentation | Structure, clarity, completeness |
| **Technical Reviewer** | Ensures technical accuracy | Azure/AI concepts, code samples |
| **Documentation Reviewer** | Verifies standards compliance | Formatting, navigation, accessibility |
| **Final Approver** | Provides final sign-off | Strategic alignment, overall quality |

![Documentation Workflow](https://via.placeholder.com/800x200?text=Documentation+Review+Workflow)

## 💡 Tips for Effective Issue Creation

<table>
  <tr>
    <td width="50%">
      <h3>Do:</h3>
      <ul>
        <li>✅ Be specific about what needs to be done</li>
        <li>✅ Link related issues and cross-references</li>
        <li>✅ Set realistic deadlines for writing and review</li>
        <li>✅ Include helpful reference materials</li>
        <li>✅ Complete all required template fields</li>
      </ul>
    </td>
    <td width="50%">
      <h3>Avoid:</h3>
      <ul>
        <li>❌ Creating vague or overly broad issues</li>
        <li>❌ Combining multiple unrelated changes</li>
        <li>❌ Setting unrealistic timelines</li>
        <li>❌ Forgetting to assign appropriate labels</li>
        <li>❌ Skipping the checklist sections</li>
      </ul>
    </td>
  </tr>
</table>

## 📝 Example Issues

Here are examples of how to use each template effectively:

<details>
<summary>📚 <b>Documentation Task Example</b></summary>

```markdown
Title: [AI Ready] - Improve Cloud Adoption Framework references and diagrams

Challenge Area: AI Ready Challenge
Task Type: Content Update
Related Files: 
  - docs/ai-ready/ifs-aiready-step2-principles.md
  - docs/ai-ready/ifs-aiready-step3-architecture.md
Estimated Time: ☕☕☕ Large (4+ hours)

Description:
Update all Cloud Adoption Framework references to align with the latest Microsoft guidance. 
Create new Mermaid diagrams to illustrate the integration points with Azure AI services.
```

</details>

<details>
<summary>🔄 <b>Content Update Example</b></summary>

```markdown
Title: [AI Agent] - Update: RAG pattern description with latest Azure OpenAI capabilities

Challenge Area: AI Agent Challenge
File(s) to Update: docs/ai-agent/ifs-aiagent-step1-principles.md
Estimated Time: ☕☕ Medium (1-2 hours)
Priority: 🟠 High

What Needs to Be Updated:
The RAG pattern description needs to incorporate the latest Azure OpenAI capabilities
including semantic ranking and the newest embedding models.
```

</details>

<details>
<summary>🌟 <b>New Content Creation Example</b></summary>

```markdown
Title: [AI Hub] - New: Create security best practices guide for AI Hub implementation

Challenge Area: AI Hub Challenge
File Path: docs/ai-hub/ifs-aihub-security-guide.md
Estimated Time: ☕☕☕☕ Very Large (8+ hours)
Version for Inclusion: v1.2.0

Content Overview:
A comprehensive security guide for implementing AI Hub solutions, covering authentication,
authorization, data protection, and secure API access patterns.
```

</details>

<details>
<summary>🐞 <b>Documentation Issue Example</b></summary>

```markdown
Title: [General] - Issue: Broken links in references section

Challenge Area: General Documentation
Affected File(s): docs/references/external-resources.md
Severity: 🟡 Medium

Issue Description:
Multiple links in the external resources page are broken or pointing to outdated content.
Specifically, the links to Azure OpenAI documentation and the Responsible AI guidelines.
```

</details>

## 🔄 Issue Management Workflow

![Issue Management Workflow](https://via.placeholder.com/800x300?text=Issue+Management+Workflow)

| 📊 Stage | 🎯 Actions | ✅ Success Criteria |
|---------|-----------|-------------------|
| **Creation** | Submit issue with appropriate template | All required fields completed |
| **Triage** | Assign priority, reviewers, due date | Team members assigned within 2 days |
| **Implementation** | Complete work according to requirements | All checklist items addressed |
| **Review** | Technical and documentation review | Approvals from all required reviewers |
| **Completion** | Merge changes, close issue | Documentation published and verified |

> **Pro Tip:** Use the workflow status checkboxes to track progress through these stages.

---

<div align="center">
  
## 🚀 Elevate Your Documentation Game!

Great documentation drives understanding, adoption, and success.  
Use these templates to streamline your process and deliver amazing content.

[View Documentation Standards](https://github.com/jonathan-vella/xlr8-e2eaisolutions/blob/main/docs/documentation-standards.md) | 
[View Versioning Guide](https://github.com/jonathan-vella/xlr8-e2eaisolutions/blob/main/docs/versioning-guide.md)

</div>

---

*Last updated: June 2023*
