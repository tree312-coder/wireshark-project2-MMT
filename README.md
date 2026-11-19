# Wireshark Project 2 — Computer Networks (HK1 2026–2027)

**Team:** Treé (Thiên Trí), Mari, Nhu Kei  
**Moodle deadline:** 05 Dec 2026, **21:00 (Vietnam time)**  
**Internal finalization target:** 04 Dec 2026  
**Scope:** DNS over UDP/TCP (36 pts), SMTP (27 pts), Traceroute UDP/ICMP (27 pts), report and submission (10 pts).

## Responsibilities

| Owner | Scope | Experiments | Working branch |
| --- | --- | --- | --- |
| Treé — team lead | DNS + report integration and submission | 1–5 | `part1-dns` |
| Mari | SMTP analysis using instructor-supplied `smtp-2026.pcapng` | 6–9 | `part2-smtp` |
| Nhu Kei | Traceroute UDP vs ICMP | 10–13 | `part3-traceroute` |

## Working folders

- `docs/`: individual analysis drafts, experiment notes and report template.
- `captures/`: **only our own capture files** `dns_udp_tcp.pcapng`, `traceroute.pcapng` (when ready).
- `screenshots/dns/`, `screenshots/smtp/`, `screenshots/traceroute/`: labeled, annotated evidence.
- `submission/`: final report PDF / assembled ZIP when ready.
- `references/`: links to the instructor's reference materials, not copies of unneeded source files.

**Never invent packet numbers, field values, timings, or experiment outcomes.** Every observation must be traceable to a real capture. Highlight/circle the relevant field in each evidence screenshot.

## Team workflow

1. Each member works only on their assigned branch and in their own files/folders.
2. Record commands, Windows/WSL environment, capture interface, packet numbers and observed fields.
3. Commit work and open a PR into `main`; another teammate reviews the evidence and report.
4. After integration, verify all experiment answers and screenshots before preparing the PDF and ZIP.
5. Submit the ZIP in Moodle **before 21:00 on 05 Dec 2026**.

## Internal milestones

| Date | Deliverable |
| --- | --- |
| 21 Nov | Wireshark, Npcap, Windows tooling tested; sample capture working |
| 26 Nov | Experiments and preliminary evidence complete |
| 29 Nov | Individual report sections ready |
| 30 Nov–02 Dec | Cross-review and integration |
| 03–04 Dec | PDF, PCAPNG and ZIP QA; submit early |

## Final submission format (follow the instructor's instructions)

```text
StudentID1_StudentID2_StudentID3.zip
└── StudentID1_StudentID2_StudentID3/
    ├── Package/
    │   ├── dns_udp_tcp.pcapng
    │   └── traceroute.pcapng
    └── StudentID1_StudentID2_StudentID3.pdf
```

Do not include the teacher-supplied SMTP capture in the submission ZIP.

**Official project requirements:** https://drive.google.com/drive/folders/13jVlSxqLlxr_Cc8uPgvA5kZUto2tgMmx  
**Lab references:** https://drive.google.com/drive/folders/1futgxw-8LfdlxYB3nqQI-ln7QU02UcKW  
**Team allocation:** https://docs.google.com/document/d/1gHNYhADzmlr9QqxJFyba9i3AEMfX2VTBOX9ky3jdeYg/edit
