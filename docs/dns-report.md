# Part 1 — DNS UDP vs TCP (Experiments 1–5)

**Owner:** Treé (Thiên Trí)  
**Status:** Not started  
**Capture target:** `captures/dns_udp_tcp.pcapng`

## Environment
- Windows version:
- Wireshark version / interface:
- DNS client and exact commands:
- WSL/Linux environment, if required:
- Local IP, DNS server IP:
- Capture time and notes:

## Experiment 1 — UDP DNS
### Procedure and complete command log
### Packet numbers and evidence
### DNS fields, name encoding, records/TTL, timing, length
### Explanation

## Experiment 2 — Forced DNS over TCP
### Procedure and command log
### TCP SYN/SYN-ACK/ACK, DNS length prefix, closure
### Packet numbers and evidence
### Explanation

## Experiment 3 — UDP vs TCP overhead
| Metric | UDP | TCP | How measured |
| --- | --- | --- | --- |
| Packets | TBD | TBD | |
| Bytes on wire | TBD | TBD | |
| Header overhead | TBD | TBD | |
| Response/total time | TBD | TBD | |

## Experiment 4 — Root-server referral, truncation and automatic TCP retry
### Procedure and full log
### Referral / truncated response / retry evidence
### Forced TCP vs automatic retry
### Explanation

## Experiment 5 — Authority and Additional records; security
### NS/A/AAAA/glue packet evidence
### UDP 512-byte limit and truncation
### Plaintext DNS versus DoT/DoH

## Self-review checklist
- [ ] Full command session/log attached
- [ ] Packet numbers correspond to actual PCAPNG
- [ ] All evidence screenshots are annotated
- [ ] No unsupported TCP fallback claim
- [ ] All five experiments answered
