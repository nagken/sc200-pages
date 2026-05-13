# Hands-On Labs - SC-200

> Free-tier or trial labs you can run end-to-end in 30-60 minutes.

### 1. Tour the Microsoft Defender portal

Sign in to security.microsoft.com on a free M365 dev tenant. Walk Incidents -> Hunting -> Settings -> Permissions (Unified RBAC).

### 2. Build your first scheduled rule

Create a Sentinel scheduled rule that fires when a sign-in to a privileged role originates from a tor exit node.

### 3. Author a SOAR playbook

Create a Logic App with the Sentinel trigger that posts an incident summary to a Teams channel.

### 4. Run advanced hunting

DeviceProcessEvents | where ProcessCommandLine contains 'powershell' and InitiatingProcessFileName == 'winword.exe' | take 50.

### 5. Configure attack disruption

In Defender XDR Settings, ensure attack disruption is enabled for human-operated ransomware + BEC.


---

[Master Index](00-MASTER-INDEX.md)
