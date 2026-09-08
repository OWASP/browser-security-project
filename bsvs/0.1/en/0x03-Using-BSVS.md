# Using the BSVS

## Verification Levels

Each BSVS requirement is assigned a verification level (1, 2, or 3) indicating the depth of security assurance:

| Level | Description | When to use |
| :---: | --- | --- |
| **1** | Essential baseline controls that every organization should implement. | All organizations with managed browser fleets. |
| **2** | Standard controls for organizations handling sensitive data or operating in regulated industries. | Most enterprises, organizations processing personal or financial data. |
| **3** | Advanced controls for high-assurance environments requiring defense against sophisticated threats. | Critical infrastructure, financial services, government, high-value targets. |

Organizations should select a target level based on their risk profile. Most enterprises should aim for at least Level 2.

## How to use BSVS

- **During policy development.** Use requirements as a foundation for browser security policies.
- **During deployment.** Validate browser configurations against BSVS requirements.
- **During security assessments.** Use as a verification framework for audits and reviews.
- **For procurement.** Reference specific requirements when evaluating enterprise browsers and security tools.
- **For maturity measurement.** Track compliance across levels to measure and communicate browser security posture over time.

## Requirement Identifiers

Each requirement has an identifier in the format `BSVS-V.S.R`, where V is the chapter, S is the section, and R is the requirement number. For example, `BSVS-3.2.1` refers to Chapter 3 (Extension & Plugin Management), Section 2 (Review & Risk Assessment), Requirement 1.

When referencing requirements in external documents, include the version: `BSVS-v0.1-3.2.1`.
