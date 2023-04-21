<h1>PCI-DSS Gap Analysis</h1>

<h2>Complying with the Payment Card Industry Data Security Standard (PCI DSS) can be complicated and time-consuming, but you can reduce that burden with a PCI DSS gap analysis. It’s usually the first step towards compliance, as it provides a detailed comparison of what an organisation is currently doing against what it should be doing.
</h2>

<br />A PCI gap assessment can help you identify any missing or incomplete cybersecurity infrastructure you’ll need to patch before your next required audit for certification, internal or external.

The following examples are a list of gap finding's and violation findings, requirements that are currently being violated, and an action that will remedy the gap. There also are some recommendations included in this examples for issues that could become an issue if not managed properly.

<br />
PCI DSS Requirement 1.2.3: Install perimeter firewalls between all wireless networks and the cardholder data environment, and configure these firewalls to deny or, if traffic is necessary for business purposes, permit only authorized traffic between the wireless environment and the cardholder data environment.

Network Diagram:
<br />
<img src="https://imgur.com/uckLYrt.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

<br />
Sonicwall Firewall Rules : You don't want unknown traffic in a network that is unauthorized. Any source, any destination should be denied.

1.2.1 Restrict inbound and outbound traffic to that which is necessary for the cardholder data environment, and specifically deny all other traffic.
<br />
<img src="https://imgur.com/DG2zD6b.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

<br />

Results of the internal Qualys scan which makes this a gap.
Vulnerability has not been addressed in 90 days, was discovered 01/09/2018 and was last detected 08/29/2018.
<br />
<img src="https://imgur.com/oiKr4sT.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

<br />
Window Server Configuration in compliance with security configuration standard documentation.As an internal PCI Assessor preparing for an upcoming assessment. Meeting with the window system admin to ensure servers have been configured to company security standards. Admin walks through several configurations for me to compare to the approved company security standards and identify instances of non compliance.
<br />
<img src="https://imgur.com/9MbCI4W.png" height="58%" width="58%" alt="Disk Sanitization Steps"/>

<br />
F5 Load Balancer Configuration Review : load balance not compliant with requirement 4.1. Use strong cryptography and security protocols to safeguard sensitive cardholder data during transmission over open, public networks, including the following: For the protocol in use to only support secure versions and configurations (that insecure versions or configurations are not supported).
<br />
<img src="https://imgur.com/G4ST3iu.png" height="58%" width="58%" alt="Disk Sanitization Steps"/>

<br />
Web Server Configuration Review: Web server non-compliant.Use strong cryptography and security protocols to safeguard sensitive cardholder data during transmission over open, public networks, including the following: For the protocol in use to only support secure versions and configurations (that insecure versions or configurations are not supported).
<br />
<img src="https://imgur.com/aWmdd7t.png" height="58%" width="58%" alt="Disk Sanitization Steps"/>

<br />
Scoping AWS Cloud: RTA is in scope, yet system hardening needs to be in place so PCI network isn't breached through weak RTA. Configurations should provide IP addresses since they are missing from the diagram.
<br/>
<img src="https://imgur.com/OORfQ7j.png" height="58%" width="58%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://imgur.com/gMrJoIX.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

<br />
Configurations that makes this McAfee compliant with PCI DSS Requirement 5.1.1 Ensure that anti-virus programs are capable of detecting, removing, and protecting against all known types of malicious software.5.1.1 Review vendor documentation and examine anti-virus configurations to verify that anti-virus programs; • Detect all known types of malicious software, • Remove all known types of malicious software, and • Protect against all known types of malicious software. Examples of types of malicious software include viruses, Trojans, worms, spyware, adware, and rootkits.
<br />
<img src="https://imgur.com/L5ZHygh.png" height="58%" width="58%" alt="Disk Sanitization Steps"/>

<br />
Network Firewall Configuration in Compliance with Security Policy Documentation: Cisco ASA Firewall. Identifying any findings on non-compliance.The firewall configuration is compared to approved ports, protocols and services in accordance with policy from the ITSecurity Department.The firewall has port 165 open and it has not been authorized by IT Security.

1.1.6 Documentation of business justification and approval for use of all services, protocols, and ports allowed, including documentation of security features implemented for those protocols considered to be insecure.
<br />
<img src="https://imgur.com/fc8NQRm.png" height="58%" width="58%" alt="Disk Sanitization Steps"/>


<br />
Configuration on the Red Hat system that is compliant with PCI DSS Requirement 8.1.6 Limit repeated access attempts by locking out the user ID after not more than six attempts.
<br />
<img src="https://imgur.com/Eqwpq1Y.png" height="58%" width="58%" alt="Disk Sanitization Steps"/>

<br />
Configuration on the Windows system that is Not compliant with PCI DSS Requirement 8.1.6
<br />
<img src="https://imgur.com/yOeFF7p.png" height="58%" width="58%" alt="Disk Sanitization Steps"/>




