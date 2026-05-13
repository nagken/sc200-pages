# SC-200 - Microsoft Security Operations Analyst - Visual Study Guide

> Concept-only study aid. No exam questions reproduced. Source PDF (if any) stays local + gitignored.

**Skills outline:** https://learn.microsoft.com/en-us/credentials/certifications/exams/sc-200/

## Master mind map

```mermaid
mindmap
  root((SC-200))
    Manage Security Operations Environment
      Configure settings in Microsoft Defender XDR portal security.micros...
      Manage role-based access control RBAC, Unified RBAC, and assigned r...
      Configure data retention, alert tuning, and notification preferences
      Connect Defender XDR to Microsoft Sentinel unified portal
      Manage settings for the Microsoft Sentinel workspace workspace, ret...
    Configure Protections and Detections
      Configure protections in Defender XDR workloads DfE, DfO, DfI, DfCA
      Configure detections in Sentinel scheduled / NRT / ML / Microsoft a...
      Configure attack-disruption settings
      Tune false positives, manage suppression, configure indicators of c...
      Configure custom detection rules in Defender XDR
    Manage Incident Response
      Investigate and respond to incidents in Defender XDR + Sentinel
      Investigate and respond to alerts in Defender for Endpoint, Office ...
      Manage automated investigation and response AIR settings
      Author SOAR playbooks Logic Apps and automation rules
      Configure Microsoft Defender for Cloud incidents and entity recomme...
    Perform Threat Hunting
      Hunt in Microsoft Defender XDR using KQL on advanced hunting tables
      Hunt in Microsoft Sentinel using KQL across connected sources
      Use bookmarks, livestream, and notebooks Jupyter for ongoing hunts
      Manage threat indicators and integrate threat intelligence feeds
      Use UEBA insights and entity behavior pages
```

## Domain map

```mermaid
flowchart LR
    Master["SC-200 Master Index"]
    D01["Manage Security Operations Environment"]
    Master --> D01
    D02["Configure Protections and Detections"]
    Master --> D02
    D03["Manage Incident Response"]
    Master --> D03
    D04["Perform Threat Hunting"]
    Master --> D04
```

## Domain weights

```mermaid
pie showData
    title SC-200 domain weights
    "Manage Security Operations Environment" : 25
    "Configure Protections and Detections" : 20
    "Manage Incident Response" : 35
    "Perform Threat Hunting" : 20
```

> Click a slice / legend label to jump to that chapter.

## Recommended study order

```mermaid
gantt
    title Suggested study plan
    dateFormat X
    axisFormat Day %d
    section Plan
    Manage Security Operations Environment :t1, 0, 2d
    Configure Protections and Detections :t2, after t1, 2d
    Manage Incident Response :t3, after t2, 2d
    Perform Threat Hunting :t4, after t3, 2d
```

---

**Next:** open [01-secops-environment.md](01-secops-environment.md)

<!-- TODO: fill remaining sections via Copilot chat. Target structure mirrors c:\az305\study-guide\00-MASTER-INDEX.md. -->
