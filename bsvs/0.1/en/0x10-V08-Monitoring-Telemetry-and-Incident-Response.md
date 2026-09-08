# V8: Monitoring, Telemetry & Incident Response

## Control Objective

This chapter addresses the controls for collecting browser telemetry, integrating with detection and response workflows, forensic readiness, and continuous improvement of browser security posture.

---

## V8.1 Telemetry Collection

| # | Description | Level |
| :---: | --- | :---: |
| **8.1.1** | **Verify that** security-relevant browser events (extension installs, policy changes, malware/phishing blocks, dangerous downloads) are collected centrally. | 2 |
| **8.1.2** | **Verify that** browser telemetry collection is documented, proportionate, and compliant with applicable employee privacy law and internal policy. | 2 |
| **8.1.3** | **Verify that** telemetry covers data-movement events (uploads, downloads, paste to unsanctioned destinations) for sensitive data classes. | 3 |

---

## V8.2 Detection & Response Integration

| # | Description | Level |
| :---: | --- | :---: |
| **8.2.1** | **Verify that** browser telemetry is integrated with the organization's detection stack (SIEM/XDR) with defined alerting use cases. | 2 |
| **8.2.2** | **Verify that** infostealer indicators (credential store access, mass cookie theft) on endpoints trigger revocation of browser sessions and credentials for affected users. | 2 |
| **8.2.3** | **Verify that** incident response playbooks cover browser-layer scenarios: malicious extension, session token theft, AitM-phished credentials, data exfiltration via browser. | 2 |

---

## V8.3 Forensics & Retention

| # | Description | Level |
| :---: | --- | :---: |
| **8.3.1** | **Verify that** browser artifacts needed for investigation (history, extension state, download records) can be acquired from managed endpoints. | 3 |
| **8.3.2** | **Verify that** retention periods for browser telemetry meet investigation and regulatory needs. | 3 |

---

## V8.4 Metrics & Continuous Improvement

| # | Description | Level |
| :---: | --- | :---: |
| **8.4.1** | **Verify that** browser security posture metrics (patch latency, policy compliance, unapproved extension count, unmanaged browser usage) are reported to security leadership on a defined cadence. | 2 |
| **8.4.2** | **Verify that** findings from browser-related incidents feed back into policy, configuration baselines, and this standard's local implementation. | 3 |
