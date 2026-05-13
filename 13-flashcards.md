# Flashcards - SC-200

> Click any card to reveal the answer. Use the Domain pager bottom-right to switch between exam areas.

<section class="fc-section" data-fc-title="Manage Security Operations Environment">
<h2>1 - Manage Security Operations Environment</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">Where do you administer Defender XDR?</div><div class="fc-a">security.microsoft.com (the Microsoft Defender portal) which now also hosts Sentinel.</div></div>

<div class="flashcard"><div class="fc-q">What is Unified RBAC?</div><div class="fc-a">A single role-based access model spanning Defender XDR workloads + Sentinel.</div></div>

<div class="flashcard"><div class="fc-q">How do you cut Sentinel ingestion cost predictably?</div><div class="fc-a">Buy a commitment tier (per GB/day) and route low-value chatty data to Basic/Auxiliary logs.</div></div>

<div class="flashcard"><div class="fc-q">Difference between interactive and archive retention?</div><div class="fc-a">Interactive = queryable directly (more expensive). Archive = restored on demand (up to 12 years).</div></div>

<div class="flashcard"><div class="fc-q">How do you sync Defender XDR and Sentinel incidents?</div><div class="fc-a">Enable the Defender XDR data connector with bi-directional sync.</div></div>

</div>
</section>
<section class="fc-section" data-fc-title="Configure Protections and Detections">
<h2>2 - Configure Protections and Detections</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">Five Sentinel analytics rule types?</div><div class="fc-a">Scheduled, Near-real-time (NRT), Microsoft Security, Anomaly (ML), Fusion.</div></div>

<div class="flashcard"><div class="fc-q">Where do you write a detection across Defender XDR tables?</div><div class="fc-a">Defender XDR -> Hunting -> Custom detection rules (KQL).</div></div>

<div class="flashcard"><div class="fc-q">What is Attack Disruption?</div><div class="fc-a">Defender XDR feature that auto-contains compromised users/devices during an in-progress attack.</div></div>

<div class="flashcard"><div class="fc-q">How do you push an IOC to all endpoints?</div><div class="fc-a">Defender XDR -> Settings -> Endpoints -> Indicators (or Sentinel ThreatIntelligenceIndicator).</div></div>

<div class="flashcard"><div class="fc-q">Best fix for noisy rule?</div><div class="fc-a">Tune the rule (filters, entity mappings) or add a suppression rule - do not disable.</div></div>

</div>
</section>
<section class="fc-section" data-fc-title="Manage Incident Response">
<h2>3 - Manage Incident Response</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">Where is the unified incident view?</div><div class="fc-a">Microsoft Defender portal (security.microsoft.com), incidents tab.</div></div>

<div class="flashcard"><div class="fc-q">What is AIR?</div><div class="fc-a">Automated Investigation and Response - native to DfE / DfO / DfCA - investigates and remediates without analyst input.</div></div>

<div class="flashcard"><div class="fc-q">Difference between automation rule and playbook?</div><div class="fc-a">Automation rule = conditional trigger inside Sentinel. Playbook = the Logic App that runs.</div></div>

<div class="flashcard"><div class="fc-q">How do you enrich an incident with whois?</div><div class="fc-a">Playbook with HTTP action -> whois API -> add comment to incident.</div></div>

<div class="flashcard"><div class="fc-q">What is an attack story?</div><div class="fc-a">Defender XDR feature stitching together related alerts + entities into a single timeline.</div></div>

</div>
</section>
<section class="fc-section" data-fc-title="Perform Threat Hunting">
<h2>4 - Perform Threat Hunting</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">What language is hunting in?</div><div class="fc-a">KQL (Kusto Query Language).</div></div>

<div class="flashcard"><div class="fc-q">Where do you run advanced hunting in Defender XDR?</div><div class="fc-a">security.microsoft.com -> Hunting -> Advanced hunting.</div></div>

<div class="flashcard"><div class="fc-q">What is a livestream in Sentinel?</div><div class="fc-a">An always-on hunting query that streams new matches in real time.</div></div>

<div class="flashcard"><div class="fc-q">What is MSTICpy?</div><div class="fc-a">Microsoft Threat Intelligence Center Python library for Jupyter notebooks.</div></div>

<div class="flashcard"><div class="fc-q">How do you save investigative state for follow-up?</div><div class="fc-a">Bookmark - captures the query result + context.</div></div>

</div>
</section>

---

[Master Index](00-MASTER-INDEX.md)
