# Microsoft 365 outage analysis | November 12–13, 2026

[Back to portfolio](../README.md)

**Independent incident analysis based on public reporting.** The timeline records when updates were published. The triage and communications below are a proposed enterprise response.

## Timeline and impact

| Time (CST) | What was reported |
| --- | --- |
| Nov. 12, 12:05 p.m. | An IT status bulletin relayed Microsoft’s investigation of connectivity errors on part of Exchange Online. Outlook on the web was among the potentially affected access methods. |
| Nov. 12, 12:50 p.m. | The reported scope expanded from North America to possible Microsoft 365 connectivity and sign-in issues in any region. |
| Nov. 12, 1:28 p.m. | The bulletin named Outlook, Teams, SharePoint, OneDrive, and Copilot. Reported symptoms included intermittent access and degraded performance. |
| Nov. 13, 6:08 a.m. | The bulletin reported improved mailbox access and email processing. Queues were still clearing and intermittent issues could persist. |
| Nov. 13, 12:06 p.m. | The bulletin moved to monitoring and reported broad recovery across services. |

Source for timestamps: [University of Nebraska IT status updates](https://ywxxp3c0681s.statuspage.io/).

**Business impact.** Outlook users reported trouble loading inboxes and sending or receiving messages. Teams disruptions affected collaboration and could interfere with IT incident coordination. Microsoft attributed the outage to a technical issue during an upgrade following a network change and reported no indication of malicious activity. Public updates did not establish the exact failure mechanism or recovery time for each organization. [Associated Press reporting](https://apnews.com/article/d92547a821930290db2964388016979a)

## How I would triage it

1. **Scope the symptoms.** Record the time, location, service, client, and error for representative tickets. Test Outlook on the web and the desktop client from two approved network paths. Check mail access and delivery separately.
2. **Compare with provider and internal evidence.** Check the Microsoft 365 admin center’s Service health dashboard for tenant impact. Compare the affected services and times with internal DNS, proxy and Entra sign-in telemetry. A failure across locations and services that matches the provider advisory supports a provider incident. Failures concentrated on one office network or a specific sign-in policy warrant a separate internal investigation.
3. **Validate recovery.** Test mailbox access and send timestamped messages to confirm delivery in both directions. Check Teams sign-in and messaging. Track residual delays and clear the local incident after representative checks pass and the ticket backlog stabilizes.

## Sample internal update

> **November 12, 2:00 p.m. CST** — Microsoft is investigating a service disruption affecting Outlook and Teams. Some users may have trouble signing in, opening mailboxes, or sending messages. IT is checking which users and locations are affected. The restoration time is unknown. Use the company’s approved phone channel for urgent coordination. We’ll post another update by 3:00 p.m. CST on the IT status page, or sooner if impact changes.
