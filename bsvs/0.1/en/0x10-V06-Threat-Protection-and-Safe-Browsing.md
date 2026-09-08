# V6: Threat Protection & Safe Browsing

## Control Objective

This chapter addresses protections against malicious sites, phishing, download threats, network/transport security, and browser-specific user awareness.

---

## V6.1 Malicious Site & Phishing Protection

| # | Description | Level |
| :---: | --- | :---: |
| **6.1.1** | **Verify that** reputation-based protection (e.g., Safe Browsing or equivalent) is enabled and enforced fleet-wide. | 1 |
| **6.1.2** | **Verify that** enhanced or real-time URL protection is enabled for the fleet, with privacy implications assessed and documented. | 2 |
| **6.1.3** | **Verify that** newly registered/observed domains and known AitM infrastructure indicators can be blocked at or before the browser. | 2 |
| **6.1.4** | **Verify that** in-browser page analysis or equivalent controls detect credential-harvesting pages impersonating corporate identity providers. | 3 |

---

## V6.2 Download & Content Threats

| # | Description | Level |
| :---: | --- | :---: |
| **6.2.1** | **Verify that** downloaded files are scanned by endpoint protection before execution. | 1 |
| **6.2.2** | **Verify that** high-risk file types and password-protected archives from uncategorized sources are blocked or sandboxed by policy. | 2 |
| **6.2.3** | **Verify that** social-engineering execution patterns delivered via the browser (e.g., copy-run-paste "ClickFix" instructions) are addressed by technical control and user awareness. | 2 |

---

## V6.3 Network & Transport Protections

| # | Description | Level |
| :---: | --- | :---: |
| **6.3.1** | **Verify that** HTTPS is required by default and users are warned or blocked on certificate errors, with error click-through disabled for managed fleets where feasible. | 1 |
| **6.3.2** | **Verify that** DNS-over-HTTPS behavior is explicitly configured to align with enterprise DNS security controls rather than left to browser defaults. | 2 |
| **6.3.3** | **Verify that** TLS inspection, where used, is scoped, documented, and excludes categories where inspection creates unacceptable privacy or legal risk. | 3 |

---

## V6.4 User Awareness (Browser-Specific)

| # | Description | Level |
| :---: | --- | :---: |
| **6.4.1** | **Verify that** security awareness training includes browser-specific threats: consent phishing, fake updates, malicious extensions, MFA-bypass phishing. | 1 |
| **6.4.2** | **Verify that** users have a low-friction way to report suspicious sites/pages encountered in the browser, and reports feed detection processes. | 2 |
