# Honeypot-Deployment-Active-Deception-Lab
: Deploy an active honeypot using Pentbox on Kali Linux to simulate a high-value target and capture attacker intelligence.
**Objective:** Deploy an active honeypot using Pentbox on Kali Linux to simulate a high-value target and capture attacker intelligence.

**What I built:**
- Configured Pentbox honeypot listener on Port 80 (HTTP)
- Captured source IP addresses, User-Agent strings, and timestamps of intrusion attempts
- Triggered real-time visual alerts on unauthorized connection attempts
- Analyzed attacker fingerprints from HTTP request headers

**Sample captured intrusion data:**

```
HONEYPOT ACTIVATED ON PORT 80 (2026-02-24 12:49:46 +0530)

INTRUSION ATTEMPT DETECTED! from 10.0.2.15:53480 (2026-02-24 12:50:39 +0530)

GET / HTTP/1.1
Host: 10.0.2.15
User-Agent: Mozilla/5.0 (X11; Linux x86_64; rv:140.0) Gecko/20100101 Firefox/140.0
Accept-Language: en-US,en;q=0.5
Connection: keep-alive
```

**Intelligence gathered:**
- Attacker OS fingerprint: Linux x86_64
- Browser: Firefox 140.0
- Connection type: keep-alive (persistent)
- Follow-up request: `/favicon.ico` — indicates browser-based access attempt

**Key learning:**
Honeypots provide proactive threat intelligence by revealing attacker IPs, tooling, and behavior patterns before real production systems are targeted.

**Tools:** Pentbox 1.8, Kali Linux, Port 80 HTTP listener

---

## Skills Demonstrated Across All Projects

| Skill | Projects |
|-------|---------|
| SIEM deployment & tuning | Wazuh, Splunk |
| Log ingestion pipelines | Splunk |
| SPL query development | Splunk |
| Intrusion detection rules | Snort |
| Packet analysis | Wireshark |
| DoS/DDoS analysis | Wireshark, hping3 |
| File integrity monitoring | Wazuh, Python (Sentinel) |
| Active Directory security | Kerberoasting lab |
| Red team techniques | Kerberoasting, Honeypot |
| Blue team forensics | Kerberoasting (Event Logs) |
| MITRE ATT&CK mapping | Wazuh |
| PCI DSS / NIST compliance | Wazuh |
| Deception technology | Honeypot |
| Python scripting | Sentinel FIM |
| Firewall configuration | UFW |

---

## Contact

Open to entry-level SOC Analyst opportunities.  
📧 arjunrajeevepillai@gmail.com  
🔗 [linkedin.com/in/arjunrpillai-soc](https://www.linkedin.com/in/arjunrpillai-soc)
