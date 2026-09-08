# OWASP Browser Security Verification Standard (BSVS)

[![CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-blue.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

## What is BSVS?

The **Browser Security Verification Standard (BSVS)** is a community-driven catalogue of testable security requirements for browser security in enterprise environments. It gives security teams, IT administrators, auditors, and CISOs a structured framework to assess, implement, and verify browser security controls.

BSVS is modeled after the [OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/) and [OWASP AISVS](https://github.com/OWASP/AISVS) and follows the same philosophy: every requirement should be **verifiable, testable, and implementable**.

## Project Leaders

- [Jerry Hoff](mailto:jerry@owasp.org)

---

## Latest Version

The latest version is **BSVS 0.1** (draft), which can be found:

| Format | Link |
| --- | --- |
| Markdown (source) | [Browse online](0.1/en) |
| CSV | [BSVS 0.1 CSV](0.1/dist/OWASP-BSVS-v0.1-requirements.csv) |
| XLSX | [BSVS 0.1 XLSX](0.1/dist/OWASP-BSVS-v0.1-requirements.xlsx) |

---

## Verification Levels

Each BSVS requirement is assigned a verification level (1, 2, or 3) indicating the depth of security assurance:

| Level | Description | When to use |
| :---: | --- | --- |
| **1** | Essential baseline controls that every organization should implement. | All organizations with managed browser fleets. |
| **2** | Standard controls for organizations handling sensitive data or operating in regulated industries. | Most enterprises, organizations processing personal or financial data. |
| **3** | Advanced controls for high-assurance environments requiring defense against sophisticated threats. | Critical infrastructure, financial services, government, high-value targets. |

---

## Requirement Chapters

1. [Browser Governance, Ownership & Policy](0.1/en/0x10-V01-Browser-Governance-Ownership-and-Policy.md)
2. [Deployment, Configuration & Update Management](0.1/en/0x10-V02-Deployment-Configuration-and-Update-Management.md)
3. [Extension & Plugin Management](0.1/en/0x10-V03-Extension-and-Plugin-Management.md)
4. [Identity, Session & Credential Protection](0.1/en/0x10-V04-Identity-Session-and-Credential-Protection.md)
5. [Data Protection & Exfiltration Control](0.1/en/0x10-V05-Data-Protection-and-Exfiltration-Control.md)
6. [Threat Protection & Safe Browsing](0.1/en/0x10-V06-Threat-Protection-and-Safe-Browsing.md)
7. [AI & Agentic Browsing](0.1/en/0x10-V07-AI-and-Agentic-Browsing.md)
8. [Monitoring, Telemetry & Incident Response](0.1/en/0x10-V08-Monitoring-Telemetry-and-Incident-Response.md)

---

## How to Reference BSVS Requirements

Each requirement has an identifier in the format `BSVS-V.S.R`, where V is the chapter, S is the section, and R is the requirement number. For example, `BSVS-3.2.1`.

When referencing requirements in external documents, include the version: `BSVS-v0.1-3.2.1`.

---

## Contributing

We welcome contributions from the community. Please [open an issue](https://github.com/OWASP/browser-security-project/issues) to report bugs or suggest improvements. We may ask you to [submit a pull request](https://github.com/OWASP/browser-security-project/pulls) based on the discussion.

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

The entire project content is under the **[Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)** license.
