# wazuh-soc-bruteforce-detection
Project Overview

Simulated SSH brute-force attack and implemented detection & automated containment using Wazuh SIEM.

🔹 Lab Architecture

Wazuh Manager (SIEM)

Ubuntu Victim (SSH server)

Attacker (Hydra simulation)

🔹 Attack Simulation
  
  SSH brute-force using Hydra

  Multiple failed login attempts generated

🔹 Detection

  Wazuh rule ID 5716 triggered

  Custom rule tuning to increase severity

Real-time alert monitoring in dashboard

🔹 Automated Response

Implemented Wazuh Active Response

Automatically blocked attacker IP using firewall-drop

Verified containment effectiveness

🔹 Hardening & Mitigation

Disabled root SSH login

Disabled password authentication

Configured Fail2Ban

Restricted SSH via firewall

🔹 Skills Demonstrated

SIEM monitoring

Log analysis

Rule customization

Incident containment

Linux hardening

Network security fundamentals
