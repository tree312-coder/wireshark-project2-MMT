# Part 3 — UDP vs ICMP Traceroute (Experiments 10–13)

**Owner:** Nhu Kei  
**Status:** Not started  
**Capture target:** `captures/traceroute.pcapng`

## Environment
- Windows version:
- Wireshark interface:
- WSL/Linux environment or alternative traceroute tool:
- Destination: 8.8.8.8
- Commands and full console outputs:

> Important: Windows `tracert` sends ICMP Echo probes. A separate method is required for the assignment's UDP traceroute. If using WSL2, document the virtual network hop and capture interface.

## Experiment 10 — UDP traceroute probes
### Commands and first six probes: TTL, source/destination ports, length
### Packet numbers, first response, protocol dissection

## Experiment 11 — ICMP Time Exceeded and UDP responses
### ICMP type/code and embedded datagram matching
### RTT and asterisk/nonresponse evidence
### Load balancing and firewall discussion

## Experiment 12 — ICMP Echo traceroute
### Echo request and reply: type/code, identifier, sequence, TTL
### Hop count and Windows tracert comparison

## Experiment 13 — UDP vs ICMP comparison
| Metric | UDP | ICMP |
| --- | --- | --- |
| Hops | TBD | TBD |
| Last response | TBD | TBD |
| Unresponsive hops | TBD | TBD |
| Probe counts | TBD | TBD |
| Completion behavior | TBD | TBD |

### Firewall treatment and destination port 53
### Conclusion

## Self-review checklist
- [ ] Both UDP and ICMP captures present
- [ ] Complete command logs retained
- [ ] All packet numbers correspond to capture
- [ ] Evidence screenshots highlight relevant fields
