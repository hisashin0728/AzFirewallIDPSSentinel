# AzFirewallIDPSSentinel
This repository provides Analytics Rule of Microsoft Sentinel for Azure Firewall IDPS Alert.

# Screenshot of Microsoft Sentinel Incident
When you imported exported json file from Sentinel, Analytics Rule will trigger Azure Firewall IDPS alert to Microsoft Sentinel.  
<img width="1088" alt="image" src="https://github.com/hisashin0728/AzFirewallIDPSSentinel/assets/55295601/625b1b0b-9fcf-45ae-94af-bdef6f46a87e">

# Preparations
You should enable Structured format of Diagnostic setting from Azure Firewall.
<img width="655" alt="image" src="https://github.com/hisashin0728/AzFirewallIDPSSentinel/assets/55295601/eb1a613a-7d93-4124-9b01-8c3f38551904">

# Analytics Rule
Created three analytics rules for Azure Firewall IDPS Alert

| Severity | Rule Title | Description |
| ---- | ---- | ---- |
| High | Detect High Severity from IDS Event of Azure Firewall | Detected High Severity Non-blocked alert event from Azure Firewall IDPS.|
| Medium | Detect Alert Event from IDS Events of Azure Firewall | Detected Non-blocked alert event from Azure Firewall IDPS.|
| Low | Detect Blocked Event from IPS Events of Azure Firewall | Detected Blocked Event from Azure Firewall IDPS.|
