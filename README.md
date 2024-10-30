<h1>Incident Report Analysis</h1>


<h2>Description</h2>
As a cybersecurity analyst, I am responsible for developing a comprehensive network security improvement plan following a recent security incident, using the NIST Cybersecurity Framework (CSF) as a guide. Leveraging the CSF’s structured approach, I will analyze the incident to identify vulnerabilities and design a security strategy that enhances our organization’s defenses. This plan will cover essential elements of risk identification, asset protection, threat detection, incident response, and recovery to ensure a resilient and secure network environment.
<br />


<h2>Scenario</h2>

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.
During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 
The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 
To address this security event, the network security team implemented: 
<br />
- A new firewall rule to limit the rate of incoming ICMP packets
-	Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
-	Network monitoring software to detect abnormal traffic patterns
-	An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics


<h2>Summary</h2>
During the attack, the organization’s network was overwhelmed by a flood of ICMP packets, causing network services to stop responding for 2 hours. The incident management team blocked incoming ICMP packets, took non-critical services offline, and restored critical ones. The cybersecurity team discovered that a malicious actor exploited an unconfigured firewall to launch a DDoS attack with ICMP pings.

<h2>Identify</h2>
The incident management team audited the systems, devices, and access policies involved in the attack to pinpoint security gaps. The team found that a malicious actor exploited an unconfigured firewall to launch a DDoS attack with ICMP pings known as an ICMP flood attack. Upon initial review, we only had a disruption in service for about 2 hours. This affected the whole organization because it knocked off connection to our internal network and could not access network resources needing critical network resources to be restored.
<h2>Protect</h2>
The network security team implemented an update to the firewall by adding a new rule to limit the rate of ICMP packets and source IP verification. Additionally, the team is implementing proactive technology such as network monitoring software and install an IDS/IPS system.
<h2>Detect</h2>
To detect new attacks in the future, the team has added network monitoring software to detect and alert the team for any abnormal traffic patterns. The team also installed IDS/IPS systems to filter out ICMP traffic based on suspicious characteristics and alert the team when ICMP traffic is filtered out.
<h2>Respond</h2>
The incident management team promptly blocked incoming ICMP packets, deactivated non-critical services, and restored essential ones. We performed comprehensive firewall maintenance and implemented new rules to limit ICMP packet rates and verify source IPs, mitigating future DDoS attack risks. Upper management has been briefed on the incident and will notify appropriate legal authorities if needed.
<h2>Recover</h2>
The team updating the configuration of the firewall to stop incoming ICMP packets, allowed us to start the process of recovering the servers. Then deactivating non-critical services allows for the team to focus on getting critical services back online. Lastly, once the flood of ICMP packets have ended, non-critical services can be brought online.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
