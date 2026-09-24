# Phishing Email Analysis

## PayPal-Themed Phishing Email Investigation

### Objective

This project demonstrates a practical phishing email investigation from a SOC Analyst perspective.

The investigation focuses on analyzing a suspicious email, identifying Indicators of Compromise (IOCs), reviewing email headers and authentication, analyzing URLs and network information, mapping findings to MITRE ATT&CK, and documenting the final assessment.

---

## Email Summary

| Field | Details |
|---|---|
| Subject | URGENT: Your PayPal Account Has Been Suspended |
| From | security@paypa1-secure.com |
| Reply-To | support@paypa1-recovery.tk |
| Return-Path | bounce@spam-relay.xyz |
| Originating IP | 91.234.56.78 |
| Attachment | None identified |

---

## Investigation Tools

- PhishTool
- VirusTotal
- Email Header Analysis
- URL Analysis
- MITRE ATT&CK
- GitHub

---

## Investigation Workflow

1. Collect the suspicious email
2. Analyze email headers
3. Identify sender and Reply-To inconsistencies
4. Check SPF, DKIM and DMARC
5. Identify the originating IP
6. Analyze suspicious URLs
7. Review the email transmission path
8. Identify Indicators of Compromise
9. Map relevant activity to MITRE ATT&CK
10. Determine the final assessment
11. Document recommendations
12. Close the investigation

---

## Key Findings

- The sender uses the look-alike domain `paypa1-secure.com`.
- The sender, Reply-To and Return-Path domains are inconsistent.
- SPF, DKIM and DMARC authentication results were not identified.
- Multiple suspicious URLs were present.
- TinyURL and Bitly indicators had observed phishing detections during the analysis.
- The email used urgency and account-suspension messaging.
- The email requested sensitive information.
- No attachment was identified.

---

## Indicators of Compromise

### Email Addresses

```text
security@paypa1-secure.com
support@paypa1-recovery.tk
bounce@spam-relay.xyz
