# KBI-IP-LIST

A curated list of known or suspected malicious infrastructure IP addresses gathered from Aero IT's SOC investigations, alerts, and threat-hunting activity.

## Purpose

This repository is intended to provide a practical blocklist of IP addresses that have been associated with suspicious, malicious, or unwanted activity observed by Aero IT.

Examples may include:

- Brute-force attempts
- Credential stuffing
- Phishing infrastructure
- Malware command-and-control activity
- Suspicious VPN, proxy, or hosting-provider traffic
- Repeated probing or scanning activity
- Other SOC-observed indicators of compromise or abuse

## Disclaimer

Aero IT makes no claim that every IP address in this list is definitively malicious. Some entries may represent shared infrastructure, compromised hosts, VPN services, hosting providers, or IP addresses that were suspicious only in a specific context.

Use this list at your own discretion.

Aero IT is not responsible for any disruption, outage, false positive, loss of access, business impact, or other consequence resulting from use of this list.

## Recommended Use

This list may be used for:

- Firewall blocklists
- SIEM correlation
- Threat hunting
- Conditional access review
- IDS/IPS enrichment
- SOC triage
- Security research

Before applying this list in a production environment, review the potential impact and consider testing it in monitor-only or alert-only mode first.

## False Positives

Because IP addresses can change ownership, be reused, or belong to shared hosting providers, false positives are possible.

Do not assume that every IP in this list should be permanently blocked without review.

## Data Sources

The list is based on Aero IT SOC observations, including but not limited to:

- Security alerts
- Firewall logs
- Microsoft 365 / Entra ID sign-in activity
- Endpoint security alerts
- IDS/IPS events
- Email security investigations
- Incident response activity

## Update Frequency

This list may be updated periodically as new suspicious infrastructure is identified or older indicators are removed.

## License / Usage

This list is provided as-is, without warranty of any kind.

You may use, copy, and reference this list for defensive security purposes. Attribution to Aero IT is appreciated but not required unless otherwise stated.

## Important Note

This repository is not a substitute for a full threat intelligence platform, SIEM, EDR, firewall policy, or security monitoring program. It should be treated as one supporting source of security context.
