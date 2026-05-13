# SC-200 Exam Decision Reference

> Compressed decision table covering the entire exam. Use 1 day before the test.

| Scenario | Pick | Why |
|---|---|---|
| Unified portal | security.microsoft.com hosts XDR + Sentinel | One pane |
| Cost driver in Sentinel | Ingestion + retention | Use commitment tiers + Basic logs |
| Detection latency | NRT ~1 min, scheduled 5+ min | Pick by SLA |
| Cross-workload custom detection | Defender XDR custom detection rule | AdvancedHunting KQL |
| Auto-isolate during attack | Attack Disruption + AIR full automation | Built-in |
| Block IOC across estate | Defender XDR Indicators | Push to MDE/DfO |
| Long-term retention | Sentinel archive tier (12 yrs) | Cheap restore |
| Custom enrichment | Sentinel playbook (Logic App) | HTTP + add comment |
| Hypothesis-driven hunt | Bookmark + livestream + notebook | Sentinel toolset |
| Reduce alert noise | Tune entities + suppression rule | Do not disable |

---

[Master Index](00-MASTER-INDEX.md)
