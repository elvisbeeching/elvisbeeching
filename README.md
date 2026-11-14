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

## Skills demonstrated

- **Network log analysis** — Matched source and destination addresses and ports across firewall and proxy logs. Compared timestamps to determine which events belonged to the same connection. [Phishing investigation](https://elvis-beeching.elvisbeeching.chatgpt.site/#phishing-investigation)
- **Identity alert validation** — Used historical sign-in records to test an Entra ID rule against the account’s normal activity and identify a timezone assumption that affects the verdict. [Guest sign-in review](https://elvis-beeching.elvisbeeching.chatgpt.site/#guest-signin-case)
- **Endpoint response** — Used Defender AV quarantine details and the reported absence of recurrence to assess severity and document the closure decision in ServiceNow. [PUA investigation](https://elvis-beeching.elvisbeeching.chatgpt.site/#pua-investigation)
- **Scoping and escalation** — Compared reported scan activity with the approved scan window and identified the scanner job history and firewall/IDS logs needed to determine authorization. [Port sweep triage](https://elvis-beeching.elvisbeeching.chatgpt.site/#port-sweep-case)

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
