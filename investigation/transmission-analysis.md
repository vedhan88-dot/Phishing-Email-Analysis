# Transmission Analysis

## Overview

The email transmission path was reviewed using PhishTool to
identify the hosts and IP addresses shown in the message
routing information.

## Transmission Path

### Hop 1

**Received from:**

`origin.paypa1-secure.com`

**Received by:**

`internal.paypa1-secure.com`

### Hop 2

**Received from:**

`internal.paypa1-secure.com`

**Received by:**

`smtp.paypa1-secure.com`

### Hop 3

**Received from:**

`smtp.paypa1-secure.com`

**Received by:**

`mail-gateway.xyz`

### Hop 4

**Received from:**

`mail-gateway.xyz`

**Received by:**

`compromised-server.cn`

### Hop 5

**Received from:**

`compromised-server.cn`

**Received by:**

`unknown-host.ru`

### Hop 6

**Received from:**

`unknown-host.ru (91.234.56.78)`

**Received by:**

`spam-relay.xyz`

### Hop 7

**Received from:**

`mail.spam-relay.xyz (192.168.1.100)`

**Received by:**

`mx.example.com`

## IP Address Analysis

The public IP identified in the transmission path is:

`91.234.56.78`

The address:

`192.168.1.100`

is a private/internal IP address shown at Hop 7 and is not
treated as the public originating IP.

## Transmission Assessment

The transmission path contains multiple hosts and domains that
differ from the apparent PayPal identity used by the email.

The hostname `compromised-server.cn` is documented exactly as
displayed by PhishTool. The hostname itself is not treated as
independent proof that the server was actually compromised.

The transmission findings provide additional context for the
overall phishing investigation.
