# V5: Data Protection & Exfiltration Control

## Control Objective

This chapter addresses the controls for preventing unauthorized data exfiltration through the browser, including uploads, downloads, clipboard, shadow SaaS, GenAI leakage, and local data hygiene.

---

## V5.1 Upload, Download & Transfer Control

| # | Description | Level |
| :---: | --- | :---: |
| **5.1.1** | **Verify that** downloads from sensitive corporate applications to unmanaged devices or unsanctioned locations can be controlled. | 2 |
| **5.1.2** | **Verify that** uploads of corporate data to unsanctioned destinations (personal cloud storage, file sharing, webmail) can be detected or blocked, based on data classification. | 2 |
| **5.1.3** | **Verify that** transfers between corporate and personal contexts of the same service (e.g., corporate vs personal tenant of the same SaaS) are distinguished and controlled (tenant restrictions). | 3 |

---

## V5.2 Clipboard, Print & Screen Controls

| # | Description | Level |
| :---: | --- | :---: |
| **5.2.1** | **Verify that** copy/paste of sensitive data from designated corporate applications to unsanctioned destinations can be restricted. | 3 |
| **5.2.2** | **Verify that** printing and screen capture of designated sensitive web applications can be restricted where required by data classification. | 3 |

---

## V5.3 Shadow SaaS & Unsanctioned Applications

| # | Description | Level |
| :---: | --- | :---: |
| **5.3.1** | **Verify that** SaaS applications accessed through the browser are discoverable (shadow IT visibility), and access to unsanctioned categories can be controlled. | 2 |
| **5.3.2** | **Verify that** a process exists to sanction, tolerate, or block newly discovered SaaS applications based on risk. | 2 |

---

## V5.4 GenAI Data Leakage

| # | Description | Level |
| :---: | --- | :---: |
| **5.4.1** | **Verify that** submission of sensitive corporate data to unsanctioned GenAI services via the browser can be detected or blocked, consistent with policy (see V1.2.4). | 2 |
| **5.4.2** | **Verify that** controls distinguish sanctioned enterprise GenAI tenants from consumer versions of the same tools. | 3 |

---

## V5.5 Local Data Hygiene

| # | Description | Level |
| :---: | --- | :---: |
| **5.5.1** | **Verify that** browser-cached corporate data on shared or kiosk endpoints is cleared between users/sessions. | 2 |
| **5.5.2** | **Verify that** corporate data in browser storage (cache, IndexedDB, service workers) on unmanaged devices is minimized or prevented for sensitive applications. | 3 |
