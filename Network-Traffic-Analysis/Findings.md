## TCP and TLS Analysis

A complete TCP three-way handshake was observed:

1. SYN
2. SYN-ACK
3. ACK

Following the TCP connection establishment, a TLS handshake occurred.

Observed TLS Events:

- Client Hello
- Server Hello
- Certificate Exchange
- Key Exchange
- Encrypted Handshake

Observed SNI:

v20.events.data.microsoft.com

Observation:

The connection successfully transitioned from TCP establishment to encrypted TLS communication over port 443.
