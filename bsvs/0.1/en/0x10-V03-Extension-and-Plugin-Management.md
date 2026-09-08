# V3: Extension & Plugin Management

## Control Objective

This chapter addresses the controls for managing the lifecycle of browser extensions and plugins, from installation through runtime monitoring and removal.

---

## V3.1 Installation Control

| # | Description | Level |
| :---: | --- | :---: |
| **3.1.1** | **Verify that** users cannot install extensions from arbitrary or unofficial sources (sideloading, developer mode) on managed browsers. | 1 |
| **3.1.2** | **Verify that** extension installation is restricted to an approved allowlist, or that a defined blocklist plus permission-based restrictions are enforced. | 2 |
| **3.1.3** | **Verify that** extension installation requests follow a documented review-and-approval workflow. | 3 |

---

## V3.2 Review & Risk Assessment

| # | Description | Level |
| :---: | --- | :---: |
| **3.2.1** | **Verify that** a documented process exists for assessing extensions before approval, covering permissions requested, publisher reputation, and data handling. | 2 |
| **3.2.2** | **Verify that** extensions requesting high-risk permissions (e.g., access to all sites, reading browsing data, clipboard, native messaging) receive heightened review. | 2 |
| **3.2.3** | **Verify that** approved extensions are re-assessed on ownership change, permission escalation, or a defined periodic cadence. | 3 |

---

## V3.3 Runtime & Lifecycle Control

| # | Description | Level |
| :---: | --- | :---: |
| **3.3.1** | **Verify that** installed extensions across the fleet are inventoried, including version and permission set. | 2 |
| **3.3.2** | **Verify that** an extension can be force-removed or disabled fleet-wide within a defined SLA when found malicious or compromised. | 2 |
| **3.3.3** | **Verify that** extension permission changes on update are detected and trigger re-review. | 2 |
| **3.3.4** | **Verify that** extensions are blocked or restricted from running on designated sensitive sites (e.g., admin consoles, banking, healthcare records). | 3 |

---

## V3.4 Enterprise-Developed Extensions

| # | Description | Level |
| :---: | --- | :---: |
| **3.4.1** | **Verify that** internally developed extensions follow secure development practices and are distributed through managed channels only. | 2 |
| **3.4.2** | **Verify that** internally developed extensions undergo security review equivalent to other internal software before deployment. | 3 |
