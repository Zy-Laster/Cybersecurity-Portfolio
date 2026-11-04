# Phishing Email Investigation — Incident Report

**Case ID:** PSS-2026-001  
**Analyst:** Zynia Laster  
**Investigation Type:** Phishing / Credential Harvesting  
**Risk Level:** High  
**Incident Status:** Containment Measures Implemented — Investigation Ongoing  
**Lab Type:** Simulated Cybersecurity Investigation

## 1. Executive Summary

This report documents a simulated phishing investigation involving Peach State Solutions, a fictional organization.

A suspicious email was distributed to 50 employees. The message claimed to originate from the IT Security Department and instructed employees to verify their usernames and passwords within 24 hours to avoid permanent account suspension.

The investigation identified indicators of phishing, including urgency-based social engineering, a suspicious sender domain, and a potentially malicious credential-harvesting URL.

## 2. Initial Email Analysis

The following suspicious indicators were identified:

- The email used urgent language requiring action within 24 hours.
- The message threatened permanent account suspension.
- Employees were instructed to provide their usernames and passwords.
- The sender's domain differed from the company's email domain.

These findings raised concerns about a potential phishing attempt designed to obtain employee login credentials.

## 3. URL Investigation

**Suspicious URL:** `https://peachstate-secure-login.example/verify`

The sender's domain did not match the organization's employee email domain.

A fictional URL reputation report provided the following training results:

- 8 security engines classified the URL as malicious.
- 3 security engines classified the URL as suspicious.
- The domain was reportedly registered three days before the email was sent.
- The simulated webpage contained username and password fields.

Based on the combined evidence, the phishing threat was assessed as high risk.

*Note: These are fictional training results, not findings from a live URL scan.*

## 4. Employee Exposure Assessment

**Marcus:** Reported receiving the phishing email but stated that he did not click the link or submit credentials.

**Jessica:** Clicked the suspicious link. Credential submission was not confirmed, and further device investigation was required.

**David:** Clicked the suspicious link and reported entering his username and password. His credentials were treated as exposed.

**Other 47 employees:** No interaction was confirmed at the time of the investigation. Additional review remained necessary.

David was prioritized because he disclosed his login credentials through the suspected phishing website.

## 5. Incident Response and Containment

The following actions were reported as completed in the simulated incident:

- The suspicious URL was blocked.
- Phishing emails were quarantined.
- David's password was reset.
- David's active sessions were revoked.

These actions helped limit further exposure and reduce the risk of unauthorized access.

## 6. Remaining Investigation

Although containment measures were implemented, the incident was not fully resolved.

The security team still needed to:

- Complete the investigation of Jessica's device and browser activity.
- Determine whether Jessica submitted information or downloaded suspicious content.
- Review authentication logs for unauthorized account activity.
- Investigate whether additional employees interacted with the phishing message.
- Verify that containment measures were effective.

## 7. Security Recommendations

The following recommendations were identified:

- Continue investigating potentially exposed accounts and devices.
- Verify suspicious communications through trusted IT channels.
- Provide phishing awareness exercises to help employees identify suspicious messages.
- Encourage employees to report suspicious emails promptly.
- Maintain appropriate email security and URL-blocking controls.

## 8. Final Assessment

The incident was classified as **contained, with the investigation ongoing**.

Although the suspicious URL was blocked and affected emails were quarantined, additional investigation was necessary to determine whether unauthorized activity occurred.

The simulated investigation demonstrated the importance of identifying phishing indicators, assessing credential exposure, prioritizing containment, and documenting remaining security concerns.

## 9. Skills Practiced

- Phishing Email Analysis
- Social Engineering Identification
- Domain and URL Analysis
- Threat Assessment
- Credential Exposure Investigation
- Incident Response Fundamentals
- Security Documentation

**Disclaimer:** This project is a fictional training exercise completed for educational and portfolio development purposes. All organizations, employees, email addresses, scanner results, and incident details are simulated.
