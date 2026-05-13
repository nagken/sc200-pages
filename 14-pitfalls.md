# Common Pitfalls - SC-200

> Frequent confusions, traps, and "gotchas" that cause wrong answers on the exam.

### Two SIEMs running in parallel

Defender XDR is not a SIEM but if you ingest its incidents into Sentinel without unified portal you get duplicates.

### Wrong KQL table

Advanced hunting tables differ slightly between XDR (DeviceX) and Sentinel (Syslog, SecurityEvent). Pick the right one.

### Ignoring archive tier

Storing 7 years in interactive retention costs 10x what archive does.

### Auto-close on critical sev

Never auto-close High/Critical incidents without analyst review.


---

[Master Index](00-MASTER-INDEX.md)
