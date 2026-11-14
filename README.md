# Elvis Beeching

**Cybersecurity & Network Security** · Dallas–Fort Worth, TX

I have a master’s degree in cybersecurity from EC-Council University and hands-on training in SOC alert triage, log correlation, incident documentation, and Cisco networking. I’m pursuing entry-level SOC and network engineering roles.

[Cybersecurity portfolio](https://elvis-beeching.elvisbeeching.chatgpt.site) · [LinkedIn](https://www.linkedin.com/in/elvisbeeching) · [Credly](https://www.credly.com/users/elvisbeeching)

## Featured SOC investigations

These cases come from simulated training environments. The linked write-ups include investigation notes and supporting screenshots.

| Investigation | What I checked and documented |
| --- | --- |
| [Suspected phishing](https://elvis-beeching.elvisbeeching.chatgpt.site/#phishing-investigation) | Correlated firewall and proxy records by connection details and timing. The email appeared later in the timeline, so its connection to the traffic remained unverified. |
| [PUA detection and quarantine](https://elvis-beeching.elvisbeeching.chatgpt.site/#pua-investigation) | Reviewed the Defender AV quarantine evidence, assessed the detection as a low-severity true positive, and documented remediation in ServiceNow. |
| [Guest sign-in baseline review](https://elvis-beeching.elvisbeeching.chatgpt.site/#guest-signin-case) | Compared an Entra ID alert with previous sign-ins from the same IP and device. Assessed the first-time condition as a false positive assuming a UTC rule window, and recommended validating the rule settings. |
| [Out-of-window internal port sweep](https://elvis-beeching.elvisbeeching.chatgpt.site/#port-sweep-case) | Triaged a reported scan affecting 160 internal hosts. Documented missing evidence and requested senior analyst review in ServiceNow. |

## Planned networking labs

- **Enterprise headquarters and branch network** — VLANs, inter-VLAN routing, OSPF, DHCP, NAT, ACLs, and secure management.
- **Campus high availability** — HSRP, Rapid PVST+, and EtherChannel across a redundant campus. Measure downtime after each core switch failure against a target of under three seconds.
- **Secure network segmentation** — Validate VLAN boundaries, perimeter controls, and syslog visibility.
- **Network troubleshooting case studies** — Document symptoms, diagnostics, root causes, and verification.
- **Network traffic analysis** — Use Wireshark captures to explain protocol behavior and investigate connectivity.
- **Dual-ISP edge with eBGP** — Verify primary and backup paths, failover, and recovery.
- **Automated change verification and rollback** — Use Python to validate a change across three routers and verify recovery after rollback.

## Technical skills

- **Security operations** — SIEM monitoring, alert triage, log correlation, incident documentation, and MITRE ATT&CK. Microsoft Sentinel, Splunk, Microsoft Defender AV, Entra ID, ServiceNow, and LetsDefend.
- **Networking** — Cisco IOS, Packet Tracer, Wireshark, TCP/IP, VLANs, STP, OSPF, EIGRP, ACLs, NAT, DHCP, and IPv6.
- **Scripting and systems** — Python, PowerShell, Linux, SQL, and Git.

## Applied training

- **MyFirstHack** — Simulated SOC internship focused on alert triage, ServiceNow documentation, and escalation.
- **NexGenT** — Enterprise network simulation and Cisco configuration and troubleshooting practice.

## Education and certifications

- **M.S. in Cybersecurity**, EC-Council University
- **CompTIA** — Security+, CySA+, Network+
- **EC-Council** — CEH, CHFI, CSA, CND
