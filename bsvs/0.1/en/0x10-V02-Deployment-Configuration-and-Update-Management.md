# V2: Deployment, Configuration & Update Management

## Control Objective

This chapter addresses the technical controls for deploying, configuring, updating, and hardening browsers across the enterprise fleet.

---

## V2.1 Inventory & Fleet Visibility

| # | Description | Level |
| :---: | --- | :---: |
| **2.1.1** | **Verify that** the organization maintains an inventory of browsers (product and version) in use across managed endpoints. | 1 |
| **2.1.2** | **Verify that** unmanaged or unapproved browsers on managed endpoints can be detected and remediated. | 2 |
| **2.1.3** | **Verify that** browser access to sensitive applications from outside the managed fleet is identified (e.g., via IdP or application logs). | 3 |

---

## V2.2 Centralized Configuration Management

| # | Description | Level |
| :---: | --- | :---: |
| **2.2.1** | **Verify that** browser security settings are enforced centrally (e.g., via management policy) rather than relying on user-controlled defaults. | 1 |
| **2.2.2** | **Verify that** enforced configuration is derived from a documented hardening baseline (e.g., CIS Benchmarks) with deviations recorded. | 2 |
| **2.2.3** | **Verify that** users cannot disable or override security-relevant policies (e.g., Safe Browsing, extension controls, update settings). | 2 |
| **2.2.4** | **Verify that** configuration drift from the approved baseline is detected and alerted. | 3 |

---

## V2.3 Update & Vulnerability Management

| # | Description | Level |
| :---: | --- | :---: |
| **2.3.1** | **Verify that** automatic browser updates are enabled and cannot be disabled by users. | 1 |
| **2.3.2** | **Verify that** browser versions across the fleet reach the latest stable release within a defined SLA, with reporting on laggards. | 2 |
| **2.3.3** | **Verify that** a process exists for emergency deployment of browser patches for actively exploited vulnerabilities (0-days). | 2 |
| **2.3.4** | **Verify that** browser and extension vulnerabilities are included in the organization's vulnerability management program. | 2 |
| **2.3.5** | **Verify that** relaunch/restart is enforced within a defined window after update download so patches take effect. | 3 |

---

## V2.4 Feature & API Surface Reduction

| # | Description | Level |
| :---: | --- | :---: |
| **2.4.1** | **Verify that** unneeded high-risk browser capabilities (e.g., WebUSB, WebSerial, WebBluetooth, remote debugging) are disabled by policy where there is no business need. | 2 |
| **2.4.2** | **Verify that** developer tools and browser flags are restricted on endpoints or for users where there is no business need. | 2 |
| **2.4.3** | **Verify that** legacy or deprecated protocols and features (e.g., insecure TLS versions, deprecated plugin interfaces) are disabled fleet-wide. | 3 |

---

## V2.5 Profiles & Environment Separation

| # | Description | Level |
| :---: | --- | :---: |
| **2.5.1** | **Verify that** corporate browser profiles are separated from personal profiles, with corporate data confined to managed profiles. | 2 |
| **2.5.2** | **Verify that** sync of corporate profile data (passwords, history, tabs) to personal accounts is blocked. | 2 |
| **2.5.3** | **Verify that** high-risk browsing (unknown sites) can be isolated from sessions accessing sensitive applications (e.g., separate profiles, isolation technology). | 3 |
