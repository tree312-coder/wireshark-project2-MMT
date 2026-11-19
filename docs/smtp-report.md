# Part 2 — SMTP Analysis (Experiments 6–9)

**Owner:** Mari  
**Status:** Not started  
**Source:** Instructor-supplied `smtp-2026.pcapng` (do **not** submit this original file)

## Environment
- Wireshark version:
- Enable relative TCP sequence numbers:
- Display filters used:

## Experiment 6 — TCP connection and server greeting
### Source/destination IP and ports
### Three-way handshake and MSS
### Server 220 greeting with packet references

## Experiment 7 — TCP sequence numbers and ACKs
### SYN consumes one sequence number
### HELO and 250 response, payload lengths
### Packet references and annotated evidence

## Experiment 8 — SMTP conversation
| Order | Packet no. | Sender | Command / reply | SMTP code | Notes |
| --- | --- | --- | --- | --- | --- |
| | | | | | |

### MAIL FROM / RCPT TO vs From: / To:
### DATA and end-of-message marker
### Reassembled IMF content
### SMTP security and STARTTLS/auth discussion

## Experiment 9 — TCP retransmissions and teardown
### Packet 14 original transmission
### Packets 15 and 17 retransmission/duplicate ACK analysis
### Packet 16 ACK and TCP timestamp echo
### FIN/ACK closure and packet references

## Self-review checklist
- [ ] Every response supported by actual packet evidence
- [ ] Screenshots highlight the relevant fields
- [ ] Command/reply table is complete
- [ ] No instructor capture included in final ZIP
