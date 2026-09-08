# V7: AI & Agentic Browsing

## Control Objective

This chapter addresses the controls for managing AI-enabled browser capabilities, agentic extensions, prompt injection risks, and AI data handling within the browser environment.

---

## V7.1 Inventory & Sanctioning of AI Capabilities

| # | Description | Level |
| :---: | --- | :---: |
| **7.1.1** | **Verify that** AI-enabled browsers, sidebars, copilots, and agentic extensions in use are inventoried and classified as sanctioned or unsanctioned. | 2 |
| **7.1.2** | **Verify that** policy defines which AI browsing capabilities are permitted, for which users, and with access to which data classes. | 2 |
| **7.1.3** | **Verify that** unsanctioned AI browsers and agentic extensions can be technically blocked on managed endpoints. | 2 |

---

## V7.2 Agent Authority & Session Access

| # | Description | Level |
| :---: | --- | :---: |
| **7.2.1** | **Verify that** agentic capabilities cannot operate with access to authenticated corporate sessions unless explicitly sanctioned for that application. | 2 |
| **7.2.2** | **Verify that** sanctioned agents operate under least privilege: scoped to defined sites/tasks, with sensitive actions (payments, permission changes, data export, sending communications) requiring human confirmation. | 3 |
| **7.2.3** | **Verify that** agent sessions are distinguishable from human sessions in application and identity logs. | 3 |

---

## V7.3 Prompt Injection & Content Manipulation

| # | Description | Level |
| :---: | --- | :---: |
| **7.3.1** | **Verify that** the organization has assessed prompt-injection risk (page content or documents steering agent behavior) for each sanctioned agentic capability. | 2 |
| **7.3.2** | **Verify that** mitigations exist for untrusted-content-driven agent actions (e.g., restricting agent browsing to trusted origins, isolating agent context from sensitive tabs, requiring confirmation for actions initiated after processing untrusted content). | 3 |

---

## V7.4 AI Data Handling & Auditability

| # | Description | Level |
| :---: | --- | :---: |
| **7.4.1** | **Verify that** data submitted to AI browser features is governed by the data protection controls in V5, including page-context capture by sidebars/copilots. | 2 |
| **7.4.2** | **Verify that** sanctioned AI browsing features log actions taken and data accessed sufficiently to support incident investigation. | 2 |
| **7.4.3** | **Verify that** AI browsing capabilities are included in incident response planning, including revoking agent access and investigating agent-performed actions. | 3 |
