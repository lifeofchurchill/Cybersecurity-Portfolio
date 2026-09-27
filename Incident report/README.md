# Network Incident Report — ICMP Flood Attack

## Overview

This activity involved analyzing a network security incident in which a
company's network services became unavailable following a flood of
incoming ICMP packets.

The incident disrupted internal network traffic for approximately two
hours. The incident was analyzed using the NIST Cybersecurity Framework
(CSF).

## Incident

The security event involved an incoming flood of ICMP packets that
disrupted access to network resources.

The incident response team blocked the incoming ICMP traffic, stopped
non-critical network services, and restored critical services.

## NIST Cybersecurity Framework Analysis

### Identify

The incident involved an attacker flooding the organization's network
with ICMP packets, disrupting internal network flow and access to
critical network resources.

### Protect

Security safeguards included:

- A firewall rule to limit incoming ICMP traffic
- An IDS/IPS system to filter abnormal traffic patterns

### Detect

Detection measures included:

- Network monitoring software
- Source IP address verification on the firewall
- Monitoring for abnormal traffic patterns
- Checking for spoofed IP addresses

### Respond

The response plan included:

- Isolating affected systems
- Restoring critical systems and services
- Analyzing network logs for suspicious activity
- Reporting incidents to appropriate stakeholders and authorities when applicable

### Recover

Recovery involved:

1. Blocking the external ICMP flood at the firewall
2. Stopping non-critical network services
3. Restoring critical network services
4. Returning non-critical systems and services to normal operation
   after the attack subsided

## Skills Demonstrated

- Network security analysis
- Incident analysis
- Incident response
- Network monitoring
- Firewall controls
- IDS/IPS concepts
- NIST Cybersecurity Framework
- Security documentation

## Key Takeaway

This activity helped me practice applying the NIST Cybersecurity
Framework to a network security incident and understand how the
Identify, Protect, Detect, Respond, and Recover functions can be used
to structure an organization's security response.
