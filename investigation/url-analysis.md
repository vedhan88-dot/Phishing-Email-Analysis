# URL Analysis

## Overview

Four URLs were identified in the investigated PayPal-themed phishing email. The URLs were reviewed using PhishTool and VirusTotal. The VirusTotal results documented below represent the results observed during the investigation.

## URL 1 — PayPal Look-Alike Domain

**URL:**

`http://paypa1-secure.tk/verify?token=a8f3k2&redirect=http://bit.ly/3xR9pQ`

**Domain:**

`paypa1-secure.tk`

**VirusTotal Result:**

`0/91 detections`

**Assessment:**

No detection was reported in the VirusTotal scan reviewed. A `0/91` result does not establish that the URL is legitimate. The domain uses the look-alike spelling `paypa1`, which is a suspicious impersonation indicator.

## URL 2 — PayPal Look-Alike Domain

**URL:**

`http://www.paypa1-secure.tk`

**Domain:**

`www.paypa1-secure.tk`

**VirusTotal Result:**

`0/91 detections`

**Assessment:**

No detection was reported in the VirusTotal scan reviewed. A `0/91` result does not establish that the URL is legitimate. The domain uses the look-alike `paypa1` spelling and is associated with the suspicious sender infrastructure observed during the investigation.

## URL 3 — Shortened URL

**URL:**

`http://tinyurl.com/verify-account`

**Domain:**

`tinyurl.com`

**VirusTotal Result:**

`1/95 detections`

**Detection:**

`Phishing`

**Detection Source:**

`SafeToOpen`

**Assessment:**

The reviewed VirusTotal result contained one phishing detection. This result provides supporting evidence for the overall phishing assessment.

## URL 4 — Shortened URL

**URL:**

`http://bit.ly/paypal-unlock`

**Domain:**

`bit.ly`

**VirusTotal Result:**

`1/95 detections`

**Detection:**

`Phishing`

**Detection Source:**

`Phishing Database`

**HTTP Status:**

`200`

An HTTP 200 status indicates that an HTTP response was received. It does not establish that the URL is legitimate.

**Assessment:**

The reviewed VirusTotal result contained one phishing detection. This result provides supporting evidence for the overall phishing assessment.

## URL Summary

| URL | Domain | VirusTotal Result | Observed Detection |
|---|---|---|---|
| URL 1 | paypa1-secure.tk | 0/91 | None reported |
| URL 2 | www.paypa1-secure.tk | 0/91 | None reported |
| URL 3 | tinyurl.com | 1/95 | Phishing |
| URL 4 | bit.ly | 1/95 | Phishing |

## Overall URL Assessment

The investigated email contained multiple URLs associated with account verification or account unlocking.

The investigation identified look-alike PayPal-themed domains, shortened URLs, and phishing detections for the TinyURL and Bitly addresses.

These URL findings provide supporting evidence for classifying the email as a phishing attempt.

VirusTotal results are recorded as observed during the investigation and may change over time.

Suspicious URLs should not be opened directly.
