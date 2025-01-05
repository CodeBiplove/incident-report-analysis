# Incident Report Analysis

## Summary
The company experienced a **distributed denial of service (DDoS)** attack that disrupted all network services. The disruption was caused by a flood of incoming ICMP packets, rendering internal network resources inaccessible. The cybersecurity team mitigated the attack by blocking the incoming ICMP traffic and stopping all non-critical services to restore critical operations.

---

## Identify
A malicious actor targeted the organization with an **ICMP flood attack**, impacting the entire internal network. All critical network resources required immediate attention to secure and restore functionality.

---

## Protect
The cybersecurity team implemented the following measures:
1. **Firewall rule**: Limited the rate of incoming ICMP packets.
2. **IDS/IPS system**: Filtered ICMP traffic based on suspicious characteristics.

---

## Detect
1. **Source IP address verification**: Configured on the firewall to identify and block spoofed IP addresses.
2. **Network monitoring software**: Deployed to detect abnormal traffic patterns and unusual activity.

---

## Respond
For future security incidents, the team will:
1. **Isolate affected systems** to minimize disruption.
2. **Restore critical systems and services** as a priority.
3. **Analyze network logs** for suspicious activity.
4. **Report incidents** to upper management and legal authorities, if applicable.

---

## Recover
To recover from an ICMP flood-based DDoS attack:
1. Restore access to **critical network services**.
2. Block external ICMP flood attacks at the **firewall**.
3. Stop non-critical network services to reduce internal network traffic.
4. Gradually restore **non-critical systems and services** after the ICMP flood ceases.

---

## Framework Alignment
This incident analysis aligns with the **NIST Cybersecurity Framework (CSF)**, addressing the following key functions:
- **Identify**
- **Protect**
- **Detect**
- **Respond**
- **Recover**

---

## Purpose
This document demonstrates practical application of cybersecurity principles to handle network security incidents effectively and is intended to showcase my expertise in managing such scenarios.
