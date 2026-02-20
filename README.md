## Overview

**Profile:** natalierharris  
**Date:** 2026-02-20

This README summarizes a conversation about the distinction between GitHub Code Quality features and GitHub Copilot code review.

---

## Key Takeaways

- **GitHub Code Quality (traditional):** Typically refers to deterministic checks such as linters, automated tests, static analysis, and security scans — not AI-driven by default.
- **GitHub Copilot Code Review:** An LLM-based code review experience that uses AI to analyze pull requests and surface suggestions.
- **AI-assisted features in Code Quality:** Some Code Quality tooling includes AI-assisted capabilities (e.g., Copilot Autofix for security alerts), but the core checks are rule-based.
- **Product perspective:** A product design director noted that "Code Quality has standard findings and AI Findings, 100% powered by AI." This suggests there may be a product surface — potentially within a Copilot or AI review experience — labeled "Code Quality" where both "standard" (standardized categories) and explicitly labeled AI findings are produced by AI models.
- **Terminology matters:** The meaning of "Code Quality" depends on context — it could refer to GitHub's Security/Code Scanning tab, the Checks tab on a PR, or a Copilot-powered review experience.

---

## Open Questions / Next Steps

- **Where does this feature surface?** Clarify whether "Code Quality" appears in the PR Copilot review panel, the Security/Code Scanning tab, or the Checks tab — each has different underlying technology.
- **Definition alignment:** Align on a shared definition of "Code Quality" across product, design, and engineering to avoid confusion between rule-based and AI-generated findings.
- **Task started:** A Copilot coding task was initiated as a follow-up action from this conversation.
