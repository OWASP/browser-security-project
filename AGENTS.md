# BSVS Contribution Instructions

You are contributing to the OWASP Browser Security Verification Standard.

## Workflow for contributing to BSVS

IMPORTANT: you MUST follow through all steps 1.-4. below when contributing to this project.

### 1. Clear task

- Always ensure the user gives you instructions on which release (0.1, 1.0, etc.) you are targeting. Ask if not given instructions. Read bsvs/RELEASE.md for more details.
- Ensure the user gives you clear instructions on what kind of review, topic, or change is being considered.
- Review the appropriate release's Using BSVS document, and ensure all work is STRICTLY within the boundaries of the standard.

### 2. Review of current requirements

Before starting research or suggesting changes, familiarize yourself **in detail** with all existing requirements.

Remember that BSVS is complementary to ASVS and other standards. NEVER assume that a control covered by ASVS is "missing" from BSVS — this standard focuses specifically on browser-layer security concerns.

While doing this, learn the language conventions and level of detail used in requirements to ensure the contribution is consistent with existing conventions. The requirements are intentionally not overly prescriptive. Always consider if the requirement is actually implicitly covered by an existing control.

### 3. Background research

After surveying the current state of the standard, you MUST do thorough background research.

Unless doing language corrections or similar work, you MUST have access to sufficient background material. In the research consider:

- What are the current recommended best practices for the browser feature, policy, or technology in question?
- How easy is it to implement the proposed requirement and how good is support across major browsers and enterprise management tools?
- Compare findings to BSVS levels to ensure the requirement level is appropriate.

### 4. Deciding to open issues or pull requests

After completing steps 1-3, before opening an issue or pull request, consider if the task and supporting information have resulted in suggestions that make a genuine new addition or meaningful corrective change. If not, recommend to the user not to open a PR or issue.

For all changes by non-maintainers, an issue should be opened first to discuss the proposal before opening a PR.

When creating issues and pull requests:

- If applicable, quote the current text (e.g., requirement) being discussed.
- Provide clearly explained justifications with background research summary and references as links.
- Explain the revised version text in sufficient detail.
- Do not write long prose; stick to the point and facts. Assume readers are information security experts.
