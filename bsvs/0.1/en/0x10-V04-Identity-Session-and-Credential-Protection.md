# V4: Identity, Session & Credential Protection

## Control Objective

This chapter addresses the controls for protecting authentication, sessions, credentials, and third-party grants within the browser environment.

---

## V4.1 Authentication & Federation

| # | Description | Level |
| :---: | --- | :---: |
| **4.1.1** | **Verify that** access to sensitive corporate applications through the browser requires SSO with MFA. | 1 |
| **4.1.2** | **Verify that** phishing-resistant authentication (e.g., FIDO2/WebAuthn, passkeys) is deployed for high-value accounts and applications. | 2 |
| **4.1.3** | **Verify that** authentication policies evaluate device and browser posture (managed state, browser version) before granting access to sensitive applications. | 3 |

---

## V4.2 Session & Token Protection

| # | Description | Level |
| :---: | --- | :---: |
| **4.2.1** | **Verify that** session anomalies (token reuse from new device/location/IP) for critical applications are detected and can trigger revocation. | 2 |
| **4.2.2** | **Verify that** session lifetimes and re-authentication requirements for sensitive applications are risk-appropriate and enforced. | 2 |
| **4.2.3** | **Verify that** session credentials are bound to the device where supported (e.g., device-bound session credentials, token binding mechanisms), so exfiltrated cookies cannot be replayed elsewhere. | 3 |
| **4.2.4** | **Verify that** administrative and privileged web sessions are conducted from hardened or isolated browser environments. | 3 |

---

## V4.3 Credential Storage & Password Management

| # | Description | Level |
| :---: | --- | :---: |
| **4.3.1** | **Verify that** an approved password manager is available to users, and policy defines whether the browser's built-in manager is sanctioned. | 1 |
| **4.3.2** | **Verify that** browser-stored credentials are protected by OS-level encryption tied to the user account, and that saving corporate credentials into unsanctioned stores is restricted. | 2 |
| **4.3.3** | **Verify that** credential autofill is restricted to exact-match, legitimate origins (mitigating phishing-site autofill). | 2 |
| **4.3.4** | **Verify that** corporate credentials cannot be entered into known-phishing or non-sanctioned lookalike sites (e.g., password reuse and paste detection for the corporate identity). | 3 |

---

## V4.4 OAuth & Third-Party Grants

| # | Description | Level |
| :---: | --- | :---: |
| **4.4.1** | **Verify that** user consent to third-party OAuth applications for corporate identities is restricted or subject to admin approval. | 2 |
| **4.4.2** | **Verify that** granted OAuth applications and scopes are periodically reviewed and stale or high-risk grants revoked. | 2 |
