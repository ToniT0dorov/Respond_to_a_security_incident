
<h1>Use the NIST Cybersecurity Framework to respond to a security incident</h1>



<h2>Scenario</h2>
 You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

<b>-A new firewall rule to limit the rate of incoming ICMP packets</b>

<b>-Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets</b>

<b>-Network monitoring software to detect abnormal traffic patterns</b>

<b>-An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics</b>

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. We have broken the analysis into different parts in the template below. You can explore them here:

-<b>Identify</b> security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

-<b>Protect</b> internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

-<b>Detect</b> potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

-<b>Respond</b> to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.  

<br />


<h2>Supporting materials</h2>

- [Applying the NIST CSF ](https://docs.google.com/document/d/15yCDbDCOAcJw-LTz2DeCA7UeLRfvsf176T6MA6ku6ok/template/preview?usp=sharing)
- [Example of an incident report analysis ](https://docs.google.com/document/d/11eTIo1igTRFrY279DG9tHTO3tB3bugSGyknZxsvY5vI/template/preview?usp=sharing&resourcekey=0-97MA-eOwoGtqcfqky0vjmg)



<p><strong><h2>Incident report analysis</h2></strong></p>
<p>&nbsp;</p>
<table width="0">
<tbody>
<tr>
<td width="137">
<p><strong>Summary</strong></p>
</td>
<td width="535">
<p>The company experienced a security event when all network services suddenly stopped responding. The cybersecurity team found the disruption was caused by a distributed denial of services (DDoS) attack through a flood of incoming ICMP packets. The team responded by blocking the attack and stopping all non-critical network services, so that critical network services could be restored.</p>
</td>
</tr>
<tr>
<td width="137">
<p>Identify</p>
</td>
<td width="535">
<p>A malicious actor or actors targeted the company with an ICMP flood attack. The entire internal network was affected. All critical network resources needed to be secured and restored to a functioning state.</p>
</td>
</tr>
<tr>
<td width="137">
<p>Protect</p>
</td>
<td width="535">
<p>The cybersecurity team implemented a new firewall rule to limit the rate of incoming ICMP packets and an IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics.</p>
</td>
</tr>
<tr>
<td width="137">
<p>Detect</p>
</td>
<td width="535">
<p>The cybersecurity team configured source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets and implemented network monitoring software to detect abnormal traffic patterns.</p>
</td>
</tr>
<tr>
<td width="137">
<p>Respond</p>
</td>
<td width="535">
<p>For future security events, the cybersecurity team will isolate affected systems to prevent further disruption to the network. They will attempt to restore any critical systems and services that were disrupted by the event. Then, the team will analyze network logs to check for suspicious and abnormal activity. The team will also report all incidents to upper management and appropriate legal authorities, if applicable.</p>
</td>
</tr>
<tr>
<td width="137">
<p>Recover</p>
</td>
<td width="535">
<p>To recover from a DDoS attack by ICMP flooding, access to network services need to be restored to a normal functioning state. In the future, external ICMP flood attacks can be blocked at the firewall. Then, all non-critical network services should be stopped to reduce internal network traffic. Next, critical network services should be restored first. Finally, once the flood of ICMP packets have timed out, all non-critical network systems and services can be brought back online.</p>
</td>
</tr>
</tbody>
</table>
