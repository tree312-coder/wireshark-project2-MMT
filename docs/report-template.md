# Final report checklist and template

> This is a *working* template. The submitted artifact must be a PDF named according to all three student IDs.

## Cover page
- Course / project name / term
- Group members and student IDs
- Date / environment

## Methodology
- Wireshark version, host OS, capture interface
- Windows tools, WSL version if used
- Capture and display filters used
- Limitations and experimental conditions

## Part 1 — DNS (Experiments 1–5)
Include answers, logs, tables, annotated screenshots and packet references from `dns-report.md`.

## Part 2 — SMTP (Experiments 6–9)
Include answers, a command/reply table, sequence/ACK/retransmission analysis, annotated screenshots and packet references from `smtp-report.md`.

## Part 3 — Traceroute (Experiments 10–13)
Include both command logs, UDP/ICMP packet analysis, side-by-side comparisons, annotated screenshots and packet references from `traceroute-report.md`.

## Findings and limitations
Explain any missing or environment-dependent behavior; do not fabricate outputs or packet evidence.

## Final QA
- [ ] 13 experiments answered
- [ ] Every claim cross-checked with capture
- [ ] Packet numbering still matches original captured files
- [ ] Screenshots have visible highlighted/circled fields
- [ ] UDP and ICMP traceroute commands / logs saved
- [ ] DNS TCP fallback supported by evidence or limitations acknowledged
- [ ] Captures open successfully
- [ ] ZIP matches exact project structure
- [ ] SMTP instructor-supplied capture excluded from ZIP
- [ ] Final upload completed before 05/12/2026 at 21:00
