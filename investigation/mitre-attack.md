# MITRE ATT&CK Mapping

## Overview

The observed behavior in this phishing email was mapped to
relevant MITRE ATT&CK techniques based on the evidence
identified during the investigation.

---

## T1566.002 — Phishing: Spearphishing Link

The investigated email contains multiple URLs associated with
account verification and account unlocking.

The use of links to direct a recipient toward a suspicious
destination is mapped to:

**T1566.002 — Phishing: Spearphishing Link**

### Evidence

- Multiple URLs were present in the email.
- The email used account-verification language.
- The email used account-unlock language.
- Two shortened URLs produced phishing detections in the
  VirusTotal results reviewed.

---

## T1036 — Masquerading

The sender used the domain:

`paypa1-secure.com`

The use of `paypa1` instead of the expected brand spelling is
consistent with a look-alike domain used for impersonation.

This behavior is mapped to:

**T1036 — Masquerading**

### Evidence

- Sender: `security@paypa1-secure.com`
- Look-alike spelling: `paypa1`
- PayPal-themed email content
- PayPal-themed URLs

---

## Attachment-Based Techniques

No attachment was identified during the investigation.

Therefore, attachment-based phishing techniques were not
mapped to this case.

---

## MITRE ATT&CK Summary

| Technique ID | Technique | Evidence |
|---|---|---|
| T1566.002 | Phishing: Spearphishing Link | Multiple suspicious URLs |
| T1036 | Masquerading | Look-alike PayPal domain |

---

## Assessment

The MITRE ATT&CK mapping is based only on behaviors and
evidence observed during this investigation.

No additional techniques are mapped where the available
evidence does not support them.
