# Investigation Findings

## Finding 1 — Look-Alike Sender Domain

The sender address was:

`security@paypa1-secure.com`

The domain uses `paypa1`, replacing the letter `l` with the
number `1`.

This is consistent with a look-alike domain and
impersonation indicator.

---

## Finding 2 — Mismatched Reply-To Address

The Reply-To address was:

`support@paypa1-recovery.tk`

The Reply-To domain differs from the sender domain.

---

## Finding 3 — Mismatched Return-Path

The Return-Path was:

`bounce@spam-relay.xyz`

The Return-Path differs from both the sender and Reply-To
domains.

---

## Finding 4 — Email Authentication Findings

PhishTool reported:

- SPF: None
- DKIM: None
- DKIM signatures: 0
- DMARC: None

These authentication findings provide supporting evidence
when correlated with the other indicators identified during
the investigation.

---

## Finding 5 — Suspicious URLs

Four URLs were identified in the email.

The two `paypa1-secure.tk` URLs returned:

`0/91 detections`

The shortened URLs returned:

- `tinyurl.com/verify-account` — `1/95`, Phishing
- `bit.ly/paypal-unlock` — `1/95`, Phishing

The VirusTotal results are recorded as observed during the
investigation and do not independently establish legitimacy
or maliciousness.

---

## Finding 6 — Social Engineering Indicators

The email uses several social-engineering indicators,
including:

- Urgent account-suspension language
- A 24-hour deadline
- Final-notice language
- Requests for password information
- Requests for credit-card information
- Requests for billing information
- Requests for Social Security Number
- A reward incentive

These elements are designed to encourage the recipient to
take immediate action and provide sensitive information.

---

## Finding 7 — No Attachment

No attachment was identified during the PhishTool attachment
check.

Therefore, no attachment-based analysis was performed.

---

## Finding 8 — Transmission Path

PhishTool identified the public IP:

`91.234.56.78`

at Hop 6.

The transmission data also displayed:

`192.168.1.100`

at Hop 7. This is a private/internal IP address and is not
treated as the public originating IP.

---

## Overall Finding

The combined evidence supports classifying the investigated
email as a phishing attempt impersonating PayPal.

The classification is based on the combination of sender
impersonation, mismatched email routing information,
authentication findings, suspicious URLs, observed phishing
detections, and social-engineering indicators.
