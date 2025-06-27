# Cybersecurity-day-4
---
## Objective:
  - To Configure and test basic firewall rules to allow or block traffic.

## Using Windows Firewall

✅ Step-by-Step (Block Port 23 - Telnet)

1. Open Windows Defender Firewall with Advanced Security

Press Windows + S → Search: “Windows Defender Firewall with Advanced Security”

Open it



2. Click “Inbound Rules” → “New Rule…”


3. In the wizard:

Rule Type: Port

Protocol: TCP

Specific local port: 23

Action: Block the connection

Profile: All

Name: Block Telnet (Port 23)



4. Apply the Rule


5. ✅ Test by trying to use:

telnet localhost 23

(Telnet should fail if blocked)


6. 🔓 Remove the Rule

Go back to “Inbound Rules”

Right-click your Block Telnet rule → Delete
