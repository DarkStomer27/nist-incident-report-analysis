# ICMP Flood DoS Incident Report Analysis Using the NIST Cybersecurity Framework

This repository contains my security incident report analysis using the NIST Cybersecurity Framework (CSF). The activity focuses on analysing a denial-of-service (DoS) attack, identifying security risks, and proposing measures to improve the organisation's network security.

## Scenario

The following scenario, provided as part of the course activity, serves as the basis for this security incident report analysis.

A multimedia company that provides web design, graphic design, and social media marketing services to small businesses experienced a denial-of-service (DoS) attack that disrupted its internal network for approximately two hours.

During the incident, the company's network services became unresponsive due to a flood of incoming ICMP packets, preventing normal internal network traffic from accessing network resources. The incident management team responded by blocking incoming ICMP packets, temporarily disabling non-critical network services, and restoring critical services.

Following the incident, the cybersecurity team investigated the event and discovered that a malicious actor had exploited an unconfigured firewall to flood the company's network with ICMP packets.

To address the security issue, the network security team implemented the following measures:

- A firewall rule to limit the rate of incoming ICMP packets.
- Source IP address verification to check for spoofed IP addresses.
- Network monitoring software to detect abnormal traffic patterns.
- An IDS/IPS system to filter suspicious ICMP traffic.

## Analysis

The incident is analysed using the five functions of the NIST Cybersecurity Framework:

1. **Identify:** Identify the affected assets, security vulnerabilities, and potential risks.
2. **Protect:** Establish security measures to prevent or reduce the impact of future incidents.
3. **Detect:** Identify suspicious activities and improve network monitoring capabilities.
4. **Respond:** Develop procedures to contain, investigate, and manage security incidents.
5. **Recover:** Restore affected systems and network services to normal operation.

## Learning Objective

This activity demonstrates my understanding of cybersecurity incident analysis and how the NIST Cybersecurity Framework can be applied to identify security risks, evaluate incidents, and develop appropriate security improvements.
