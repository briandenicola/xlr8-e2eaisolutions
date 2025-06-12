- @azure Rule - Use Azure Best Practices: When generating code for Azure, running terminal commands for Azure, or performing operations related to Azure, invoke your `azure_development-get_best_practices` tool if available.
- You are not allowed to modify the "config.yyml" file in the root directory unless explicitly instructed to do so.

## 🛠️ GitHub Copilot Instructions: Documentation Improvement Tasks

### 1. Standardize Naming Conventions
- Help me name challenge titles using consistent patterns: `AI Ready Challenge`, `AI Hub Challenge`, and `AI Agent Challenge` (avoid "Agentic AI Challenge").
- Help me Use unified file naming: `ifs-[challenge]-step[step#]-[slug].md` (example: `ifs-aihub-step1-scenario.md`).

### 2. Improve Navigation
- Add breadcrumb navigation to the top of each `.md` file.
- Insert "Back to Top" links after each major section in long files.
- Include previous/next navigation at both the top and bottom of each page.

### 3. Enhance Visual Layout
- Where applicable, recommend me to add Mermaid diagrams for challenge workflows.
- Use consistent headings and subheadings across all challenges.
- Use relevant icons for each step type: 📝 (requirements), 🏗️ (design), etc.
- Add step progress indicators at the top: `"Step X of Y"`.

### 4. Strengthen Content Quality
- Add a 2–3 sentence executive summary at the top of each `.md` file.
- Include estimated time to complete each step.
- Add explicit links to prerequisites for dependent steps.
- Standardize success criteria formatting across all docs.

### 5. Improve Technical Sections
- Use language-specific fenced code blocks (e.g., \`\`\`json or \`\`\`yaml).
- Convert implementation variations (e.g., PowerShell vs. CLI) into tabbed content.
- Use callout boxes for warnings, notes, and tips consistently.

### 6. Strengthen Cross-Challenge Integration
- Add cross-links between relevant steps across challenges.
- Explain how challenges build on each other (add flow diagrams or context).
- Create and use a shared glossary across all challenge documents.

### 7. Organize Documentation Better
- Add tags (e.g., `#aihub`, `#rag`, `#agents`) for better filtering.
- Include a detailed Table of Contents for longer files.
- Move reference materials to a dedicated `/references/` folder.

### 8. Enhance Accessibility & Usability
- Ensure all images have descriptive alt text.
- Provide print-friendly versions (`.pdf` or `.print.md`) for core challenges.
- Ensure diagrams and styles support both dark and light mode.

### 9. Boost SEO & Discoverability
- Add meta descriptions to the top of each `.md` for search engines.
- Include relevant keywords in headings and intros.

### 10. Plan for Future-Proofing
- Add version numbers and "Last Updated" dates to each document.
- Maintain a `CHANGELOG.md` in the root or inside each challenge folder.

### 11. If it works, don't touch it.
- You are not allowed to modify the "config.yml" file in the root directory unless explicitly instructed to do so.

### 12. Use the provided tools
- @azure Rule - Use Azure Best Practices: When generating code for Azure, running terminal commands for Azure, or performing operations related to Azure, invoke your `azure_development-get_best_practices` tool if available.

