# Overview
Conducting Post Mortem of the security incident also provides valuable nuggets of information about the weaknesses/vulnerabilities within the current security posture and allows us to improve the posture. 

The NIST CSF and its six core functions provide a framework of planning proactive to applying reactive measures to cybersecurity threats. These functions are essential for ensuring that an organisation has effective security strategies in place. An organisation must have the ability to quickly recover from any damage caused by an incident to minimise their level of risk. 

## This is what I have performed:
 - In this scenario, I conduct a post mortem of a recent Cyber security incident that took place within my organisation using NIST CSF, so that the network security of my organisation can be improved.
 - I document this inside the (IncidentReportAnalysis)[IncidentReportAnalysis.pdf]


## Case Study:
You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organisation recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.
During the attack, your organisation's network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 
The company's cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company's network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company's network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 
1. A new firewall rule to limit the rate of incoming ICMP packets
2. Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
3. Network monitoring software to detect abnormal traffic patterns
4. An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics





